# 📊 Análisis de Cáncer de Mama

## Descripción del Proyecto
Este proyecto tiene como objetivo realizar un **Análisis Exploratorio de Datos (EDA)** sobre el cáncer de mama utilizando **Python y Visual Studio Code**. Se ha trabajado con un dataset extraído de Kaggle que contiene información sobre pacientes diagnosticados con cáncer de mama, así como datos adicionales sobre la distribución de casos por continente y país.

## Datos Utilizados
Se han empleado tres conjuntos de datos:

1. **Dataset Principal**: Contiene información sobre pacientes diagnosticados con cáncer de mama, incluyendo:
   - Age: Edad del paciente.
   - Race: Raza del paciente.
   - Marital Status: Estado civil del paciente.
   - T Stage: Tamaño del tumor (T1, T2, etc.).
   - N Stage: Nivel de afectación de los ganglios linfáticos (N0, N1, etc.).
   - 6th Stage: Etapa del cáncer según la clasificación de la sexta edición de la AJCC (por ejemplo, IIA, IIIA).
   - differentiate: Nivel de diferenciación del tumor (bien diferenciado, moderadamente diferenciado, pobremente diferenciado).
   - Grade: Grado del tumor (2, 3, etc.).
   - A Stage: Etapa avanzada del cáncer (regional, metastásico, etc.).
   - Tumor Size: Tamaño del tumor en milímetros.
   - Estrogen Status: Estado del receptor de estrógeno (positivo o negativo).
   - Progesterone Status: Estado del receptor de progesterona (positivo o negativo).
   - Regional Node Examined: Número de ganglios linfáticos examinados.
   - Regional Node Positive: Número de ganglios linfáticos afectados.
   - Survival Months: Meses de supervivencia del paciente.
   - Status: Estado del paciente (vivo o fallecido)

2. **Dataset por Continentes**: Contiene información sobre el número total de casos, tasas de incidencia y riesgos acumulativos en diferentes continentes.

3. **Dataset por Países**: Presenta datos sobre la incidencia del cáncer de mama por país;
   - Tasa de incidencia estandarizada por edad: Permite comparar la incidencia del cáncer entre regiones con diferentes estructuras de edad.
   - Crude rate: Tasa cruda de incidencia, que es el número de casos por cada 100,000 habitantes sin ajuste por edad.
   - Cumulative risk: Riesgo acumulado de desarrollar cáncer de mama hasta los 75 años, expresado como un porcentaje.

## Objetivos del Análisis
- Explorar la distribución de casos según variables demográficas y clínicas.
- Identificar los continentes y países con mayor incidencia de cáncer de mama.
- Analizar la relación entre estudios tumorales y la supervivencia.
- Visualizar los datos con **Power BI**.

## Herramientas Utilizadas
- **Python** (para el EDA): Pandas, Numpy
- **Visual Studio Code** (para programación y edición del código)
- **Power BI** (para visualizaciones)

## Hallazgos Iniciales
- 💡 **Distribución por raza:** La mayoría de los casos pertenecen a la raza **blanca (84.82%)**, seguidos por **black (7.95%)** y **other (7.23%)**.
- 💡 **Distribución por edad:** La mayor cantidad de diagnósticos ocurre en pacientes entre **45 y 60 años**.
- 💡 **Supervivencia:** De un total de 4 mil casos, aproximadamente **3.4 mil pacientes siguen vivos**, mientras que **600 han fallecido**.
- 💡 **Etapas del cáncer:** La mayoría de los casos se encuentran en las etapas **IIA (32.43%) e IIB (28.08%)**, seguidos por **IIIA (26.09%)**.
- 💡 **Países con mayor incidencia:** China y Estados Unidos presentan las tasas más altas de cáncer de mama.

---
