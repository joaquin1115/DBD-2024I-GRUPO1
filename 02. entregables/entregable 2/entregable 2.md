# Presentación Grupal 02: Proceso de Negocio y Requerimientos (Avance)

## Descripción del Proceso de Negocio

| Secuencia | Actividad                                          | Descripción         | Responsable  |
| --------- | -------------------------------------------------- | ------------------- | ------------ |
| 1         |  Evaluacion de actividades
| 2         |  Elaboracion de requerimientos
| 3         |  Cargar requerimientos al WMF
| 4         |
| 5         |
| 6         |
| 7         |
| 8         |
| 9         |
| 10        |

### 1. Roles del proceso de negocio

-
-
-
-


### 2. Diagrama del proceso de negocio

a. Diagrama AS-IS

B. Diagrama TO-BE

## Módulos del Sistema
El objetivo principal es encontrar una estructura optima de forma que su software pueda cumplir con sus requerimientos.

### Modulo #1: 

Responsabilidades:

-
-
-
-

Interacción con otros módulos:

Visibilidad de interfaces:

### Modulo #2: 

Responsabilidades:

-
-
-
-

Interacción con otros módulos:

Visibilidad de interfaces:

### Modulo #3: 

Responsabilidades:

-
-
-
-

Interacción con otros módulos:

Visibilidad de interfaces:

### Modulo #4: 

Responsabilidades:

-
-
-
-

Interacción con otros módulos:

Visibilidad de interfaces:

### Modulo #5: 

Responsabilidades:

-
-
-
-

Interacción con otros módulos:

Visibilidad de interfaces:

### Modulo #6: 

Responsabilidades:

-
-
-
-

Interacción con otros módulos:

Visibilidad de interfaces:

## Requerimientos

### 1. Requerimientos funcionales

a. Usuarios

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

b. Casos de Uso

Caso de Uso #1:

### 2. Requerimientos de atributos de calidad
- Rendimiento: El sistema debe ser capaz de manejar grandes volúmenes de transacciones y datos, especialmente en áreas como despacho y producción, donde se manejan operaciones críticas con ventanas de tiempo limitadas.
- Procesos batch: Ciertos procesos, como la planificación de producción y la generación de pedidos, pueden requerir ejecuciones periódicas (diarias, semanales, mensuales) de acuerdo con los ciclos de negocio.
- Integración con sistemas existentes: El sistema debe integrarse con el sistema SAP existente para intercambiar información de pedidos, inventarios, entregas, etc.
- Trazabilidad y auditoría: El sistema debe mantener un registro detallado de todas las transacciones y operaciones realizadas, permitiendo la trazabilidad y auditoría de los procesos.
- Seguridad y control de acceso: El sistema debe implementar medidas de seguridad adecuadas, como control de acceso basado en roles y perfiles de usuario, para proteger la información confidencial de la empresa.

### 3. Restricciones
-
-
-

## Entrevista
A continuación, se muestra la grabación de la entrevista realizada a la ingeniera Joselin Alexandra Torres Robles, supervisora del área de almacén de la planta Huaral de San Fernando.

[![Entrevista](http://img.youtube.com/vi/DPxvZC3R6Ws/0.jpg)](http://www.youtube.com/watch?v=DPxvZC3R6Ws "Entrevista a Joselin Torres")

Los detalles de la reunión fueron registrados en la [acta](acta-entrevista-20240401.md) respectiva, así como también se elaboró una [transcripción](transcripcion-entrevista-20240401.md) de las preguntas y respuestas realizadas durante la entrevista.
