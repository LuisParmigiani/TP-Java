# TP-Java


##### Regularidad

|Requerimiento|Detalle/Listado de casos incluidos|
|:-|-|
|ABMC simple| Carga <br> Producto <br>Zona <br>Usuario <br> Persona <br> Camion|
|ABMC dependiente| Precio <br>  LineaPedido<br> Venta<br> Domicilio|
|CU NO-ABMC| Venta <br> Carga/Descarga |
|Listado simple|Listado de Clientes (Por zona, deudores, etc). <br> Listado de camiones (por ventas, zona, dia, etc.). |
|Listado complejo| Listado de ventas (filtado por montos, zona, producto, etc. )|


##### Aprobación Directa

|Requerimiento|Detalle/Listado de casos incluidos|
|:-|:-|
|ABMC|Carga <br> Producto<br> Zona<br> Usuario<br> Precio<br> Localidad<br> Provincia<br> Domicilio<br> LineaPedido<br> Venta<br> Persona<br> Mensaje<br> Temporal<br> Pago<br> Gastos |todos|
|CU "Complejo"| Ventas <br> Registro nuevo cliente/domicilio <br> Asignar clientes a camion <br> Asignar los precios a los productos por zona <br> Control de carga <br>  Mandar a los deudores la deuda  |
|Listado complejo|Listado de ventas. <br> |
|Nivel de acceso| Cliente <br> Admin <br> Empleado <br> No registrado |
|requerimiento extra obligatorio | N |


###### Requerimientos extra - AD
|Requerimiento |Detalle/Listado de casos incluidos|
|:-|:-|
|Manejo de archivos||
|Custom exceptions||
|Log de errores||
|Envio de emails||