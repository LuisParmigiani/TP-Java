# TP-Java

## Descripción

Software para venta y distribución de bebidas con seguimiento de envases vacíos para los retornables. Garantiza la honestidad de los choferes controlando lo que se lleva y lo que se trae, contrastándolo con las ventas que hizo. Cuenta con una plataforma para los choferes, ayudándolos a recordar todos los puntos en donde tienen que vender y registrando la venta. Además, cuenta con una plataforma para los clientes donde pueden ver su deuda y el detalle de la misma, así como enlaces para cancelarla automáticamente.

Además del control de los choferes para ayudar a la administración, cuenta con un registro de gastos para los vehículos de la empresa sumado a un dashboard repleto de información de las ventas y las deudas
## Enlace al Frontend y Backend
![Backend](https://github.com/LuisParmigiani/Java-TP2026-Back)
![Frontend](https://github.com/LuisParmigiani/Java-TP2026-Front)


## DER

![DER](DER-JAVA.jpg)

##### Regularidad

| Requerimiento    | Detalle/Listado de casos incluidos                                                                     |
| :--------------- | ------------------------------------------------------------------------------------------------------ |
| ABMC simple      | Producto <br>Zona <br>Usuario <br> Persona <br> Camion                                                 |
| ABMC dependiente | Domicilio                                                        |
| CU NO-ABMC       | Venta <br> Carga/Descarga                                                                              |
| Listado simple   | Listado de Clientes (Por zona, deudores, etc). <br> Listado de camiones (por ventas, zona, dia, etc.). |
| Listado complejo | Listado de ventas (filtado por montos, zona, producto, etc. )                                          |

##### Aprobación Directa                                                                                                                                                                                      |
| Requerimiento                   | Detalle/Listado de casos incluidos                                                                                                                                                      |
| :------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ABMC                            |  Precio<br> Localidad<br> Provincia<br> Domicilio<br> LineaPedido<br> Venta<br> Mensaje<br> Temporal<br> Pago<br> Gastos <br>                                                           |
| CU "Complejo"                   | Registro nuevo cliente/domicilio <br> Asignar clientes a camion <br> Asignar los precios a los productos por zona (Ent: Precio) <br>  Mandar a los deudores la deuda (API: Wspp)        |
| Listado complejo                | Listado de ventas. <br>                                                                                                                                                                 |
| Nivel de acceso                 | Cliente <br> Admin <br> Empleado <br> No registrado                                                                                                                                     |
| requerimiento extra obligatorio | N                                                                                                                                                                                       |

###### Requerimientos extra - AD

| Requerimiento      | Detalle/Listado de casos incluidos |
| :----------------- | :--------------------------------- |
| Manejo de archivos |                                    |
| Custom exceptions  |                                    |
| Log de errores     |                                    |
| Envio de emails    |                                    |
