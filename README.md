# Logistics Operations Analytics: Control y Desempeño de Carga Aérea

### Monitor de Cumplimiento Operativo y Evaluación de Proveedores (SLA)
**Herramientas:** `Power BI (DAX)` | `Excel` | `Análisis de Riesgo Financiero` | `Vendor Scoring`

---

## Objetivo del Proyecto
Optimizar la visibilidad de la cadena de suministro internacional mediante un modelo de control operativo para carga aérea. El proyecto se centra en la mitigación de riesgos financieros derivados de retrasos y en la clasificación técnica de aerolíneas basada en niveles de servicio (**SLA**).

## Metodología y Análisis de Datos
1. **Arquitectura de Datos:** Estructuración de 70 registros de importación aérea, incluyendo trazabilidad de guías (AWB) y tiempos de tránsito.
2. **Modelado en Power BI:** Implementación de medidas avanzadas en **DAX** para calcular desviaciones temporales y exposición financiera.
3. **Vendor Scoring (Ponderación):** Creación de un índice de desempeño dinámico basado en:
   * **60%** Cumplimiento de entregas.
   * **30%** Severidad del retraso (Días mora).
   * **10%** Impacto financiero (Valor de la carga en riesgo).

## Hallazgos Estratégicos (Insights)
* **Exposición Financiera:** Se identificó que el riesgo económico no es proporcional al volumen, sino que se concentra en retrasos críticos de mercancía de alto valor.
* **Ranking de Confiabilidad:** El modelo permitió categorizar a los proveedores (aerolíneas) en niveles de criticidad, facilitando la toma de decisiones para futuras contrataciones.
* **Anomalías en Tiempos de Tránsito:** El análisis evidencia que demoras superiores a 24 horas impactan drásticamente el índice de cumplimiento operativo global.

## Propuesta de Valor para el Negocio
Con este modelo, la compañía puede:
1. **Optimizar el Lead Time:** Seleccionar rutas y proveedores con menores tasas de desviación.
2. **Reducción de Costos Extraordinarios:** Anticipar retrasos para mitigar gastos por almacenamiento o paradas de línea de producción.

---

## Estructura del Proyecto
* **data/**: Datasets en Excel y CSV con registros de guías aéreas y estados de envío.
* **powerbi/**: Archivo `.pbix` con el dashboard interactivo y versión en PDF para reportes ejecutivos.

---

### 🔗 Recursos del Proyecto
* [Descargar Reporte en PDF](/Power_BI/dashboard_operaciones.pdf)
* [Explorar Dataset de Carga](/Data/Cargas.xlsx)

**Autor** Laura M
