# Estructuras_de_Archivos
Proyecto Realizado para la Materia de Estructuras de Archivos
En este proyecto se programa como guardar archivos e información en ellos, simlando de manera basica estructural
el funcionamiento de una base de datos, esta información incluye Metadatos de la información (Esquema), los cuales nos describen la estructura de los datos que se almacenan, Entidades (Tablas) y Atributos (Campos de la tabla), tambien se implementan algoritmos
de busqueda mediante indexación de los datos, a continuación se muestra la definición de algunos algoritmos de indexación, de estos fueron implementados (Secuancial Indexado, Índice Primario, Índice Secundario y Árbol B+).

-  Archivos secuenciales indexados: Se usan en aquellas
aplicaciones que demandan un procesamiento secuencial del archivo completo, así como
un acceso directo a sus registros.

- Índice primario: El índice primario de un archivo permite acceder a cada uno de los registros del
archivo mediante una clave primaria exclusiva.

- índice secundario: Los índices secundarios deben ser densos, con una entrada en el
índice por cada valor de la clave de búsqueda, y un puntero a cada registro del archivo. 

- índices de árbol B+: La estructura de índice de árbol B+ es la más extendida de las estructuras de índices
que mantienen su eficiencia a pesar de la inserción y borrado de datos. Un índice de árbol
B+ toma la forma de un árbol equilibrado donde los caminos de la raíz a cada hoja del
árbol son de la misma longitud.

- Organización de archivos multillave: Los archivos multillave o multilista, mantienen un índice para cada clave secundaria. La
organización de archivos multilista difiere de a inversión en que mientras en la entrada
en el índice de inversión para un valor de clave tienen un apuntador a cada registro de
datos con ese valor de la clave, la entrada en el índice multillave para un valor de la clave
tiene solo un apuntador al primer registro de datos con ese valor de la clave de búsqueda.
Este registro de datos contiene un apuntador al siguiente registro de datos con ese valor
de clave y así sucesivamente.

- Hash: Son estructuras de datos que se utilizan para almacenar un número elevado de datos
sobre los que se necesitan operaciones de búsqueda e inserción muy eficientes. Una
tabla hash almacena un conjunto de pares “(clave, valor)”. La clave es única para
cada elemento de la tabla y es el dato que se utiliza para buscar un determinado
valor.