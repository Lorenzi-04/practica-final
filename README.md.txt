# Gestión de Almacén

Este proyecto permite gestionar productos en un almacén mediante una interfaz gráfica en Java. El código está organizado en la carpeta `Almacen` y consta de varias clases que implementan la funcionalidad de agregar, editar, eliminar y visualizar productos.

## Estructura del Proyecto

El proyecto contiene las siguientes clases principales:

### 1. **Producto.java**
   Esta clase define un objeto `Producto` que representa los productos que se gestionan en el sistema. Cada producto tiene los siguientes atributos:
   - `nombre`: el nombre del producto.
   - `marca`: la marca del producto.
   - `categoria`: la categoría a la que pertenece el producto.
   - `precio`: el precio del producto.
   - `cantidad`: la cantidad disponible del producto.

   Además, la clase tiene un constructor para inicializar estos valores.

### 2. **GestionProductos.java**
   Esta clase es la que maneja la interfaz gráfica para gestionar los productos. Se usa `JTable` para mostrar los productos y tiene botones para agregar, editar, eliminar y volver a la ventana anterior.

   Funcionalidades de la clase:
   - **Nuevo**: Abre un formulario para agregar un nuevo producto.
   - **Editar**: Permite editar un producto ya existente. Al seleccionar un producto en la tabla y presionar el botón editar, se abre el formulario con los datos del producto seleccionado.
   - **Eliminar**: Elimina el producto seleccionado de la lista y actualiza la tabla.
   - **Volver**: Permite volver a la ventana anterior. (En el código actual solo muestra un mensaje).

   La clase también maneja la actualización de la tabla para reflejar los cambios realizados en los productos.

### 3. **MainApplication.java**
   Esta clase contiene el punto de entrada del programa y muestra un menú inicial para elegir entre las siguientes opciones:
   - **Gestión de Usuarios**: Dirige a la funcionalidad de inicio de sesión de usuarios (no implementada en el código proporcionado).
   - **Gestión de Productos**: Abre la interfaz de gestión de productos.
   - **Salir**: Cierra el programa.

   Dependiendo de la opción seleccionada en el menú, se abre la ventana correspondiente.

## Requisitos

Para ejecutar este proyecto, es necesario tener configurado Java en tu entorno de desarrollo.

### Dependencias
Este proyecto utiliza las siguientes bibliotecas:
- **Java Swing**: Para crear la interfaz gráfica de usuario.

## Cómo ejecutar el proyecto

1. Abre el archivo `MainApplication.java`.
2. Ejecuta el archivo como una aplicación Java.

## Notas

- El código está organizado en la carpeta `Almacen`.
- La gestión de usuarios está prevista para futuras implementaciones, aunque en este código solo se maneja la gestión de productos.
- Se puede mejorar el manejo de errores y la validación de los campos de entrada en el formulario de productos.

