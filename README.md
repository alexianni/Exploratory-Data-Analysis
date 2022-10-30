# SQL-Proyect

--- 


## Nombre, apellido y ciudad de clientes de brasil 

```
select 
cl.name, 
cl.lastname,
c.name as Ciudad
from clientes cl 
left join ciudades c on c.city_id = cl.city_id
order by 1;

```
- Output

<body>
<table border="1">
<tbody><tr>
<td bgcolor="silver" class="medium">name</td>
<td bgcolor="silver" class="medium">lastname</td>
<td bgcolor="silver" class="medium">Ciudad</td>
</tr>

<tr>
<td class="normal" valign="top">Alberto</td>
<td class="normal" valign="top">Maca</td>
<td class="normal" valign="top">san jose</td>
</tr>

<tr>
<td class="normal" valign="top">Alejandra</td>
<td class="normal" valign="top">Diaz</td>
<td class="normal" valign="top">guanajuato</td>
</tr>

<tr>
<td class="normal" valign="top">Ana</td>
<td class="normal" valign="top">Cuellar</td>
<td class="normal" valign="top">guadalajara</td>
</tr>

<tr>
<td class="normal" valign="top">Andrea</td>
<td class="normal" valign="top">Teran</td>
<td class="normal" valign="top">rio de janeiro</td>
</tr>

<tr>
<td class="normal" valign="top">Antonio</td>
<td class="normal" valign="top">Terraza</td>
<td class="normal" valign="top">guanajuato</td>
</tr>

<tr>
<td class="normal" valign="top">Cristina</td>
<td class="normal" valign="top">Tellez</td>
<td class="normal" valign="top">sao paolo</td>
</tr>

<tr>
<td class="normal" valign="top">Diana</td>
<td class="normal" valign="top">Canales</td>
<td class="normal" valign="top">santiago</td>
</tr>

<tr>
<td class="normal" valign="top">Diego</td>
<td class="normal" valign="top">Gonzalez</td>
<td class="normal" valign="top">guadalajara</td>
</tr>

<tr>
<td class="normal" valign="top">Elena</td>
<td class="normal" valign="top">Lechuga</td>
<td class="normal" valign="top">buenos aires</td>
</tr>

<tr>
<td class="normal" valign="top">Erica</td>
<td class="normal" valign="top">Cano</td>
<td class="normal" valign="top">san jose</td>
</tr>

<tr>
<td class="normal" valign="top">Francisco</td>
<td class="normal" valign="top">Merz</td>
<td class="normal" valign="top">brasilia</td>
</tr>

<tr>
<td class="normal" valign="top">Imanol</td>
<td class="normal" valign="top">Hernandez</td>
<td class="normal" valign="top">monterrey</td>
</tr>

<tr>
<td class="normal" valign="top">Inaki</td>
<td class="normal" valign="top">Merk</td>
<td class="normal" valign="top">brasilia</td>
</tr>

<tr>
<td class="normal" valign="top">Irene</td>
<td class="normal" valign="top">Perez</td>
<td class="normal" valign="top">guadalajara</td>
</tr>

<tr>
<td class="normal" valign="top">Jaime</td>
<td class="normal" valign="top">Moncalvo</td>
<td class="normal" valign="top">brasilia</td>
</tr>

<tr>
<td class="normal" valign="top">Javier</td>
<td class="normal" valign="top">Guzman</td>
<td class="normal" valign="top">chihuahua</td>
</tr>

<tr>
<td class="normal" valign="top">Jose</td>
<td class="normal" valign="top">Rodriguez</td>
<td class="normal" valign="top">merida</td>
</tr>

<tr>
<td class="normal" valign="top">Juan</td>
<td class="normal" valign="top">Perez</td>
<td class="normal" valign="top">guadalajara</td>
</tr>

<tr>
<td class="normal" valign="top">Juan Pablo</td>
<td class="normal" valign="top">Rodriguez</td>
<td class="normal" valign="top">leon</td>
</tr>

<tr>
<td class="normal" valign="top">Lea</td>
<td class="normal" valign="top">Blanco</td>
<td class="normal" valign="top">cdmx</td>
</tr>

<tr>
<td class="normal" valign="top">Maite</td>
<td class="normal" valign="top">Beazar</td>
<td class="normal" valign="top">cdmx</td>
</tr>

<tr>
<td class="normal" valign="top">Maria</td>
<td class="normal" valign="top">Nunez</td>
<td class="normal" valign="top">sao paolo</td>
</tr>

<tr>
<td class="normal" valign="top">Marina</td>
<td class="normal" valign="top">Hernandez</td>
<td class="normal" valign="top">brasilia</td>
</tr>

<tr>
<td class="normal" valign="top">Mario</td>
<td class="normal" valign="top">Mejia</td>
<td class="normal" valign="top">guadalajara</td>
</tr>

<tr>
<td class="normal" valign="top">Mercedes</td>
<td class="normal" valign="top">Salas</td>
<td class="normal" valign="top">cdmx</td>
</tr>

<tr>
<td class="normal" valign="top">Mercedes</td>
<td class="normal" valign="top">Garcia</td>
<td class="normal" valign="top">brasilia</td>
</tr>

<tr>
<td class="normal" valign="top">Mikel</td>
<td class="normal" valign="top">Perez</td>
<td class="normal" valign="top">rio de janeiro</td>
</tr>

<tr>
<td class="normal" valign="top">Pablo</td>
<td class="normal" valign="top">Golio</td>
<td class="normal" valign="top">merida</td>
</tr>

<tr>
<td class="normal" valign="top">Rodrigo</td>
<td class="normal" valign="top">Dieguez</td>
<td class="normal" valign="top">cdmx</td>
</tr>

<tr>
<td class="normal" valign="top">Rosario</td>
<td class="normal" valign="top">Arellano</td>
<td class="normal" valign="top">brasilia</td>
</tr>

<tr>
<td class="normal" valign="top">Santiago</td>
<td class="normal" valign="top">Torres</td>
<td class="normal" valign="top">merida</td>
</tr>

<tr>
<td class="normal" valign="top">Sebastian</td>
<td class="normal" valign="top">Castillo</td>
<td class="normal" valign="top">buenos aires</td>
</tr>
</tbody></table>

</body>

## Joins

### Inner Join

- Para cada orden se obtiene el id de la orden, la fecha, el id del producto y el nombre del producto.

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
- Output

<body>
<table border="1">
<tbody><tr>
<td bgcolor="silver" class="medium">order_id</td>
<td bgcolor="silver" class="medium">date_placed</td>
<td bgcolor="silver" class="medium">product_id</td>
<td bgcolor="silver" class="medium">Nombre_Producto</td>
</tr>

<tr>
<td class="normal" valign="top">1</td>
<td class="normal" valign="top">2020-06-15</td>
<td class="normal" valign="top">17</td>
<td class="normal" valign="top">kiwi</td>
</tr>

<tr>
<td class="normal" valign="top">2</td>
<td class="normal" valign="top">2020-08-02</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">brocoli</td>
</tr>

<tr>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">2020-09-09</td>
<td class="normal" valign="top">2</td>
<td class="normal" valign="top">lechuga</td>
</tr>

<tr>
<td class="normal" valign="top">4</td>
<td class="normal" valign="top">2020-09-16</td>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">toronja</td>
</tr>

<tr>
<td class="normal" valign="top">5</td>
<td class="normal" valign="top">2020-11-30</td>
<td class="normal" valign="top">12</td>
<td class="normal" valign="top">fresa</td>
</tr>

<tr>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">2020-12-11</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">manzana</td>
</tr>

<tr>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">2020-10-12</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">brocoli</td>
</tr>

<tr>
<td class="normal" valign="top">8</td>
<td class="normal" valign="top">2020-03-07</td>
<td class="normal" valign="top">11</td>
<td class="normal" valign="top">limon</td>
</tr>

<tr>
<td class="normal" valign="top">9</td>
<td class="normal" valign="top">2020-08-13</td>
<td class="normal" valign="top">4</td>
<td class="normal" valign="top">platano</td>
</tr>

<tr>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">2020-08-04</td>
<td class="normal" valign="top">1</td>
<td class="normal" valign="top">jitomate</td>
</tr>

<tr>
<td class="normal" valign="top">11</td>
<td class="normal" valign="top">2020-04-24</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">manzana</td>
</tr>

<tr>
<td class="normal" valign="top">12</td>
<td class="normal" valign="top">2020-01-10</td>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">papaya</td>
</tr>

<tr>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">2020-11-01</td>
<td class="normal" valign="top">8</td>
<td class="normal" valign="top">calabaza</td>
</tr>

<tr>
<td class="normal" valign="top">14</td>
<td class="normal" valign="top">2020-03-04</td>
<td class="normal" valign="top">17</td>
<td class="normal" valign="top">kiwi</td>
</tr>

<tr>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">2020-04-13</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">manzana</td>
</tr>

<tr>
<td class="normal" valign="top">16</td>
<td class="normal" valign="top">2020-08-20</td>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">uva</td>
</tr>

<tr>
<td class="normal" valign="top">17</td>
<td class="normal" valign="top">2020-02-09</td>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">papaya</td>
</tr>

<tr>
<td class="normal" valign="top">18</td>
<td class="normal" valign="top">2020-10-21</td>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">uva</td>
</tr>

<tr>
<td class="normal" valign="top">19</td>
<td class="normal" valign="top">2020-05-07</td>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">pepino</td>
</tr>

<tr>
<td class="normal" valign="top">20</td>
<td class="normal" valign="top">2020-08-28</td>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">toronja</td>
</tr>

<tr>
<td class="normal" valign="top">21</td>
<td class="normal" valign="top">2020-05-23</td>
<td class="normal" valign="top">9</td>
<td class="normal" valign="top">papa</td>
</tr>

<tr>
<td class="normal" valign="top">22</td>
<td class="normal" valign="top">2020-04-16</td>
<td class="normal" valign="top">12</td>
<td class="normal" valign="top">fresa</td>
</tr>

<tr>
<td class="normal" valign="top">23</td>
<td class="normal" valign="top">2020-09-30</td>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">pepino</td>
</tr>

<tr>
<td class="normal" valign="top">24</td>
<td class="normal" valign="top">2020-12-17</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">manzana</td>
</tr>

<tr>
<td class="normal" valign="top">25</td>
<td class="normal" valign="top">2020-01-01</td>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">uva</td>
</tr>

<tr>
<td class="normal" valign="top">26</td>
<td class="normal" valign="top">2020-10-20</td>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">toronja</td>
</tr>

<tr>
<td class="normal" valign="top">27</td>
<td class="normal" valign="top">2020-07-11</td>
<td class="normal" valign="top">4</td>
<td class="normal" valign="top">platano</td>
</tr>

<tr>
<td class="normal" valign="top">28</td>
<td class="normal" valign="top">2020-06-24</td>
<td class="normal" valign="top">4</td>
<td class="normal" valign="top">platano</td>
</tr>

<tr>
<td class="normal" valign="top">29</td>
<td class="normal" valign="top">2020-04-13</td>
<td class="normal" valign="top">5</td>
<td class="normal" valign="top">aguacate</td>
</tr>

<tr>
<td class="normal" valign="top">30</td>
<td class="normal" valign="top">2020-03-28</td>
<td class="normal" valign="top">8</td>
<td class="normal" valign="top">calabaza</td>
</tr>

<tr>
<td class="normal" valign="top">31</td>
<td class="normal" valign="top">2020-06-12</td>
<td class="normal" valign="top">14</td>
<td class="normal" valign="top">melon</td>
</tr>

<tr>
<td class="normal" valign="top">32</td>
<td class="normal" valign="top">2020-12-13</td>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">pepino</td>
</tr>

<tr>
<td class="normal" valign="top">33</td>
<td class="normal" valign="top">2020-06-07</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">brocoli</td>
</tr>

<tr>
<td class="normal" valign="top">34</td>
<td class="normal" valign="top">2020-04-30</td>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">toronja</td>
</tr>

<tr>
<td class="normal" valign="top">35</td>
<td class="normal" valign="top">2020-07-15</td>
<td class="normal" valign="top">9</td>
<td class="normal" valign="top">papa</td>
</tr>

<tr>
<td class="normal" valign="top">36</td>
<td class="normal" valign="top">2020-04-29</td>
<td class="normal" valign="top">5</td>
<td class="normal" valign="top">aguacate</td>
</tr>

<tr>
<td class="normal" valign="top">37</td>
<td class="normal" valign="top">2020-08-05</td>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">toronja</td>
</tr>

<tr>
<td class="normal" valign="top">38</td>
<td class="normal" valign="top">2020-01-26</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">brocoli</td>
</tr>

<tr>
<td class="normal" valign="top">39</td>
<td class="normal" valign="top">2020-11-12</td>
<td class="normal" valign="top">1</td>
<td class="normal" valign="top">jitomate</td>
</tr>

<tr>
<td class="normal" valign="top">40</td>
<td class="normal" valign="top">2020-04-17</td>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">uva</td>
</tr>

<tr>
<td class="normal" valign="top">41</td>
<td class="normal" valign="top">2020-01-05</td>
<td class="normal" valign="top">8</td>
<td class="normal" valign="top">calabaza</td>
</tr>

<tr>
<td class="normal" valign="top">42</td>
<td class="normal" valign="top">2020-01-05</td>
<td class="normal" valign="top">14</td>
<td class="normal" valign="top">melon</td>
</tr>

<tr>
<td class="normal" valign="top">43</td>
<td class="normal" valign="top">2020-07-30</td>
<td class="normal" valign="top">17</td>
<td class="normal" valign="top">kiwi</td>
</tr>

<tr>
<td class="normal" valign="top">44</td>
<td class="normal" valign="top">2020-07-12</td>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">pepino</td>
</tr>

<tr>
<td class="normal" valign="top">45</td>
<td class="normal" valign="top">2020-06-21</td>
<td class="normal" valign="top">11</td>
<td class="normal" valign="top">limon</td>
</tr>

<tr>
<td class="normal" valign="top">46</td>
<td class="normal" valign="top">2020-10-09</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">brocoli</td>
</tr>

<tr>
<td class="normal" valign="top">47</td>
<td class="normal" valign="top">2020-01-24</td>
<td class="normal" valign="top">1</td>
<td class="normal" valign="top">jitomate</td>
</tr>

<tr>
<td class="normal" valign="top">48</td>
<td class="normal" valign="top">2020-12-08</td>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">pepino</td>
</tr>

<tr>
<td class="normal" valign="top">49</td>
<td class="normal" valign="top">2020-08-06</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">manzana</td>
</tr>

<tr>
<td class="normal" valign="top">50</td>
<td class="normal" valign="top">2020-04-27</td>
<td class="normal" valign="top">5</td>
<td class="normal" valign="top">aguacate</td>
</tr>

<tr>
<td class="normal" valign="top">51</td>
<td class="normal" valign="top">2020-11-14</td>
<td class="normal" valign="top">9</td>
<td class="normal" valign="top">papa</td>
</tr>

<tr>
<td class="normal" valign="top">52</td>
<td class="normal" valign="top">2020-05-07</td>
<td class="normal" valign="top">11</td>
<td class="normal" valign="top">limon</td>
</tr>

<tr>
<td class="normal" valign="top">53</td>
<td class="normal" valign="top">2020-06-14</td>
<td class="normal" valign="top">1</td>
<td class="normal" valign="top">jitomate</td>
</tr>

<tr>
<td class="normal" valign="top">54</td>
<td class="normal" valign="top">2020-02-18</td>
<td class="normal" valign="top">9</td>
<td class="normal" valign="top">papa</td>
</tr>

<tr>
<td class="normal" valign="top">55</td>
<td class="normal" valign="top">2020-10-05</td>
<td class="normal" valign="top">1</td>
<td class="normal" valign="top">jitomate</td>
</tr>

<tr>
<td class="normal" valign="top">56</td>
<td class="normal" valign="top">2020-07-23</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">manzana</td>
</tr>

<tr>
<td class="normal" valign="top">57</td>
<td class="normal" valign="top">2020-09-22</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">brocoli</td>
</tr>

<tr>
<td class="normal" valign="top">58</td>
<td class="normal" valign="top">2020-11-17</td>
<td class="normal" valign="top">11</td>
<td class="normal" valign="top">limon</td>
</tr>

<tr>
<td class="normal" valign="top">59</td>
<td class="normal" valign="top">2020-04-27</td>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">uva</td>
</tr>

<tr>
<td class="normal" valign="top">60</td>
<td class="normal" valign="top">2020-08-04</td>
<td class="normal" valign="top">18</td>
<td class="normal" valign="top">zanahoria</td>
</tr>
</tbody></table>

</body>

###  Left join

- Para cada orden se obtiene el el id de la orden, el nombre del agricultor y su apellido.

```
select
o.order_id, 
a.name,
a.lastname
from ordenes o 
left join agricultores a on a.farmer_id = o.farmer_id 
order by 1;
```
- Output 

<body>
<table border="1">
<tbody><tr>
<td bgcolor="silver" class="medium">order_id</td>
<td bgcolor="silver" class="medium">name</td>
<td bgcolor="silver" class="medium">lastname</td>
</tr>

<tr>
<td class="normal" valign="top">1</td>
<td class="normal" valign="top">David</td>
<td class="normal" valign="top">Merk</td>
</tr>

<tr>
<td class="normal" valign="top">2</td>
<td class="normal" valign="top">Maria</td>
<td class="normal" valign="top">Hernandez</td>
</tr>

<tr>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">Diego</td>
<td class="normal" valign="top">Diaz</td>
</tr>

<tr>
<td class="normal" valign="top">4</td>
<td class="normal" valign="top">Tito</td>
<td class="normal" valign="top">Lechuga</td>
</tr>

<tr>
<td class="normal" valign="top">5</td>
<td class="normal" valign="top">Pedro</td>
<td class="normal" valign="top">Terraza</td>
</tr>

<tr>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">Tito</td>
<td class="normal" valign="top">Lechuga</td>
</tr>

<tr>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">Gabriela</td>
<td class="normal" valign="top">Guzman</td>
</tr>

<tr>
<td class="normal" valign="top">8</td>
<td class="normal" valign="top">Juan</td>
<td class="normal" valign="top">Arellano</td>
</tr>

<tr>
<td class="normal" valign="top">9</td>
<td class="normal" valign="top">Carlos</td>
<td class="normal" valign="top">Blanco</td>
</tr>

<tr>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">David</td>
<td class="normal" valign="top">Merk</td>
</tr>

<tr>
<td class="normal" valign="top">11</td>
<td class="normal" valign="top">Jaime</td>
<td class="normal" valign="top">Merz</td>
</tr>

<tr>
<td class="normal" valign="top">12</td>
<td class="normal" valign="top">Clara</td>
<td class="normal" valign="top">Beazar</td>
</tr>

<tr>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">Yann</td>
<td class="normal" valign="top">Rodriguez</td>
</tr>

<tr>
<td class="normal" valign="top">14</td>
<td class="normal" valign="top">Clara</td>
<td class="normal" valign="top">Beazar</td>
</tr>

<tr>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">Cristobal</td>
<td class="normal" valign="top">Nunez</td>
</tr>

<tr>
<td class="normal" valign="top">16</td>
<td class="normal" valign="top">Fernando</td>
<td class="normal" valign="top">Perez</td>
</tr>

<tr>
<td class="normal" valign="top">17</td>
<td class="normal" valign="top">Alejandro</td>
<td class="normal" valign="top">Torres</td>
</tr>

<tr>
<td class="normal" valign="top">18</td>
<td class="normal" valign="top">Alejandro</td>
<td class="normal" valign="top">Torres</td>
</tr>

<tr>
<td class="normal" valign="top">19</td>
<td class="normal" valign="top">Diego</td>
<td class="normal" valign="top">Diaz</td>
</tr>

<tr>
<td class="normal" valign="top">20</td>
<td class="normal" valign="top">Marina</td>
<td class="normal" valign="top">Golio</td>
</tr>

<tr>
<td class="normal" valign="top">21</td>
<td class="normal" valign="top">Ana</td>
<td class="normal" valign="top">Maca</td>
</tr>

<tr>
<td class="normal" valign="top">22</td>
<td class="normal" valign="top">Carlos</td>
<td class="normal" valign="top">Blanco</td>
</tr>

<tr>
<td class="normal" valign="top">23</td>
<td class="normal" valign="top">Alejandro</td>
<td class="normal" valign="top">Torres</td>
</tr>

<tr>
<td class="normal" valign="top">24</td>
<td class="normal" valign="top">Carlos</td>
<td class="normal" valign="top">Blanco</td>
</tr>

<tr>
<td class="normal" valign="top">25</td>
<td class="normal" valign="top">Jose</td>
<td class="normal" valign="top">Tellez</td>
</tr>

<tr>
<td class="normal" valign="top">26</td>
<td class="normal" valign="top">Ana</td>
<td class="normal" valign="top">Maca</td>
</tr>

<tr>
<td class="normal" valign="top">27</td>
<td class="normal" valign="top">Yann</td>
<td class="normal" valign="top">Rodriguez</td>
</tr>

<tr>
<td class="normal" valign="top">28</td>
<td class="normal" valign="top">Fernando</td>
<td class="normal" valign="top">Perez</td>
</tr>

<tr>
<td class="normal" valign="top">29</td>
<td class="normal" valign="top">Bernardo</td>
<td class="normal" valign="top">Castillo</td>
</tr>

<tr>
<td class="normal" valign="top">30</td>
<td class="normal" valign="top">Gabriela</td>
<td class="normal" valign="top">Guzman</td>
</tr>

<tr>
<td class="normal" valign="top">31</td>
<td class="normal" valign="top">Juan</td>
<td class="normal" valign="top">Arellano</td>
</tr>

<tr>
<td class="normal" valign="top">32</td>
<td class="normal" valign="top">Jorge</td>
<td class="normal" valign="top">Gonzalez</td>
</tr>

<tr>
<td class="normal" valign="top">33</td>
<td class="normal" valign="top">Yann</td>
<td class="normal" valign="top">Rodriguez</td>
</tr>

<tr>
<td class="normal" valign="top">34</td>
<td class="normal" valign="top">Ari</td>
<td class="normal" valign="top">Salas</td>
</tr>

<tr>
<td class="normal" valign="top">35</td>
<td class="normal" valign="top">Cristobal</td>
<td class="normal" valign="top">Nunez</td>
</tr>

<tr>
<td class="normal" valign="top">36</td>
<td class="normal" valign="top">Maria</td>
<td class="normal" valign="top">Hernandez</td>
</tr>

<tr>
<td class="normal" valign="top">37</td>
<td class="normal" valign="top">Ari</td>
<td class="normal" valign="top">Salas</td>
</tr>

<tr>
<td class="normal" valign="top">38</td>
<td class="normal" valign="top">David</td>
<td class="normal" valign="top">Merk</td>
</tr>

<tr>
<td class="normal" valign="top">39</td>
<td class="normal" valign="top">Andrea</td>
<td class="normal" valign="top">Perez</td>
</tr>

<tr>
<td class="normal" valign="top">40</td>
<td class="normal" valign="top">Clara</td>
<td class="normal" valign="top">Beazar</td>
</tr>

<tr>
<td class="normal" valign="top">41</td>
<td class="normal" valign="top">Alejandro</td>
<td class="normal" valign="top">Torres</td>
</tr>

<tr>
<td class="normal" valign="top">42</td>
<td class="normal" valign="top">Ana</td>
<td class="normal" valign="top">Maca</td>
</tr>

<tr>
<td class="normal" valign="top">43</td>
<td class="normal" valign="top">Maria</td>
<td class="normal" valign="top">Hernandez</td>
</tr>

<tr>
<td class="normal" valign="top">44</td>
<td class="normal" valign="top">Jose</td>
<td class="normal" valign="top">Tellez</td>
</tr>

<tr>
<td class="normal" valign="top">45</td>
<td class="normal" valign="top">Pedro</td>
<td class="normal" valign="top">Terraza</td>
</tr>

<tr>
<td class="normal" valign="top">46</td>
<td class="normal" valign="top">Gabriela</td>
<td class="normal" valign="top">Guzman</td>
</tr>

<tr>
<td class="normal" valign="top">47</td>
<td class="normal" valign="top">Fernando</td>
<td class="normal" valign="top">Perez</td>
</tr>

<tr>
<td class="normal" valign="top">48</td>
<td class="normal" valign="top">Cristobal</td>
<td class="normal" valign="top">Nunez</td>
</tr>

<tr>
<td class="normal" valign="top">49</td>
<td class="normal" valign="top">Juan</td>
<td class="normal" valign="top">Arellano</td>
</tr>

<tr>
<td class="normal" valign="top">50</td>
<td class="normal" valign="top">Jaime</td>
<td class="normal" valign="top">Merz</td>
</tr>

<tr>
<td class="normal" valign="top">51</td>
<td class="normal" valign="top">Juan</td>
<td class="normal" valign="top">Arellano</td>
</tr>

<tr>
<td class="normal" valign="top">52</td>
<td class="normal" valign="top">Yann</td>
<td class="normal" valign="top">Rodriguez</td>
</tr>

<tr>
<td class="normal" valign="top">53</td>
<td class="normal" valign="top">Daniel</td>
<td class="normal" valign="top">Dieguez</td>
</tr>

<tr>
<td class="normal" valign="top">54</td>
<td class="normal" valign="top">Bernardo</td>
<td class="normal" valign="top">Castillo</td>
</tr>

<tr>
<td class="normal" valign="top">55</td>
<td class="normal" valign="top">Jorge</td>
<td class="normal" valign="top">Gonzalez</td>
</tr>

<tr>
<td class="normal" valign="top">56</td>
<td class="normal" valign="top">Cristobal</td>
<td class="normal" valign="top">Nunez</td>
</tr>

<tr>
<td class="normal" valign="top">57</td>
<td class="normal" valign="top">Alejandro</td>
<td class="normal" valign="top">Torres</td>
</tr>

<tr>
<td class="normal" valign="top">58</td>
<td class="normal" valign="top">Jorge</td>
<td class="normal" valign="top">Gonzalez</td>
</tr>

<tr>
<td class="normal" valign="top">59</td>
<td class="normal" valign="top">Yann</td>
<td class="normal" valign="top">Rodriguez</td>
</tr>

<tr>
<td class="normal" valign="top">60</td>
<td class="normal" valign="top">Gabriela</td>
<td class="normal" valign="top">Guzman</td>
</tr>
</tbody></table>

</body>

### Multiples joins

- Para cada orden se obtiene el id de la orden, la fecha, el nombre y apellido del cliente al igual que el nombre y apellido del agricultor.

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

- Output 

<body>
<table border="1">
<tbody><tr>
<td bgcolor="silver" class="medium">order_id</td>
<td bgcolor="silver" class="medium">date_placed</td>
<td bgcolor="silver" class="medium">Nombre_Cliente</td>
<td bgcolor="silver" class="medium">Apellido_Cliente</td>
<td bgcolor="silver" class="medium">Nombre_Agricultor</td>
<td bgcolor="silver" class="medium">Apellido_agricultor</td>
</tr>

<tr>
<td class="normal" valign="top">1</td>
<td class="normal" valign="top">2020-06-15</td>
<td class="normal" valign="top">Juan</td>
<td class="normal" valign="top">Perez</td>
<td class="normal" valign="top">David</td>
<td class="normal" valign="top">Merk</td>
</tr>

<tr>
<td class="normal" valign="top">2</td>
<td class="normal" valign="top">2020-08-02</td>
<td class="normal" valign="top">Rosario</td>
<td class="normal" valign="top">Arellano</td>
<td class="normal" valign="top">Maria</td>
<td class="normal" valign="top">Hernandez</td>
</tr>

<tr>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">2020-09-09</td>
<td class="normal" valign="top">Mercedes</td>
<td class="normal" valign="top">Salas</td>
<td class="normal" valign="top">Diego</td>
<td class="normal" valign="top">Diaz</td>
</tr>

<tr>
<td class="normal" valign="top">4</td>
<td class="normal" valign="top">2020-09-16</td>
<td class="normal" valign="top">Cristina</td>
<td class="normal" valign="top">Tellez</td>
<td class="normal" valign="top">Tito</td>
<td class="normal" valign="top">Lechuga</td>
</tr>

<tr>
<td class="normal" valign="top">5</td>
<td class="normal" valign="top">2020-11-30</td>
<td class="normal" valign="top">Elena</td>
<td class="normal" valign="top">Lechuga</td>
<td class="normal" valign="top">Pedro</td>
<td class="normal" valign="top">Terraza</td>
</tr>

<tr>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">2020-12-11</td>
<td class="normal" valign="top">Sebastian</td>
<td class="normal" valign="top">Castillo</td>
<td class="normal" valign="top">Tito</td>
<td class="normal" valign="top">Lechuga</td>
</tr>

<tr>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">2020-10-12</td>
<td class="normal" valign="top">Diana</td>
<td class="normal" valign="top">Canales</td>
<td class="normal" valign="top">Gabriela</td>
<td class="normal" valign="top">Guzman</td>
</tr>

<tr>
<td class="normal" valign="top">8</td>
<td class="normal" valign="top">2020-03-07</td>
<td class="normal" valign="top">Mercedes</td>
<td class="normal" valign="top">Garcia</td>
<td class="normal" valign="top">Juan</td>
<td class="normal" valign="top">Arellano</td>
</tr>

<tr>
<td class="normal" valign="top">9</td>
<td class="normal" valign="top">2020-08-13</td>
<td class="normal" valign="top">Juan Pablo</td>
<td class="normal" valign="top">Rodriguez</td>
<td class="normal" valign="top">Carlos</td>
<td class="normal" valign="top">Blanco</td>
</tr>

<tr>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">2020-08-04</td>
<td class="normal" valign="top">Ana</td>
<td class="normal" valign="top">Cuellar</td>
<td class="normal" valign="top">David</td>
<td class="normal" valign="top">Merk</td>
</tr>

<tr>
<td class="normal" valign="top">11</td>
<td class="normal" valign="top">2020-04-24</td>
<td class="normal" valign="top">Antonio</td>
<td class="normal" valign="top">Terraza</td>
<td class="normal" valign="top">Jaime</td>
<td class="normal" valign="top">Merz</td>
</tr>

<tr>
<td class="normal" valign="top">12</td>
<td class="normal" valign="top">2020-01-10</td>
<td class="normal" valign="top">Irene</td>
<td class="normal" valign="top">Perez</td>
<td class="normal" valign="top">Clara</td>
<td class="normal" valign="top">Beazar</td>
</tr>

<tr>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">2020-11-01</td>
<td class="normal" valign="top">Mercedes</td>
<td class="normal" valign="top">Salas</td>
<td class="normal" valign="top">Yann</td>
<td class="normal" valign="top">Rodriguez</td>
</tr>

<tr>
<td class="normal" valign="top">14</td>
<td class="normal" valign="top">2020-03-04</td>
<td class="normal" valign="top">Juan Pablo</td>
<td class="normal" valign="top">Rodriguez</td>
<td class="normal" valign="top">Clara</td>
<td class="normal" valign="top">Beazar</td>
</tr>

<tr>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">2020-04-13</td>
<td class="normal" valign="top">Diana</td>
<td class="normal" valign="top">Canales</td>
<td class="normal" valign="top">Cristobal</td>
<td class="normal" valign="top">Nunez</td>
</tr>

<tr>
<td class="normal" valign="top">16</td>
<td class="normal" valign="top">2020-08-20</td>
<td class="normal" valign="top">Cristina</td>
<td class="normal" valign="top">Tellez</td>
<td class="normal" valign="top">Fernando</td>
<td class="normal" valign="top">Perez</td>
</tr>

<tr>
<td class="normal" valign="top">17</td>
<td class="normal" valign="top">2020-02-09</td>
<td class="normal" valign="top">Erica</td>
<td class="normal" valign="top">Cano</td>
<td class="normal" valign="top">Alejandro</td>
<td class="normal" valign="top">Torres</td>
</tr>

<tr>
<td class="normal" valign="top">18</td>
<td class="normal" valign="top">2020-10-21</td>
<td class="normal" valign="top">Antonio</td>
<td class="normal" valign="top">Terraza</td>
<td class="normal" valign="top">Alejandro</td>
<td class="normal" valign="top">Torres</td>
</tr>

<tr>
<td class="normal" valign="top">19</td>
<td class="normal" valign="top">2020-05-07</td>
<td class="normal" valign="top">Mikel</td>
<td class="normal" valign="top">Perez</td>
<td class="normal" valign="top">Diego</td>
<td class="normal" valign="top">Diaz</td>
</tr>

<tr>
<td class="normal" valign="top">20</td>
<td class="normal" valign="top">2020-08-28</td>
<td class="normal" valign="top">Mario</td>
<td class="normal" valign="top">Mejia</td>
<td class="normal" valign="top">Marina</td>
<td class="normal" valign="top">Golio</td>
</tr>

<tr>
<td class="normal" valign="top">21</td>
<td class="normal" valign="top">2020-05-23</td>
<td class="normal" valign="top">Juan Pablo</td>
<td class="normal" valign="top">Rodriguez</td>
<td class="normal" valign="top">Ana</td>
<td class="normal" valign="top">Maca</td>
</tr>

<tr>
<td class="normal" valign="top">22</td>
<td class="normal" valign="top">2020-04-16</td>
<td class="normal" valign="top">Maite</td>
<td class="normal" valign="top">Beazar</td>
<td class="normal" valign="top">Carlos</td>
<td class="normal" valign="top">Blanco</td>
</tr>

<tr>
<td class="normal" valign="top">23</td>
<td class="normal" valign="top">2020-09-30</td>
<td class="normal" valign="top">Mercedes</td>
<td class="normal" valign="top">Salas</td>
<td class="normal" valign="top">Alejandro</td>
<td class="normal" valign="top">Torres</td>
</tr>

<tr>
<td class="normal" valign="top">24</td>
<td class="normal" valign="top">2020-12-17</td>
<td class="normal" valign="top">Mario</td>
<td class="normal" valign="top">Mejia</td>
<td class="normal" valign="top">Carlos</td>
<td class="normal" valign="top">Blanco</td>
</tr>

<tr>
<td class="normal" valign="top">25</td>
<td class="normal" valign="top">2020-01-01</td>
<td class="normal" valign="top">Diego</td>
<td class="normal" valign="top">Gonzalez</td>
<td class="normal" valign="top">Jose</td>
<td class="normal" valign="top">Tellez</td>
</tr>

<tr>
<td class="normal" valign="top">26</td>
<td class="normal" valign="top">2020-10-20</td>
<td class="normal" valign="top">Irene</td>
<td class="normal" valign="top">Perez</td>
<td class="normal" valign="top">Ana</td>
<td class="normal" valign="top">Maca</td>
</tr>

<tr>
<td class="normal" valign="top">27</td>
<td class="normal" valign="top">2020-07-11</td>
<td class="normal" valign="top">Andrea</td>
<td class="normal" valign="top">Teran</td>
<td class="normal" valign="top">Yann</td>
<td class="normal" valign="top">Rodriguez</td>
</tr>

<tr>
<td class="normal" valign="top">28</td>
<td class="normal" valign="top">2020-06-24</td>
<td class="normal" valign="top">Alejandra</td>
<td class="normal" valign="top">Diaz</td>
<td class="normal" valign="top">Fernando</td>
<td class="normal" valign="top">Perez</td>
</tr>

<tr>
<td class="normal" valign="top">29</td>
<td class="normal" valign="top">2020-04-13</td>
<td class="normal" valign="top">Santiago</td>
<td class="normal" valign="top">Torres</td>
<td class="normal" valign="top">Bernardo</td>
<td class="normal" valign="top">Castillo</td>
</tr>

<tr>
<td class="normal" valign="top">30</td>
<td class="normal" valign="top">2020-03-28</td>
<td class="normal" valign="top">Juan</td>
<td class="normal" valign="top">Perez</td>
<td class="normal" valign="top">Gabriela</td>
<td class="normal" valign="top">Guzman</td>
</tr>

<tr>
<td class="normal" valign="top">31</td>
<td class="normal" valign="top">2020-06-12</td>
<td class="normal" valign="top">Diana</td>
<td class="normal" valign="top">Canales</td>
<td class="normal" valign="top">Juan</td>
<td class="normal" valign="top">Arellano</td>
</tr>

<tr>
<td class="normal" valign="top">32</td>
<td class="normal" valign="top">2020-12-13</td>
<td class="normal" valign="top">Erica</td>
<td class="normal" valign="top">Cano</td>
<td class="normal" valign="top">Jorge</td>
<td class="normal" valign="top">Gonzalez</td>
</tr>

<tr>
<td class="normal" valign="top">33</td>
<td class="normal" valign="top">2020-06-07</td>
<td class="normal" valign="top">Erica</td>
<td class="normal" valign="top">Cano</td>
<td class="normal" valign="top">Yann</td>
<td class="normal" valign="top">Rodriguez</td>
</tr>

<tr>
<td class="normal" valign="top">34</td>
<td class="normal" valign="top">2020-04-30</td>
<td class="normal" valign="top">Marina</td>
<td class="normal" valign="top">Hernandez</td>
<td class="normal" valign="top">Ari</td>
<td class="normal" valign="top">Salas</td>
</tr>

<tr>
<td class="normal" valign="top">35</td>
<td class="normal" valign="top">2020-07-15</td>
<td class="normal" valign="top">Mercedes</td>
<td class="normal" valign="top">Garcia</td>
<td class="normal" valign="top">Cristobal</td>
<td class="normal" valign="top">Nunez</td>
</tr>

<tr>
<td class="normal" valign="top">36</td>
<td class="normal" valign="top">2020-04-29</td>
<td class="normal" valign="top">Francisco</td>
<td class="normal" valign="top">Merz</td>
<td class="normal" valign="top">Maria</td>
<td class="normal" valign="top">Hernandez</td>
</tr>

<tr>
<td class="normal" valign="top">37</td>
<td class="normal" valign="top">2020-08-05</td>
<td class="normal" valign="top">Maite</td>
<td class="normal" valign="top">Beazar</td>
<td class="normal" valign="top">Ari</td>
<td class="normal" valign="top">Salas</td>
</tr>

<tr>
<td class="normal" valign="top">38</td>
<td class="normal" valign="top">2020-01-26</td>
<td class="normal" valign="top">Marina</td>
<td class="normal" valign="top">Hernandez</td>
<td class="normal" valign="top">David</td>
<td class="normal" valign="top">Merk</td>
</tr>

<tr>
<td class="normal" valign="top">39</td>
<td class="normal" valign="top">2020-11-12</td>
<td class="normal" valign="top">Rodrigo</td>
<td class="normal" valign="top">Dieguez</td>
<td class="normal" valign="top">Andrea</td>
<td class="normal" valign="top">Perez</td>
</tr>

<tr>
<td class="normal" valign="top">40</td>
<td class="normal" valign="top">2020-04-17</td>
<td class="normal" valign="top">Cristina</td>
<td class="normal" valign="top">Tellez</td>
<td class="normal" valign="top">Clara</td>
<td class="normal" valign="top">Beazar</td>
</tr>

<tr>
<td class="normal" valign="top">41</td>
<td class="normal" valign="top">2020-01-05</td>
<td class="normal" valign="top">Diana</td>
<td class="normal" valign="top">Canales</td>
<td class="normal" valign="top">Alejandro</td>
<td class="normal" valign="top">Torres</td>
</tr>

<tr>
<td class="normal" valign="top">42</td>
<td class="normal" valign="top">2020-01-05</td>
<td class="normal" valign="top">Mercedes</td>
<td class="normal" valign="top">Salas</td>
<td class="normal" valign="top">Ana</td>
<td class="normal" valign="top">Maca</td>
</tr>

<tr>
<td class="normal" valign="top">43</td>
<td class="normal" valign="top">2020-07-30</td>
<td class="normal" valign="top">Antonio</td>
<td class="normal" valign="top">Terraza</td>
<td class="normal" valign="top">Maria</td>
<td class="normal" valign="top">Hernandez</td>
</tr>

<tr>
<td class="normal" valign="top">44</td>
<td class="normal" valign="top">2020-07-12</td>
<td class="normal" valign="top">Jose</td>
<td class="normal" valign="top">Rodriguez</td>
<td class="normal" valign="top">Jose</td>
<td class="normal" valign="top">Tellez</td>
</tr>

<tr>
<td class="normal" valign="top">45</td>
<td class="normal" valign="top">2020-06-21</td>
<td class="normal" valign="top">Marina</td>
<td class="normal" valign="top">Hernandez</td>
<td class="normal" valign="top">Pedro</td>
<td class="normal" valign="top">Terraza</td>
</tr>

<tr>
<td class="normal" valign="top">46</td>
<td class="normal" valign="top">2020-10-09</td>
<td class="normal" valign="top">Irene</td>
<td class="normal" valign="top">Perez</td>
<td class="normal" valign="top">Gabriela</td>
<td class="normal" valign="top">Guzman</td>
</tr>

<tr>
<td class="normal" valign="top">47</td>
<td class="normal" valign="top">2020-01-24</td>
<td class="normal" valign="top">Francisco</td>
<td class="normal" valign="top">Merz</td>
<td class="normal" valign="top">Fernando</td>
<td class="normal" valign="top">Perez</td>
</tr>

<tr>
<td class="normal" valign="top">48</td>
<td class="normal" valign="top">2020-12-08</td>
<td class="normal" valign="top">Mario</td>
<td class="normal" valign="top">Mejia</td>
<td class="normal" valign="top">Cristobal</td>
<td class="normal" valign="top">Nunez</td>
</tr>

<tr>
<td class="normal" valign="top">49</td>
<td class="normal" valign="top">2020-08-06</td>
<td class="normal" valign="top">Elena</td>
<td class="normal" valign="top">Lechuga</td>
<td class="normal" valign="top">Juan</td>
<td class="normal" valign="top">Arellano</td>
</tr>

<tr>
<td class="normal" valign="top">50</td>
<td class="normal" valign="top">2020-04-27</td>
<td class="normal" valign="top">Elena</td>
<td class="normal" valign="top">Lechuga</td>
<td class="normal" valign="top">Jaime</td>
<td class="normal" valign="top">Merz</td>
</tr>

<tr>
<td class="normal" valign="top">51</td>
<td class="normal" valign="top">2020-11-14</td>
<td class="normal" valign="top">Pablo</td>
<td class="normal" valign="top">Golio</td>
<td class="normal" valign="top">Juan</td>
<td class="normal" valign="top">Arellano</td>
</tr>

<tr>
<td class="normal" valign="top">52</td>
<td class="normal" valign="top">2020-05-07</td>
<td class="normal" valign="top">Juan Pablo</td>
<td class="normal" valign="top">Rodriguez</td>
<td class="normal" valign="top">Yann</td>
<td class="normal" valign="top">Rodriguez</td>
</tr>

<tr>
<td class="normal" valign="top">53</td>
<td class="normal" valign="top">2020-06-14</td>
<td class="normal" valign="top">Ana</td>
<td class="normal" valign="top">Cuellar</td>
<td class="normal" valign="top">Daniel</td>
<td class="normal" valign="top">Dieguez</td>
</tr>

<tr>
<td class="normal" valign="top">54</td>
<td class="normal" valign="top">2020-02-18</td>
<td class="normal" valign="top">Rodrigo</td>
<td class="normal" valign="top">Dieguez</td>
<td class="normal" valign="top">Bernardo</td>
<td class="normal" valign="top">Castillo</td>
</tr>

<tr>
<td class="normal" valign="top">55</td>
<td class="normal" valign="top">2020-10-05</td>
<td class="normal" valign="top">Sebastian</td>
<td class="normal" valign="top">Castillo</td>
<td class="normal" valign="top">Jorge</td>
<td class="normal" valign="top">Gonzalez</td>
</tr>

<tr>
<td class="normal" valign="top">56</td>
<td class="normal" valign="top">2020-07-23</td>
<td class="normal" valign="top">Erica</td>
<td class="normal" valign="top">Cano</td>
<td class="normal" valign="top">Cristobal</td>
<td class="normal" valign="top">Nunez</td>
</tr>

<tr>
<td class="normal" valign="top">57</td>
<td class="normal" valign="top">2020-09-22</td>
<td class="normal" valign="top">Ana</td>
<td class="normal" valign="top">Cuellar</td>
<td class="normal" valign="top">Alejandro</td>
<td class="normal" valign="top">Torres</td>
</tr>

<tr>
<td class="normal" valign="top">58</td>
<td class="normal" valign="top">2020-11-17</td>
<td class="normal" valign="top">Sebastian</td>
<td class="normal" valign="top">Castillo</td>
<td class="normal" valign="top">Jorge</td>
<td class="normal" valign="top">Gonzalez</td>
</tr>

<tr>
<td class="normal" valign="top">59</td>
<td class="normal" valign="top">2020-04-27</td>
<td class="normal" valign="top">Ana</td>
<td class="normal" valign="top">Cuellar</td>
<td class="normal" valign="top">Yann</td>
<td class="normal" valign="top">Rodriguez</td>
</tr>

<tr>
<td class="normal" valign="top">60</td>
<td class="normal" valign="top">2020-08-04</td>
<td class="normal" valign="top">Marina</td>
<td class="normal" valign="top">Hernandez</td>
<td class="normal" valign="top">Gabriela</td>
<td class="normal" valign="top">Guzman</td>
</tr>
</tbody></table>

</body>


## Subquery

### Subquery en FROM.

- Nombre y apellido de los clientes que comparon lechuga

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
 - Output
 
 <body>
<table border="1">
<tbody><tr>
<td bgcolor="silver" class="medium">Nombre_Cliente</td>
</tr>

<tr>
<td class="normal" valign="top">Mercedes Salas</td>
</tr>
</tbody></table>

</body> 

### Subquery en WHERE

- Información sobre los agricultores pertenecientes al segmento "chico"
 
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
- Output 

<body>
<table border="1">
<tbody><tr>
<td bgcolor="silver" class="medium">name</td>
<td bgcolor="silver" class="medium">order_id</td>
<td bgcolor="silver" class="medium">price</td>
<td bgcolor="silver" class="medium">units</td>
</tr>

<tr>
<td class="normal" valign="top">Pedro</td>
<td class="normal" valign="top">45</td>
<td class="normal" valign="top">416</td>
<td class="normal" valign="top">23</td>
</tr>

<tr>
<td class="normal" valign="top">Ana</td>
<td class="normal" valign="top">42</td>
<td class="normal" valign="top">134</td>
<td class="normal" valign="top">11</td>
</tr>

<tr>
<td class="normal" valign="top">Andrea</td>
<td class="normal" valign="top">39</td>
<td class="normal" valign="top">142</td>
<td class="normal" valign="top">9</td>
</tr>

<tr>
<td class="normal" valign="top">Cristobal</td>
<td class="normal" valign="top">56</td>
<td class="normal" valign="top">414</td>
<td class="normal" valign="top">8</td>
</tr>

<tr>
<td class="normal" valign="top">Carlos</td>
<td class="normal" valign="top">24</td>
<td class="normal" valign="top">215</td>
<td class="normal" valign="top">8</td>
</tr>

<tr>
<td class="normal" valign="top">Jose</td>
<td class="normal" valign="top">44</td>
<td class="normal" valign="top">133</td>
<td class="normal" valign="top">6</td>
</tr>
</tbody></table>

</body>

### Query Anidada

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
- Output

<body>
<table border="1">
<tbody><tr>
<td bgcolor="silver" class="medium">Nombre_Agricultor</td>
<td bgcolor="silver" class="medium">Nombre_Ciudad</td>
</tr>

<tr>
<td class="normal" valign="top">Andrea Perez</td>
<td class="normal" valign="top">buenos aires</td>
</tr>

<tr>
<td class="normal" valign="top">Diego Diaz</td>
<td class="normal" valign="top">buenos aires</td>
</tr>

<tr>
<td class="normal" valign="top">Tito Lechuga</td>
<td class="normal" valign="top">buenos aires</td>
</tr>
</tbody></table>

</body>

### CTE 

- Información de los agricultores "grandes"

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

- Output

<body>
<table border="1">
<tbody><tr>
<td bgcolor="silver" class="medium">Nombre_agricultor</td>
<td bgcolor="silver" class="medium">order_id</td>
<td bgcolor="silver" class="medium">date_placed</td>
</tr>

<tr>
<td class="normal" valign="top">Maria Hernandez</td>
<td class="normal" valign="top">2</td>
<td class="normal" valign="top">2020-08-02</td>
</tr>

<tr>
<td class="normal" valign="top">Diego Diaz</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">2020-09-09</td>
</tr>

<tr>
<td class="normal" valign="top">Juan Arellano</td>
<td class="normal" valign="top">8</td>
<td class="normal" valign="top">2020-03-07</td>
</tr>

<tr>
<td class="normal" valign="top">Jaime Merz</td>
<td class="normal" valign="top">11</td>
<td class="normal" valign="top">2020-04-24</td>
</tr>

<tr>
<td class="normal" valign="top">Yann Rodriguez</td>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">2020-11-01</td>
</tr>

<tr>
<td class="normal" valign="top">Bernardo Castillo</td>
<td class="normal" valign="top">29</td>
<td class="normal" valign="top">2020-04-13</td>
</tr>

<tr>
<td class="normal" valign="top">Jorge Gonzalez</td>
<td class="normal" valign="top">32</td>
<td class="normal" valign="top">2020-12-13</td>
</tr>
</tbody></table>

</body>

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
- Output 

<body>
<table border="1">
<tbody><tr>
<td bgcolor="silver" class="medium">order_id</td>
<td bgcolor="silver" class="medium">date_placed</td>
<td bgcolor="silver" class="medium">price</td>
<td bgcolor="silver" class="medium">units</td>
<td bgcolor="silver" class="medium">city_id</td>
<td bgcolor="silver" class="medium">client_id</td>
<td bgcolor="silver" class="medium">farmer_id</td>
<td bgcolor="silver" class="medium">product_id</td>
<td bgcolor="silver" class="medium">city_id</td>
<td bgcolor="silver" class="medium">name</td>
<td bgcolor="silver" class="medium">country</td>
<td bgcolor="silver" class="medium">product_id</td>
<td bgcolor="silver" class="medium">name</td>
<td bgcolor="silver" class="medium">date_farmed</td>
</tr>

<tr>
<td class="normal" valign="top">2</td>
<td class="normal" valign="top">2020-08-02</td>
<td class="normal" valign="top">277</td>
<td class="normal" valign="top">18</td>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">26</td>
<td class="normal" valign="top">8</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">monterrey</td>
<td class="normal" valign="top">mexico</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">brocoli</td>
<td class="normal" valign="top">2020-11-13</td>
</tr>

<tr>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">2020-12-11</td>
<td class="normal" valign="top">267</td>
<td class="normal" valign="top">12</td>
<td class="normal" valign="top">1</td>
<td class="normal" valign="top">16</td>
<td class="normal" valign="top">22</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">1</td>
<td class="normal" valign="top">cdmx</td>
<td class="normal" valign="top">mexico</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">manzana</td>
<td class="normal" valign="top">2020-06-29</td>
</tr>

<tr>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">2020-10-12</td>
<td class="normal" valign="top">368</td>
<td class="normal" valign="top">9</td>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">24</td>
<td class="normal" valign="top">11</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">chihuahua</td>
<td class="normal" valign="top">mexico</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">brocoli</td>
<td class="normal" valign="top">2020-11-13</td>
</tr>

<tr>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">2020-11-01</td>
<td class="normal" valign="top">305</td>
<td class="normal" valign="top">18</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">20</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">8</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">queretaro</td>
<td class="normal" valign="top">mexico</td>
<td class="normal" valign="top">8</td>
<td class="normal" valign="top">calabaza</td>
<td class="normal" valign="top">2020-11-03</td>
</tr>

<tr>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">2020-04-13</td>
<td class="normal" valign="top">246</td>
<td class="normal" valign="top">9</td>
<td class="normal" valign="top">2</td>
<td class="normal" valign="top">24</td>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">2</td>
<td class="normal" valign="top">guanajuato</td>
<td class="normal" valign="top">mexico</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">manzana</td>
<td class="normal" valign="top">2020-06-29</td>
</tr>

<tr>
<td class="normal" valign="top">18</td>
<td class="normal" valign="top">2020-10-21</td>
<td class="normal" valign="top">260</td>
<td class="normal" valign="top">22</td>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">5</td>
<td class="normal" valign="top">12</td>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">monterrey</td>
<td class="normal" valign="top">mexico</td>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">uva</td>
<td class="normal" valign="top">2020-08-01</td>
</tr>

<tr>
<td class="normal" valign="top">22</td>
<td class="normal" valign="top">2020-04-16</td>
<td class="normal" valign="top">331</td>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">17</td>
<td class="normal" valign="top">18</td>
<td class="normal" valign="top">12</td>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">leon</td>
<td class="normal" valign="top">mexico</td>
<td class="normal" valign="top">12</td>
<td class="normal" valign="top">fresa</td>
<td class="normal" valign="top">2020-10-11</td>
</tr>

<tr>
<td class="normal" valign="top">24</td>
<td class="normal" valign="top">2020-12-17</td>
<td class="normal" valign="top">215</td>
<td class="normal" valign="top">8</td>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">31</td>
<td class="normal" valign="top">18</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">chihuahua</td>
<td class="normal" valign="top">mexico</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">manzana</td>
<td class="normal" valign="top">2020-06-29</td>
</tr>

<tr>
<td class="normal" valign="top">25</td>
<td class="normal" valign="top">2020-01-01</td>
<td class="normal" valign="top">106</td>
<td class="normal" valign="top">25</td>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">20</td>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">monterrey</td>
<td class="normal" valign="top">mexico</td>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">uva</td>
<td class="normal" valign="top">2020-08-01</td>
</tr>

<tr>
<td class="normal" valign="top">45</td>
<td class="normal" valign="top">2020-06-21</td>
<td class="normal" valign="top">416</td>
<td class="normal" valign="top">23</td>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">32</td>
<td class="normal" valign="top">2</td>
<td class="normal" valign="top">11</td>
<td class="normal" valign="top">7</td>
<td class="normal" valign="top">chihuahua</td>
<td class="normal" valign="top">mexico</td>
<td class="normal" valign="top">11</td>
<td class="normal" valign="top">limon</td>
<td class="normal" valign="top">2020-12-13</td>
</tr>

<tr>
<td class="normal" valign="top">57</td>
<td class="normal" valign="top">2020-09-22</td>
<td class="normal" valign="top">132</td>
<td class="normal" valign="top">23</td>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">22</td>
<td class="normal" valign="top">12</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">leon</td>
<td class="normal" valign="top">mexico</td>
<td class="normal" valign="top">3</td>
<td class="normal" valign="top">brocoli</td>
<td class="normal" valign="top">2020-11-13</td>
</tr>

<tr>
<td class="normal" valign="top">59</td>
<td class="normal" valign="top">2020-04-27</td>
<td class="normal" valign="top">159</td>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">1</td>
<td class="normal" valign="top">22</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">1</td>
<td class="normal" valign="top">cdmx</td>
<td class="normal" valign="top">mexico</td>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">uva</td>
<td class="normal" valign="top">2020-08-01</td>
</tr>
</tbody></table>

</body>


## Window functions

### Partition

- Clientes que más compran por ciudad

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

- Output 

<body>
<table border="1">
<tbody><tr>
<td bgcolor="silver" class="medium">Nombre_Cliente</td>
<td bgcolor="silver" class="medium">Ciudad</td>
<td bgcolor="silver" class="medium">Total_compras</td>
<td bgcolor="silver" class="medium">Ranking</td>
</tr>

<tr>
<td class="normal" valign="top">Marina Hernandez</td>
<td class="normal" valign="top">brasilia</td>
<td class="normal" valign="top">1086</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Francisco Merz</td>
<td class="normal" valign="top">brasilia</td>
<td class="normal" valign="top">664</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Mercedes Garcia</td>
<td class="normal" valign="top">brasilia</td>
<td class="normal" valign="top">398</td>
<td class="normal" valign="top">3</td>
</tr>

<tr>
<td class="normal" valign="top">Rosario Arellano</td>
<td class="normal" valign="top">brasilia</td>
<td class="normal" valign="top">277</td>
<td class="normal" valign="top">4</td>
</tr>

<tr>
<td class="normal" valign="top">Jaime Moncalvo</td>
<td class="normal" valign="top">brasilia</td>
<td class="normal" valign="top">NULL</td>
<td class="normal" valign="top">5</td>
</tr>

<tr>
<td class="normal" valign="top">Inaki Merk</td>
<td class="normal" valign="top">brasilia</td>
<td class="normal" valign="top">NULL</td>
<td class="normal" valign="top">5</td>
</tr>

<tr>
<td class="normal" valign="top">Sebastian Castillo</td>
<td class="normal" valign="top">buenos aires</td>
<td class="normal" valign="top">772</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Elena Lechuga</td>
<td class="normal" valign="top">buenos aires</td>
<td class="normal" valign="top">750</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Mercedes Salas</td>
<td class="normal" valign="top">cdmx</td>
<td class="normal" valign="top">936</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Maite Beazar</td>
<td class="normal" valign="top">cdmx</td>
<td class="normal" valign="top">683</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Rodrigo Dieguez</td>
<td class="normal" valign="top">cdmx</td>
<td class="normal" valign="top">319</td>
<td class="normal" valign="top">3</td>
</tr>

<tr>
<td class="normal" valign="top">Lea Blanco</td>
<td class="normal" valign="top">cdmx</td>
<td class="normal" valign="top">NULL</td>
<td class="normal" valign="top">4</td>
</tr>

<tr>
<td class="normal" valign="top">Javier Guzman</td>
<td class="normal" valign="top">chihuahua</td>
<td class="normal" valign="top">NULL</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Irene Perez</td>
<td class="normal" valign="top">guadalajara</td>
<td class="normal" valign="top">1282</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Ana Cuellar</td>
<td class="normal" valign="top">guadalajara</td>
<td class="normal" valign="top">856</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Mario Mejia</td>
<td class="normal" valign="top">guadalajara</td>
<td class="normal" valign="top">730</td>
<td class="normal" valign="top">3</td>
</tr>

<tr>
<td class="normal" valign="top">Juan Perez</td>
<td class="normal" valign="top">guadalajara</td>
<td class="normal" valign="top">520</td>
<td class="normal" valign="top">4</td>
</tr>

<tr>
<td class="normal" valign="top">Diego Gonzalez</td>
<td class="normal" valign="top">guadalajara</td>
<td class="normal" valign="top">106</td>
<td class="normal" valign="top">5</td>
</tr>

<tr>
<td class="normal" valign="top">Antonio Terraza</td>
<td class="normal" valign="top">guanajuato</td>
<td class="normal" valign="top">544</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Alejandra Diaz</td>
<td class="normal" valign="top">guanajuato</td>
<td class="normal" valign="top">113</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Juan Pablo Rodriguez</td>
<td class="normal" valign="top">leon</td>
<td class="normal" valign="top">1290</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Santiago Torres</td>
<td class="normal" valign="top">merida</td>
<td class="normal" valign="top">442</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Pablo Golio</td>
<td class="normal" valign="top">merida</td>
<td class="normal" valign="top">359</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Jose Rodriguez</td>
<td class="normal" valign="top">merida</td>
<td class="normal" valign="top">133</td>
<td class="normal" valign="top">3</td>
</tr>

<tr>
<td class="normal" valign="top">Imanol Hernandez</td>
<td class="normal" valign="top">monterrey</td>
<td class="normal" valign="top">NULL</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Andrea Teran</td>
<td class="normal" valign="top">rio de janeiro</td>
<td class="normal" valign="top">249</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Mikel Perez</td>
<td class="normal" valign="top">rio de janeiro</td>
<td class="normal" valign="top">211</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Erica Cano</td>
<td class="normal" valign="top">san jose</td>
<td class="normal" valign="top">1408</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Alberto Maca</td>
<td class="normal" valign="top">san jose</td>
<td class="normal" valign="top">NULL</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Diana Canales</td>
<td class="normal" valign="top">santiago</td>
<td class="normal" valign="top">1080</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Cristina Tellez</td>
<td class="normal" valign="top">sao paolo</td>
<td class="normal" valign="top">925</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Maria Nunez</td>
<td class="normal" valign="top">sao paolo</td>
<td class="normal" valign="top">NULL</td>
<td class="normal" valign="top">2</td>
</tr>
</tbody></table>

</body>


### CTE + Window Function

- Dos productos más vendidos por cada agricultor

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
- Output 

<body>
<table border="1">
<tbody><tr>
<td bgcolor="silver" class="medium">Nombre_agricultor</td>
<td bgcolor="silver" class="medium">Producto</td>
<td bgcolor="silver" class="medium">Unidades_Vendidas</td>
<td bgcolor="silver" class="medium">ranking</td>
</tr>

<tr>
<td class="normal" valign="top">Alejandro Torres</td>
<td class="normal" valign="top">brocoli</td>
<td class="normal" valign="top">23</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Alejandro Torres</td>
<td class="normal" valign="top">calabaza</td>
<td class="normal" valign="top">23</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Ana Maca</td>
<td class="normal" valign="top">papa</td>
<td class="normal" valign="top">21</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Ana Maca</td>
<td class="normal" valign="top">toronja</td>
<td class="normal" valign="top">12</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Andrea Perez</td>
<td class="normal" valign="top">jitomate</td>
<td class="normal" valign="top">9</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Ari Salas</td>
<td class="normal" valign="top">toronja</td>
<td class="normal" valign="top">38</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Bernardo Castillo</td>
<td class="normal" valign="top">papa</td>
<td class="normal" valign="top">23</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Bernardo Castillo</td>
<td class="normal" valign="top">aguacate</td>
<td class="normal" valign="top">11</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Carlos Blanco</td>
<td class="normal" valign="top">manzana</td>
<td class="normal" valign="top">8</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Carlos Blanco</td>
<td class="normal" valign="top">fresa</td>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Clara Beazar</td>
<td class="normal" valign="top">uva</td>
<td class="normal" valign="top">25</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Clara Beazar</td>
<td class="normal" valign="top">papaya</td>
<td class="normal" valign="top">25</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Cristobal Nunez</td>
<td class="normal" valign="top">pepino</td>
<td class="normal" valign="top">23</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Cristobal Nunez</td>
<td class="normal" valign="top">papa</td>
<td class="normal" valign="top">23</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Daniel Dieguez</td>
<td class="normal" valign="top">jitomate</td>
<td class="normal" valign="top">16</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">David Merk</td>
<td class="normal" valign="top">kiwi</td>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">David Merk</td>
<td class="normal" valign="top">brocoli</td>
<td class="normal" valign="top">14</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Diego Diaz</td>
<td class="normal" valign="top">pepino</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Diego Diaz</td>
<td class="normal" valign="top">lechuga</td>
<td class="normal" valign="top">10</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Fernando Perez</td>
<td class="normal" valign="top">jitomate</td>
<td class="normal" valign="top">24</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Fernando Perez</td>
<td class="normal" valign="top">uva</td>
<td class="normal" valign="top">22</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Gabriela Guzman</td>
<td class="normal" valign="top">brocoli</td>
<td class="normal" valign="top">33</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Gabriela Guzman</td>
<td class="normal" valign="top">zanahoria</td>
<td class="normal" valign="top">14</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Jaime Merz</td>
<td class="normal" valign="top">aguacate</td>
<td class="normal" valign="top">17</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Jaime Merz</td>
<td class="normal" valign="top">manzana</td>
<td class="normal" valign="top">13</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Jorge Gonzalez</td>
<td class="normal" valign="top">jitomate</td>
<td class="normal" valign="top">22</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Jorge Gonzalez</td>
<td class="normal" valign="top">pepino</td>
<td class="normal" valign="top">18</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Jose Tellez</td>
<td class="normal" valign="top">uva</td>
<td class="normal" valign="top">25</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Jose Tellez</td>
<td class="normal" valign="top">pepino</td>
<td class="normal" valign="top">6</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Juan Arellano</td>
<td class="normal" valign="top">limon</td>
<td class="normal" valign="top">22</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Juan Arellano</td>
<td class="normal" valign="top">papa</td>
<td class="normal" valign="top">20</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Maria Hernandez</td>
<td class="normal" valign="top">aguacate</td>
<td class="normal" valign="top">21</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Maria Hernandez</td>
<td class="normal" valign="top">brocoli</td>
<td class="normal" valign="top">18</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Marina Golio</td>
<td class="normal" valign="top">toronja</td>
<td class="normal" valign="top">19</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Pedro Terraza</td>
<td class="normal" valign="top">limon</td>
<td class="normal" valign="top">23</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Pedro Terraza</td>
<td class="normal" valign="top">fresa</td>
<td class="normal" valign="top">11</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Tito Lechuga</td>
<td class="normal" valign="top">toronja</td>
<td class="normal" valign="top">17</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Tito Lechuga</td>
<td class="normal" valign="top">manzana</td>
<td class="normal" valign="top">12</td>
<td class="normal" valign="top">2</td>
</tr>

<tr>
<td class="normal" valign="top">Yann Rodriguez</td>
<td class="normal" valign="top">calabaza</td>
<td class="normal" valign="top">18</td>
<td class="normal" valign="top">1</td>
</tr>

<tr>
<td class="normal" valign="top">Yann Rodriguez</td>
<td class="normal" valign="top">uva</td>
<td class="normal" valign="top">15</td>
<td class="normal" valign="top">2</td>
</tr>
</tbody></table>

</body>
