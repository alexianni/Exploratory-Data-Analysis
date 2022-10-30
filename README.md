# SQL-Proyect

--- 


--  Nombre, apellido y ciudad de clientes de brasil 

```
select 
cl.name, 
cl.lastname,
c.name as Ciudad
from clientes cl 
left join ciudades c on c.city_id = cl.city_id
order by 1;

```

-- Inner Join

```
select 
o.order_id ,
o.date_placed, 
o.product_id, 
p.name as Nombre_Producto
from ordenes o
inner join productos p on p.product_id = o.product_id
order by 1;
```

-- Left join

```
select
o.order_id, 
a.name,
a.lastname
from ordenes o 
left join agricultores a on a.farmer_id = o.farmer_id 
order by 1;
```

-- Multiples joins

```
select 
o.order_id,
o.date_placed,
cl.name as Nombre_Cliente,
cl.lastname as Apellido_Cliente,
a.name as Nombre_Agricultor,
a.lastname as Apellido_agricultor
from ordenes o
left join clientes cl on cl.client_id = o.client_id
left join agricultores a on a.farmer_id = o.farmer_id
order by 1;
```

/* Avance 3 */ 

-- Subquery en FROM. Nombre y apellido de los clientes que comparon lechuga

```
Select
Nombre_Cliente
from (select o.order_id, 
 p.name as producto,
 concat(cl.name, " ", cl.lastname) as Nombre_Cliente
 from ordenes o 
 left join clientes cl on cl.client_id = o.client_id
 left join productos p on p.product_id = o.product_id )
 as a 
 where producto = "lechuga";
 ```
 
 -- Subquery en WHERE. Información sobre los agricultores pertenecientes al segmento "chico"
 
 ```
select 
a.name,
o.order_id,
o.price, 
o.units
from ordenes o
right join agricultores a on a.farmer_id = o.farmer_id
where a.farmer_id in (select farmer_id from agricultores where segment = "chico")
group by 1;
```

-- Query Anidada

```
SELECT
concat(a.name, " ", a.lastname) as Nombre_Agricultor,
c.name as Nombre_Ciudad
FROM Agricultores a
left join ciudades c on a.city_id = c.city_id
WHERE c.name IN ( SELECT name
FROM ( SELECT * FROM ciudades 
) as a 
where country = "Argentina"
);
```

-- CTE. Información de los agricultores "grandes"

```
with agricultores_grandes as (select * from agricultores where segment = "grande") 
```
```
select
concat(ag.name, " ", ag.lastname) as Nombre_agricultor, 
o.order_id,
o.date_placed
from agricultores_grandes ag
inner join ordenes o on o.farmer_id = ag.farmer_id 
group by 1;
```

-- Multiples CTEs
```
with ciudades_Mexico as (select * from ciudades where country= "Mexico"), 
Productos_junio2020 as (select * from productos where date_farmed >= "2020-06-01" )
```
```
select * from ordenes o 
right join ciudades_Mexico cm on cm.city_id = o.city_id
right join Productos_junio2020 pj on pj.product_id = o.product_id
order by order_id;
```

-- Avance 4

-- Partition. Clientes que más compran por ciudad

```
with Clientes_por_ciudad as (select  concat(cl.name, " ", cl.lastname) as Nombre_Cliente, 
c.name as Ciudad, 
sum(o.price) as Total_compras
from clientes cl
left join ciudades c on c.city_id = cl.city_id
left join ordenes o on o.client_id = cl.client_id
group by 1 
order by 3)
```
```
select 
Nombre_Cliente,
Ciudad,
Total_compras,
rank() over(partition by Ciudad order by Total_Compras desc) as Ranking
from Clientes_por_ciudad;
```

-- CTE + Window Function. Dos productos más vendidos por cada agricultor

```
with window_rank as(
select 
concat(a.name, " ", a.lastname) as Nombre_agricultor,
p.name as Producto,
sum(o.units) Unidades_Vendidas,
row_number() over( partition by  a.farmer_id order by sum(o.units) desc) as ranking
from agricultores a
left join ordenes o on a.farmer_id = o.farmer_id
left join productos p on p.product_id = o.product_id
group by 1, p.product_id
order by 1
)
```

```
select *
from window_rank
where ranking in (1,2)
order by Nombre_Agricultor, ranking;
```
