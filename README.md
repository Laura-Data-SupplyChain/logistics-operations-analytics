# Logistics Operations Analytics – Control y Desempeño de Carga Aérea
Proyecto de simulación enfocado en el análisis operativo de envíos internacionales vía aérea.

## Objetivo
Desarrollar un modelo de control operativo que permita monitorear el desempeño logístico de cargas aéreas mediante el análisis de:
- Cumplimiento de fechas estimadas vs reales
- Incidencias operativas
- Severidad de retrasos
- Impacto financiero
- Evaluación de desempeño por aerolínea

El proyecto simula el rol de Analista de Operaciones Logísticas en una empresa con operación en Bogotá.

## Estructura de Archivos

/data
- [Cargas.xlsx](Data/Cargas.xlsx)
- [Cargas.csv](Data/Cargas.csv)

/powerbi
- [dashboard_operaciones.pbix](Power_BI/dashboard_operaciones.pbix)
- [dashboard_operaciones.pdf](Power_BI/dashboard_operaciones.pdf)

### /data

Archivo en Excel con 70 envíos simulados que incluyen:
- Guía aérea
- Aerolínea
- Origen y destino
- Fecha estimada de arribo
- Fecha real
- Estado del envío
- Incidencia
- Valor de la carga

### /powerbi

Archivo del dashboard desarrollado en Power BI con:
- Columnas calculadas
- Medidas DAX
- Indicadores ejecutivos
- Visualizaciones dinámicas por aerolínea

## KPIs Analizados

- Total de Envíos
- % Cumplimiento Operativo
- Promedio de Días de Retraso
- Valor Financiero en Riesgo
- Índice de Desempeño por Aerolínea (ponderado)

El índice de desempeño combina:
- 60% Cumplimiento
- 30% Severidad del retraso
- 10% Impacto financiero

## Herramientas Utilizadas

- Microsoft Excel (estructuración y validación de datos)
- Power BI Desktop
- DAX (Data Analysis Expressions)

## Principales Hallazgos

- Se identificaron aerolíneas con mayor recurrencia de retrasos.
- El impacto financiero se concentra en envíos con demoras superiores a 1 día.
- El índice ponderado permite clasificar proveedores según confiabilidad operativa.
- El análisis evidencia cómo pequeñas demoras pueden generar exposición financiera significativa.

## Cómo Explorar el Proyecto

- Revisar el archivo Cargas.xlsx o Cargas.csv en la carpeta /data.
- Abrir el archivo dashboard_operaciones.pbix en Power BI Desktop.
- Analizar los indicadores generales en la vista ejecutiva.
- Utilizar filtros por aerolínea y estado para explorar desempeño individual.


**Autor** Laura M
