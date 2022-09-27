# **LLAVERO INTELIGENTE**
## I N T E G R A N T E S  
- Omar Arturo Moctezuma Padrón
- Sebastian Eduardo Ramírez Bocanegra
- Brenda Janet Rodríguez Salazar
- Manuel Alejandro Soria Márquez
## 

## O B J E T I V O
Generar una aplicación web de control de inventariado que permita a los usuarios llevar a cabo labores relacionadas a esto como lo son: Alta y baja de productos en sistema, Generación de facturas, reportes y contabilidad, Baja/Venta de productos mediante QR.
## 
## HISTORIAS DE USUARIO
| ID | Nombre | Prioridad | Descripción | Puntos estimados|
| --- | --- | --- | --- | --- |
| HU01 | Iniciar Sesión | Alta-10 | El usuario ingresará al sistema mediante el uso de credenciales (Correo, Username, Password).| 1 |
| HU02 | RegistrarUsuario | Alta-10 | El usuario generar un registro para ingresar al sistema al llenar un formulario con la siguiente información (Nombre de usuario, Correo, Contraseña, Dirección, Nombre organización), al enviar el formulario se guardará el registro automáticamente. | 1 |
| HU03 | Registrar Producto | Alta-10 | El usuario podrá registrar un nuevo producto al llenar un formulario con la siguiente información: (Nombre producto, descripción, categoría, Imagen, Fecha, Cantidad, Precio, medidas). Al registrar un nuevo producto se debe generar un Código QR aleatorio que identifique el registro, este se guardará junto con la demás información. Al enviar el formulario se registrará la información en la base de datos.|1|
| HU04 | Eliminar Producto | Alta-10 |El usuario podrá eliminar cualquier producto. Al querer eliminar el sistema enviará un mensaje de alerta para confirmar la eliminación. Al eliminar se borrará el registro de dicho producto.|1|
| HU05 | Modificar Producto | Alta-10 | Si se quiere modificar un producto se debe mostrar un formulario con los datos actuales del producto y el usuario podrá modificar dicha información, al modificar en cada uno de los campos. Se deberá guardar los nuevos cambios en la base. |1|
| HU06 | Venta Producto QR | Alta-10 |El usuario deberá poder realizar una venta mediante la lectura de un código QR, al leer el código se realizará una venta de producto, en caso de no contar con más producto se dará de baja en el inventario. |2|
| HU07 | Generar Reporte de ventas | Media-7  |El usuario podrá generar un reporte de ventas de las fechas especificadas por el mismo, dicho reporte contendrá:(Ventas realizadas, productos vendidos, Precio total de ventas, fecha de venta.) |2|
| HU08 | Generar Factura de ventas | Media-7  | Al realizar una venta el usuario deberá poder ver una factura de venta con información sobre la venta(Lista de producto, Costo, Fecha). |2|
| HU09 | Notificación Falta Inventario | Media-7  |El usuario deberá de ser notificado mediante correo u otro medio, cuando el producto en el inventario este pronto terminarse.|2|
## 
