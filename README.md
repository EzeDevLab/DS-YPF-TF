# DS-YPF-TF
## Análisis y predicción de demoras en vuelos

**Proyecto final – Curso de Data Science | Fundación YPF**

## Descripción del proyecto

Este repositorio contiene el desarrollo del proyecto final realizado en el marco del Curso de Data Science organizado por Fundación YPF y JUMP.

El trabajo utiliza un conjunto de datos de vuelos comerciales de Estados Unidos correspondiente al año 2013, con el propósito de analizar el comportamiento de las demoras y detectar patrones asociados a la puntualidad de los vuelos.

El análisis se centra especialmente en las demoras de llegada, buscando identificar los factores relacionados con los retrasos y reconocer patrones de comportamiento que puedan resultar útiles para el seguimiento operativo de las aeronaves.

## Dataset

El conjunto de datos utilizado es **Flights**, obtenido de Kaggle:

- **Fuente:** [Kaggle – Flights Dataset](https://www.kaggle.com/datasets/mahoora00135/flights)
- **Período:** Año 2013.
- **Ámbito geográfico:** Vuelos con salida desde aeropuertos del área de Nueva York, Estados Unidos.

El dataset contiene información relacionada con:

- Fecha y horarios programados y reales de salida y llegada.
- Demoras de salida y llegada.
- Aerolínea y número de vuelo.
- Matrícula de la aeronave.
- Aeropuertos de origen y destino.
- Duración y distancia del vuelo.

## Objetivo del proyecto

Analizar y predecir las demoras de llegada de los vuelos, buscando identificar qué factores están asociados a que un vuelo llegue tarde.

Se presta especial atención a las demoras severas y críticas, con el objetivo de distinguir los retrasos de mayor impacto y reconocer patrones que puedan contribuir a mejorar el seguimiento de la puntualidad.

## Análisis desarrollados

El proyecto contempla diferentes etapas de análisis y modelado:

### 1. Preparación y transformación de datos

- Revisión de la estructura y calidad del dataset.
- Tratamiento de valores faltantes y registros.
- Conversión de fechas y horarios.
- Creación de variables derivadas para enriquecer el análisis.
- Preparación de los datos para las etapas exploratorias y de modelado.

### 2. Análisis exploratorio de datos (EDA)

- Distribución y comportamiento de las demoras de salida y llegada.
- Análisis de puntualidad según aerolínea.
- Identificación de rutas, horarios y períodos con mayores demoras.
- Análisis del comportamiento de las aeronaves según su matrícula.
- Exploración de factores operativos asociados a las demoras.

### 3. Modelado predictivo supervisado

Aplicación de técnicas de aprendizaje supervisado para analizar y predecir las categorías de demora de llegada a partir de las variables disponibles.

### 4. Segmentación de aeronaves mediante clustering

Aplicación de técnicas de aprendizaje no supervisado utilizando el algoritmo K-Means para identificar perfiles de comportamiento entre las aeronaves.

El análisis permitió identificar dos grupos diferenciados según sus características operativas y de puntualidad, considerando especialmente el porcentaje de llegadas graves.

Esta segmentación permite reconocer perfiles que podrían requerir mayor seguimiento operativo.

## Tecnologías y herramientas

Las principales herramientas utilizadas en el desarrollo del proyecto son:

- **Python:** lenguaje de programación.
- **Pandas y NumPy:** manipulación y transformación de datos.
- **Matplotlib y Seaborn:** visualización de datos.
- **Scikit-learn:** preparación de datos y desarrollo de modelos de Machine Learning.
- **Jupyter Notebook:** desarrollo y documentación del análisis.

## Estructura del proyecto

La organización general del repositorio contempla:

- Notebooks de preparación y análisis de datos.
- Análisis exploratorio y visualizaciones.
- Desarrollo y evaluación de modelos.
- Resultados y conclusiones.

## Conclusiones

El proyecto busca transformar los registros históricos de vuelos en información útil para comprender el comportamiento de las demoras.

A través del análisis exploratorio, los modelos predictivos y la segmentación de aeronaves, se busca identificar factores asociados a la falta de puntualidad y reconocer patrones que permitan orientar futuras acciones de seguimiento y mejora operativa.

Los resultados deben interpretarse considerando el alcance y las limitaciones del dataset, que comprende un período de un año y vuelos con salida desde el área de Nueva York.

## Autor

**Ezequiel Allayme**

Proyecto final – Curso de Data Science  
Fundación YPF
