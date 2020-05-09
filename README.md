<<<<<<< HEAD
# TiendaASPNet
=======
# TiendaASPNet2.1

Viernes 08 de mayo de 2020.

Proyecto de una aplicación web en ASP.NET Core con C#, como parte de una práctica de Bases de Datos, originalmente publicado por el usuario en GitHub jquevedo1196.

El desarrollo está hecho con ASP.NET Core 3.0.0 framework en lenguaje C#, utilizando las herramientas de Entity Framework; Se implementa también una conexión a una Base de Datos, utilizando SQL Express como sistema gestor; La conexión se realiza mediante autenticación de Windows (conexión por default).

La aplicación web se basa en el funcionamiento de una tienda, que permite la visualización de una Base de Datos relacional. La aplicación permite la visualización y, para algunos casos, edición y actualización de Proveedores, Marcas, Productos, Inventario y Ventas. Habiendo dado de alta los productos con su respectiva información, pueden ser seleccionados para su venta y posteriormente generar las facturas de dichas ventas (en formato PDF y XML).

Dentro de la funcionalidad de la Base de Datos, se integran algunos Procedimientos Almacenados para controlar el inventario, dependiendo de la fecha de caducidad de algún producto, donde no se pueden vender productos que estén próxmimos a caducar. Existen otros procedimientos almacenados para operar otras funcionalidades que aún no se han implementado en este lanzamiento.

El directorio "bases" contiene el archivo de consulta SQL necesaria para generar la base de datos las tablas (entidades) necesarias para conectar la aplicación web con el sistema gestor de base de datos.
>>>>>>> 1abe0700fd5788da6ee2c956bba8bd7732c3a9fc
