# Ana-lisis-financiero-Rappi-simulatorio
Análisis Estratégico y de Retención
# Diagnóstico Estratégico Integral para RappiPlus

Este repositorio contiene el análisis financiero y operativo de **RappiPlus**, un servicio de suscripción dentro del ecosistema de Rappi diseñado para aumentar la frecuencia de compra y el valor generado por usuario. A través de este proyecto, transformamos datos transaccionales y de marketing en decisiones de negocio accionables.

## Contexto y Objetivo del Negocio
El equipo directivo necesitaba evaluar el desempeño real del modelo de suscripción para responder a dudas clave:
* ¿Podemos confiar en la calidad de los datos actuales?
* ¿El modelo está generando ganancias (Profit) o pérdidas?
* ¿En qué etapa del proceso de compra se pierden los usuarios (Funnel)?
* ¿Los usuarios regresan a comprar (Análisis de Cohortes)?
* ¿Los cambios implementados en la plataforma generan un impacto real (A/B Testing)?

## Contenido del Repositorio
* `Análisis financiero y de retención Simulator.ipynb` → Notebook principal que documenta todo el proceso: 
  1. Limpieza y validación de datos (Python).
  2. Cálculo de KPIs financieros como Revenue, Costos y Profit (Python / SQL).
  3. Construcción del embudo de conversión y puntos de fuga (SQL).
  4. Matrices de retención por cohortes (SQL).
  5. Evaluación estadística de experimentos A/B (Python / SciPy).
* `dashboards/` → Archivo `.pbix` del Dashboard ejecutivo en Power BI.
* Archivo de visualización PDF Análisis financiero y de retención.pdf
  
## Herramientas y Tecnologías Utilizadas
* **Lenguajes:** Python (Pandas, NumPy, SciPy) y SQL.
* **Visualización de Datos:** Matplotlib, Seaborn y Power BI (DAX, Modelado Estrella).
* **Análisis de Negocio:** Análisis de cohortes, Embudos de conversión (Funnels), Pruebas de Hipótesis y Conciliación Financiera.
