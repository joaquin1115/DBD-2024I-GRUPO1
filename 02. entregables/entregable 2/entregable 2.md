# Presentación Grupal 02: Proceso de Negocio y Requerimientos (Avance)

## Descripción del Proceso de Negocio

| Secuencia | Actividad                                          | Descripción         | Responsable  |
| --------- | -------------------------------------------------- | ------------------- | ------------ |
| 1         |  Evaluacion de actividades |  Se evalúa las necesidades de cada área interna para seguir con la operatividad de los procesos | Supervisor
| 2         |  Elaboracion de requerimientos                         | Se crea una solicitud formal de las necesidades del área para la carga en el sistema SAP | Almacenero
| 3         |  Cargar requerimientos al WMS | Subida de requerimientos mediante el programa SAP con el requerimiento MRP | Asistente de almacén |
| 4         |  Recepcion de solicitud de requerimientos | El almacen se encarga de recibir y verificar las solicitudes del software SAP| Tecnico de almacén |
| 5         |  Segmentación de requerimientos | Posteriormente, se hace segmentación de estos pedidos, específicamente en 3 segmentaciones: la primera  segmentación es todo lo que necesita la planta y que son nocivos, como detergentes industriales, químicos; la segunda corresponde a suministros, repuestos; y el tercero corresponde a insumos, etiquetas, bolsas, galleta molida, sacos, cajas de cartón, etc. | Gestor de compras |
| 6         |  Requerimiento de Transporte | De acuerdo a la segmentación previa se solicita un transporte adecuado al área correspondiente  para una adecuada inocuidad y evitar cualquier peligro. | Técnico de logística |
| 7         |  Evaluación de requerimiento | Cada producto puede requerir medios de transporte especifico | Asistente Operativo |
| 8         | Asignacion de vehiculo y conductor | El vehículo debe tener las características adecuadas para el trasnporte del pedido y el conductor para estar apto para el trabajo no debe estar en cuarentena | Transportista |
| 9         | Elaboracion de guía de remision electronica | Se documenta el horario de entrega, placa del vehículo, tip de vehículo, datos del conductor, capacidad de carga, peso, etc. para mandar por correo a la planta solicitante para que puedan verificar el transporte cuando lo recepcionen | Encargado de Almacén |
| 10        | Picking, precintado y carga de productos | Recogida de los productos del pedido, un precintado por cuestión de seguridad que tiene un número y carga de los productos al transporte | Asistente de Almacén |
| 11        | Verificación de recibimiento | Subida al sistema de elementos de comprobación de la conformidad de la entrega |Transportista y Encargado de Almacén |

| Secuencia | Actividad                                          | Descripción         | Responsable  |
| --------- | -------------------------------------------------- | ------------------- | ------------ |
| 1         | Requerimiento de compra   | En el sistema se detalla las cantidades, especificaciones y fechas de entrega requeridas para asegurar el cumplimiento eficiente del pedido del cliente. | Encargado de Planeación |
| 2         | Distribución de Requerimientos  |  Descarga de todas las solicitudes de pedido de los clientes, para poder distribuirlo de forma adecuada basándose en la especialización de cada planta de San Fernando. | Encargado de Almacén |
| 3         | Requerimiento de Transporte   |  Solicitud de la presencia del área de transporte que se encarga de elegir al conductor, vehiculo y todo lo relacionado | Encargado de Almacén|
| 4         | Evaluación de requerimiento   |  Cada pedido del cliente se evalúa meticulosamente. Dado que estos pedidos suelen ser mixtos, se requiere la selección de productos de varias plantas, así como la asignación de un vehículo adecuado para garantizar la entrega segura y eficiente de los productos solicitados. | Asistente Operativo |
| 5         | Asignación de vehículo y conductor | El conductor y vehculo seleccionado debe pasar por un proceso de cuarentena, que garantice que puedan cumplir sus labores de manera adecudada, además de que este procedmiento forma parte de las politicas de la empresa. | Transportista |
| 6         | Picking, precintado y carga de productos   | Toda esta información migra al  área de gestión documentaria y despacho,  que crean las guías de remisión que son electrónicas a la vez que crea las respectivas facturas electrónicas asignadas para cada cliente, también incluye el proceso de precintado, picking y carga de productos. | Asistente de Almacén |
| 7         | Verificación de entrega   |  El proceso de verificación de la entrega del pedido se realiza a través del sistema SAP. En caso de incidentes, San Fernando se comunica directamente con el cliente para validar el reclamo mediante el departamento de calidad. Si el reclamo es procedente, se reemplaza el producto en un plazo máximo de 24 horas desde su registro. | Transportista y Encargado de Almacén |



### 1. Roles del proceso de negocio

-
-
-
-


### 2. Diagrama del proceso de negocio

a. Diagrama AS-IS

![Diagrama sin título drawio](https://github.com/joaquin1115/DBD-2024I-GRUPO1/assets/121084712/da52d766-a972-4175-bc38-0cbae8069823)

Proceso de negocio: Elabarocacion de despacho. Elaboración propia.

Link del diagrama: https://app.diagrams.net/?src=about#G1dXQysSmCzSni56V_scq2cCQqn8lhpNzT#%7B%22pageId%22%3A%22prtHgNgQTEPvFCAcTncT%22%7D

## Módulos del Sistema
El objetivo principal es encontrar una estructura optima de forma que su software pueda cumplir con sus requerimientos.

### Modulo #1: Pedidos Asignados

Responsabilidades:

- 
-
-
-

Interacción con otros módulos:

Visibilidad de interfaces:

### Modulo #2: Realizar Pedidos

Responsabilidades:

-
-
-
-

Interacción con otros módulos:

Visibilidad de interfaces:

### Modulo #3: Seguimiento de Pedidos Solicitados

Responsabilidades:

-
-
-
-

Interacción con otros módulos:

Visibilidad de interfaces:

### Modulo #4: Seguimiento de Pedidos Remitidos

Responsabilidades:

-
-
-
-

Interacción con otros módulos:

Visibilidad de interfaces:

### Modulo #5: Control

Responsabilidades:

-
-
-
-

Interacción con otros módulos:

Visibilidad de interfaces:

### Modulo #6: Reclamos

Responsabilidades:

-
-
-
-

Interacción con otros módulos:

Visibilidad de interfaces:

## Requerimientos

### 1. Requerimientos funcionales

a. Usuarios y casos de uso

- Perfil de usuario de Planta de Beneficio Huaral (Supervisor de Almacén, Asistente de Almacén, etc.)

   - Realizar pedidos de materiales (suministros, repuestos, insumos, etiquetas, etc.)
   - Verificar pedidos en tránsito y recepcionar pedidos entrantes
   - Gestionar devoluciones de productos terminados
   - Visualizar estadísticas de recepción/despacho de productos

- Perfil de usuario de Almacén Central

   - Gestionar pedidos de las distintas plantas
   - Asignar vehículos y conductores para el despacho
   - Realizar despachos hacia las plantas
   - Gestionar devoluciones de plantas
   - Visualizar estadísticas de despachos

- Perfil de usuario de Área de Transporte

   - Gestionar flota de vehículos y conductores
   - Asignar vehículos y conductores para despachos
   - Realizar seguimiento de entregas
   - Visualizar estadísticas de transporte

- Perfil de usuario de Área de Programación

   - Planificar producción diaria/semanal
   - Coordinar con granjas para envío de aves
   - Visualizar estadísticas de producción
  
- Perfil de usuario de Área de Producción

   - Gestionar proceso de producción (recepción de aves, viscerado, corte, marinado, etc.)
   - Coordinar con despacho para cumplir ventanas horarias
   - Visualizar estadísticas de producció
  
- Perfil de usuario de Área de Calidad

   - Gestionar devoluciones de clientes
   - Analizar causas de devoluciones
   - Visualizar estadísticas de calidad
  
- Perfil de usuario de Proveedor

   - Visualizar pedidos de Almacén Central
   - Confirmar fechas de entrega
   - Realizar seguimiento de pedidos

### 2. Requerimientos de atributos de calidad
- Rendimiento: El sistema debe ser capaz de manejar grandes volúmenes de transacciones y datos, especialmente en áreas como despacho y producción, donde se manejan operaciones críticas con ventanas de tiempo limitadas.
- Procesos batch: Ciertos procesos, como la planificación de producción y la generación de pedidos, pueden requerir ejecuciones periódicas (diarias, semanales, mensuales) de acuerdo con los ciclos de negocio.
- Integración con sistemas existentes: El sistema debe integrarse con el sistema SAP existente para intercambiar información de pedidos, inventarios, entregas, etc.
- Trazabilidad y auditoría: El sistema debe mantener un registro detallado de todas las transacciones y operaciones realizadas, permitiendo la trazabilidad y auditoría de los procesos.
- Seguridad y control de acceso: El sistema debe implementar medidas de seguridad adecuadas, como control de acceso basado en roles y perfiles de usuario, para proteger la información confidencial de la empresa.


## Entrevista
A continuación, se muestra la grabación de la entrevista realizada a la ingeniera Joselin Alexandra Torres Robles, supervisora del área de almacén de la planta Huaral de San Fernando.

[![Entrevista](http://img.youtube.com/vi/DPxvZC3R6Ws/0.jpg)](http://www.youtube.com/watch?v=DPxvZC3R6Ws "Entrevista a Joselin Torres")

Los detalles de la reunión fueron registrados en la [acta](acta-entrevista-20240401.md) respectiva, así como también se elaboró una [transcripción](transcripcion-entrevista-20240401.md) de las preguntas y respuestas realizadas durante la entrevista, además se generó un resumen donde se sintetiza los procesos más importantes con un cierto orden [Resumen entrevista](Resumen-transcripcion.md), con el fin de comprender mejor los procesos de San Fernando.
