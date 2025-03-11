# 📊 Análisis de Cáncer de Mama

## Descripción del Proyecto
Este proyecto tiene como objetivo realizar un **Análisis Exploratorio de Datos (EDA)** sobre el cáncer de mama utilizando **Python y Visual Studio Code**. Se ha trabajado con un dataset extraído de Kaggle que contiene información sobre pacientes diagnosticados con cáncer de mama, así como datos adicionales sobre la distribución de casos por continente y país.

## Datos Utilizados
Se han empleado tres conjuntos de datos:

1. **Dataset Principal**: Contiene información sobre pacientes diagnosticados con cáncer de mama, incluyendo:
   - Edad
   - Raza
   - Estado Civil
   - Estadios Tumorales (T Stage, N Stage, 6th Stage, A Stage)
   - Diferenciación y Grado
   - Tamaño del Tumor
   - Estado de receptores hormonales (Estrógeno y Progesterona)
   - Exámenes y Resultados Regionales de Ganglios Linfáticos
   - Meses de Supervivencia y Estado del Paciente

2. **Dataset por Continentes**: Contiene información sobre el número total de casos, tasas de incidencia y riesgos acumulativos en diferentes continentes.

3. **Dataset por Países**: Presenta datos sobre la incidencia del cáncer de mama por país, con información sobre tasas estandarizadas por edad, tasas crudas y riesgos acumulativos.

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
- 💡 **Países con mayor incidencia:** Europa y Norteamérica presentan las tasas más altas de cáncer de mama.

---