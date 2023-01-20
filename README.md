Proyecto POS (Point Of Sale)

El código elaborado en este repositorio está pensado para ser utilizado por el lenguaje de programación de Python.
El crador de Python es Guido van Rossum y fue desarrollado como un proyecto de código, el cual es administrado por la empresa Python software Foundation
Este lenguaje ha sido diseñado para ser fácil de leer y simple de implementar.

Dentro de este lenguaje de programación se encuentran diversas librerías que fueron utilizadas para el proceso de creación de código, entre ellas tkinter, matplotlib, 
werkzeug y mysqlconnector.

Tkinter

Es una fina capa orientada a objetos que funciona para la creación y desarrollo de aplicaciones de escirtorio; facilita el posicionamiento y desarrollo de una
interfaz gráfica. TK se describe a sí mismo como el único toolkit o kit de herramientas para el desarrollo de una interfaz gráfica de usuario.

Matplotlib

Es la biblioteca de trazado 2D que produce figuras con calidad de publicación en una variedad de formatos impresos y entornos interactivos en todas las plataformas.
Puede generar diagramas, histogramas, espectros de potencia, gráficos de barras, gráficos de error, diagramas de dispersión, etc., con solo unas pocas líneas de código.

Werkzeug

La librería específica que se utilizó en este prograa fue werkzeug.security, el cual nos permite realizar la encriptación de las contraseñas dentro de nuestro sistema
de base de datos y también interpretar las encriptaciones.

mysqlconnector

Esta libería solo se encarga de conectar el programa en cuestión a la base de datos con el que trabajará el sistema.

Ya explicadas las librerías que se utilizan en el programa, se abordarán algunos aspectos del mismo para explicar su funcionamiento.

Funcionalidad.

De primera mano, al ejecutar el cógido, este se vinculará a la base de datos y posteriormente se visualizará una pequeña ventana para ingresar la contraseña general
del programa (la que permitirá el acceso), seguidamente de ello, se solicitará un usuario y una contraseña, los cuales se encuentran en la base de datos; al completar
estos pasos de manera exitosa, el usuario tendrá acceso al programa que está dividido en varias secciones.

Antes que nada, se debe tomar en cuenta que el programa está limitado según el usuario que ingrese al sistema, existiendo tres tipos: vendedor, supervisor y administrador.

Aparece una pantalla con la función de realizar ventas, a partir de los productos que se encuentren dentro de la base de datos; las ventas que se lleven a cabo
van a liberar una calculadora la cual va a estimar el residuo del cambio en contraste con el importe total de la venta. En esta misma pantalla habrá acceso a 
otros sectores que tienen propósitos distintos.

El usuario podrá ingresar clientes (estos clientes son los que decden estar dentro del sistema para recibir ciertos beneficios especiales), modificarlos o eliminarlos,
según sea el caso. Así mismo, podrá realizar una búsqueda de los cientes que haya disponibles dentro de la tabla con ayuda de ña base de datos.

En otros aspectos, el usuario será capaz de revisar su inventarios, el cual se va actualizando con las ventas y las compras que se vayan ejecutando a la largo del
tiempo de vida del software, así mismo, el usuario tendrá la posibilidad de dar alta de pedidos se compras y organizar los productos que va adquirir del proveedor;
del mismo modo, existe un apartado en donde el usuario será capaz de visualizar un reporte de las ventas e ingreso de los clientes en un
timepo personalizado por medio de una gráfica de barras.

El usuario de alto rango será el que tenga la capacidad de agregar, modificar o eliminar usuarios dentro del sistema.



