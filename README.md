Este proyecto es desarrollado para la prueba tecnica de Metabiblioteca

Configuracion de base da datos:

Sobre archivo config. php en carpeta principal del proyecto

Configuacion de variables para coneccion -> Funcion coinstructora del objeto Connection
Nombre de tabla en base de datos - prueba_meta

Se agregan sql con tablas 
author -> author.sql
book -> book.sql

___________________________________________________________________________

El proyecto fue creado sobre PHP Nativo, no nesecita ningun Framework o libreria externa

Se sigue el patron de diseño Modelo Vista Controlador

Se hace creacion de Router router.php para manejo de paths a rutas del proyecto 
___________________________________________________________________________

Se añade una parte de frontend para realizar las peticiones

sobre las rutas

___________________________________________________________________________
FORMULARIO FRONTEND PARA REALIZAR PETICIONES

/metabiblioteca/books -> Agrega Libros

/metabiblioteca/authors -> Agrega Autores

___________________________________________________________________________

PETICIONES

POST -> /metabiblioteca/setbooks -> Agregar libros a base de datos
POST -> /metabiblioteca/setauthors -> Agregar Autores a base de datos
GET-> /metabiblioteca/getbooks -> Mostrar Json con libros y sus autores
