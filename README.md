# Analisis de Operaciones Logisticas

Simulación de Control Operativo de Carga Aérea y Análisis de Desempeño Logístico

## Descripción del Proyecto

Este proyecto simula el rol de Analista de Operaciones Logísticas en una empresa de carga aérea con operación en Bogotá.

El objetivo es diseñar un modelo de control operativo que permita:

- Monitorear fechas estimadas vs reales de arribo
- Medir cumplimiento de entregas
- Analizar retrasos e incidencias
- Calcular impacto financiero por demoras
- Evaluar desempeño de aerolíneas mediante un índice ponderado

El análisis fue desarrollado utilizando Excel para estructuración de datos y Power BI con DAX para modelado y visualización.

📂 Estructura del Repositorio
📁 /data

Contiene el archivo base en Excel con la simulación de envíos:

seguimiento_cargas.xlsx

Incluye:

70 envíos simulados

Guía aérea

Aerolínea

Fechas estimadas y reales

Estado del envío

Incidencias

Valor de la carga

📁 /powerbi

Contiene el archivo del dashboard desarrollado en Power BI:

dashboard_operaciones.pbix

Incluye:

Modelo de datos

Columnas calculadas

Medidas DAX

Visualizaciones ejecutivas

🎯 Objetivos de Negocio

Medir el nivel de cumplimiento operativo

Detectar retrasos recurrentes

Evaluar desempeño por aerolínea

Cuantificar riesgo financiero por demoras

Apoyar la toma de decisiones basada en datos

📊 Indicadores Clave (KPIs)
📌 Total de Envíos

Cantidad total de operaciones registradas.

📌 % Cumplimiento Operativo

Envíos entregados sin retraso ÷ total de envíos.

📌 Promedio de Días de Retraso

Mide severidad de demoras.

📌 Valor en Riesgo

Suma del valor de las cargas que presentan retraso.

Representa exposición financiera operativa.

📌 Índice de Desempeño por Aerolínea

Indicador ponderado que combina:

60% Cumplimiento

30% Severidad del retraso

10% Impacto financiero

Permite clasificar aerolíneas según confiabilidad operativa.

🧠 Lógica Analítica Aplicada

Uso de columnas calculadas para determinar días de retraso

Clasificación binaria de cumplimiento (1 = a tiempo / 0 = retraso)

Medidas DAX para análisis dinámico por aerolínea

Cálculo de indicadores financieros condicionados

Construcción de índice compuesto para evaluación integral

El modelo respeta el contexto de filtros, permitiendo análisis segmentado por aerolínea y estado.

🛠 Herramientas Utilizadas

Microsoft Excel

Power BI Desktop

DAX (Data Analysis Expressions)

📈 Enfoque Profesional

Este proyecto refleja funciones propias de un analista en operaciones logísticas como:

Seguimiento de cargas internacionales

Control de arribo

Análisis de incidencias

Evaluación de proveedores (aerolíneas)

Medición de desempeño operativo

Identificación de riesgo financiero
