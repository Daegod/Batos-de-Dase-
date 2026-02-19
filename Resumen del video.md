

<h1> Diseño logico de bases de datos relacionales </h1>

Diseño conceptual --> diagramas de entidad relación

<h2> ¿Que busca el diseño logico? </h2>

Proponer una o más soluciones a uno o más problemas que se basen en un modelo de datos
definiendo también tablas, atributos y claves.

El modelo relacional se basa en tablas. Es un concepto muy intuitivo.

El esquema logico dibuja la estructura de las tablas que nos dicen qué estructura tiene la 
información.


<h3 style="color:red;">
►Cada entidad del esquema es una tabla del esquema lógico </h3>
 -Si tenemos un atributo clave, esa es nuestra Primary Key.
 
<h3>
►Las relaciones n:n (muchos a muchos) se hacen en una tabla nueva </h3>
 -La clave primaria de estas nuevas tablas son claves compuestas conformadas por
  la primary key de dos campos o más.
 -Surgen claves ajenas que apuntan a la entidad de la cual fue heredada cada una
  de las Primary Key tomadas para crear la Clave Compuesta. No cambian, simplemente
  son atributos que referencian la Primary Key de algo que ya existe.

<h3>
►Las relaciones 1:n (uno a muchos) se incluyen en la tabla de cardinalidad. n </h3>
 -En estas relaciones, la clave primaria de "1" se convierte en la clave foránea
  en "N" además de que se ven también como claves ajenas. "N" sigue teniendo su
  propia Primary Key.
 -Solo relacionan el contenido de una tabla con el de otras.

El diseño logico nos ayuda a buscar una estructura de las tablas que nos darán solución
al problema, además de también solventar todo lo que se postula en necesidades,
dándonos así también soluciones correctas.
