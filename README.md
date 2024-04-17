# Tienda de Productos

Este repositorio contiene datos y visualizaciones relacionadas con una tienda de productos. A continuación, se describen los componentes principales:

## Estructura del Repositorio

- `clientes`: Datos sobre los clientes de la tienda.
- `productos`: Información sobre los productos disponibles.
- `empleados`: Detalles de los empleados de la tienda.
- `ventas`: Registros de ventas realizadas.

## Herramientas utilizadas:
- R: Se utiliza R para el análisis de datos, manipulación y visualización.
-  Flexdashboard: Se utiliza para crear el tablero interactivo que muestra los reportes semanales.
- Highcharter y ggplot2: Se utilizan para crear gráficos interactivos y estáticos respectivamente.
- ODBC y DBI: Se utilizan para conectarse a la base de datos SQL Server y realizar consultas.
- Tidyverse: Se utiliza para la manipulación de datos y el análisis.

## Visualizaciones

### Ventas por Año y Mes

!Ventas por Año y Mes

Esta gráfica muestra las ventas totales por mes y año. Los datos provienen de la tabla de ventas.

### Empleados con los Salarios Más Altos

A continuación se presentan los 15 empleados con los salarios más altos:

| Nombre | Salario |
|--------|---------|
| Juan   | $80,000 |
| María  | $78,000 |
| ...    | ...     |

## Configuración del Proyecto

Para ejecutar este proyecto, sigue estos pasos:

1. Clona este repositorio.
2. Configura la conexión a la base de datos en el archivo `config.R`.
3. Ejecuta los scripts para cargar los datos y generar las visualizaciones.

¡Gracias por visitar nuestra tienda de productos!

## Graficas

Proporciona una variedad de graficas usando diferentes librerias, con las cuales podemos tener un vision general de la compañia