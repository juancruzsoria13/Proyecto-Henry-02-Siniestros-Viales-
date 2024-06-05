# Proyecto de Análisis de Siniestros Viales en Buenos Aires

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar los siniestros viales en la Ciudad Autónoma de Buenos Aires (CABA) utilizando datos de homicidios en siniestros viales ocurridos entre 2016 y 2021. La finalidad es proporcionar información útil para que las autoridades locales puedan tomar medidas efectivas para reducir la cantidad de víctimas fatales en accidentes de tránsito.

## Estructura del Repositorio

- `Datos/`: Carpeta que contiene el dataset original y otros datos complementarios.
- `Datos Limpios/`: Jupyter notebooks utilizados para el análisis exploratorio de datos (EDA).
- `Analisis De Siniestros/`: Scripts de Python utilizados para procesar los datos.
- `EDA/`: Archivos relacionados con el dashboard interactivo creado en Power BI.
- `ETL`: Este archivo.
- `Readme/`: Informe final del análisis con visualizaciones y conclusiones.

## Dataset

El dataset utilizado en este proyecto incluye las siguientes columnas:
Hechos:
- `ID`
- `Cantidad víctimas`
- `Fecha`
- `Año`
- `Mes`
- `Día`
- `Hora Completa`
- `Hora`
- `Tipo_de_calle`
- `Calle`
- `Cruce`
- `Lugar_del_hecho`
- `COMUNA`
- `XY (CABA)`
- `pos x`
- `pos y`
- `Participantes`
- `Víctima`
- `Acusado`

Victimas:
- `ID_victima`
- `Fecha`
- `Año`
- `Mes`
- `Día`
- `Rol`
- `Víctima` 
- `Sexo`
- `Edad`
- `Fecha_de_fallecimiento`

## Análisis Exploratorio de Datos (EDA)

El análisis exploratorio de datos se realizó para entender mejor la distribución y características de los datos. Incluye:

- Detección de valores faltantes y tratamiento de datos ausentes.
- Identificación de valores atípicos y registros duplicados.
- Visualización de la distribución temporal de los siniestros viales.
- Análisis de las características de las calles y lugares donde ocurren más siniestros.
- Exploración de la relación entre el tipo de participante (moto, peatón, etc.) y la cantidad de víctimas.

## Dashboard

El dashboard interactivo fue creado utilizando Power BI y permite explorar los datos de manera detallada mediante filtros y visualizaciones claras. Los KPIs principales están destacados en el dashboard para facilitar la interpretación de la información y su análisis.

## KPIs

### KPI 1: Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses en comparación con el semestre anterior

- **Definición**: La tasa de homicidios en siniestros viales se define como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un período específico.


### KPI 2: Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año en comparación con el año anterior

- **Definición**: La cantidad de accidentes mortales de motociclistas se define como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaron en moto en un período específico.


### KPI 3: (Definido por el usuario)

- **Descripción y fórmula del tercer KPI relevante para el análisis**.

## Conclusiones

El análisis ha proporcionado información valiosa sobre los siniestros viales en CABA, destacando las áreas y factores de mayor riesgo. Los KPIs definidos ayudarán a monitorear el progreso de las medidas implementadas para mejorar la seguridad vial.



