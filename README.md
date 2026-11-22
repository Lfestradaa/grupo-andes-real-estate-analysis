# Análisis Comercial Inmobiliario | Andes Capital Real Estate

## Descripción del proyecto

Este proyecto analiza los datos de ventas inmobiliarias de Andes Capital Real Estate durante el periodo 2023–2024, con el objetivo de evaluar el desempeño comercial, comprender el comportamiento de los clientes e identificar oportunidades de mejora para el negocio.

El análisis se centra en el desempeño financiero, los tipos de propiedad, los canales de venta, la segmentación de clientes y el comportamiento de recompra mediante un análisis de cohortes.

## Objetivos del análisis

- Evaluar el comportamiento de los ingresos y la evolución de las ventas.
- Analizar la distribución de las ventas por tipo de propiedad, ciudad y canal comercial.
- Comprender la segmentación de clientes y su contribución a los ingresos.
- Analizar el comportamiento de recompra de los clientes mediante cohortes.
- Identificar hallazgos y oportunidades de mejora para la toma de decisiones comerciales.

## Herramientas y tecnologías

- **Power BI:** Modelado de datos, medidas DAX, inteligencia de tiempo, análisis de cohortes y desarrollo de dashboards interactivos.
- **Power Query:** Preparación, transformación y limpieza de datos.
- **DAX:** Creación de medidas, columnas calculadas y cálculos analíticos.

## Conjunto de datos

El proyecto utiliza información de ventas inmobiliarias correspondiente a los años 2023 y 2024, organizada en las siguientes tablas:

- `hecho_ventas_propiedades`: información de las transacciones de venta.
- `dim_clientes`: información y segmentación de clientes.
- `dim_propiedades`: características de las propiedades.
- `Dim_Fecha`: tabla calendario construida en Power BI.

## Modelo de datos

Se implementó un modelo dimensional tipo **esquema estrella**, con la tabla de ventas como tabla central, relacionada con las dimensiones de clientes, propiedades y fechas.

Esta estructura facilita el análisis de las transacciones y la segmentación de los resultados desde diferentes perspectivas comerciales.

## Dashboard en Power BI

El dashboard está compuesto por tres páginas:

### 1. Overview Ejecutivo

Presenta los principales indicadores financieros y comerciales, incluyendo ingresos totales, cantidad de ventas, ticket promedio, comisiones y crecimiento interanual. También permite analizar la evolución mensual de los ingresos y el desempeño por ciudad.

### 2. Análisis Comercial

Permite explorar la distribución de los ingresos según el tipo de propiedad, canal de venta y segmento de compradores. Incluye una comparación del desempeño comercial por ciudad y tipo de propiedad.

### 3. Análisis de Cohortes

Estudia el comportamiento de recompra de los clientes a partir de su primera transacción, utilizando una matriz de cohort
