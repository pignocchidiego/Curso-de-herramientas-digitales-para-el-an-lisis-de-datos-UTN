# Análisis Exploratorio del Mercado Inmobiliario | UTN

## Descripción del proyecto

Proyecto final integrador del curso **Herramientas básicas para el Análisis de Datos**, dictado por el Centro de e-Learning de la Universidad Tecnológica Nacional (UTN.BA).

El trabajo consiste en un análisis exploratorio del mercado inmobiliario de la Ciudad Autónoma de Buenos Aires (CABA) y el Gran Buenos Aires, utilizando herramientas de procesamiento, análisis y visualización de datos.

Se integran datasets inmobiliarios históricos y actuales para estudiar la evolución de los precios, las diferencias entre tipos de propiedades y la distribución territorial de los valores.

## Objetivos

- Analizar la evolución de los precios inmobiliarios entre 2017 y 2026.
- Comparar los precios promedio de diferentes tipos de propiedades.
- Identificar barrios con mayores valores inmobiliarios.
- Analizar los precios promedio por metro cuadrado.
- Aplicar técnicas de limpieza, transformación y exploración de datos.
- Comunicar resultados mediante visualizaciones en Python y un dashboard en Power BI.

## Herramientas utilizadas

- **Excel:** revisión y organización de datos.
- **Python:** procesamiento y análisis exploratorio.
- **pandas:** manipulación y transformación de datasets.
- **matplotlib y seaborn:** visualización de datos.
- **Google Colab:** desarrollo del notebook.
- **Power BI:** elaboración del dashboard interactivo.
- **GitHub:** documentación y publicación del proyecto.

## Fuentes de datos

Se utilizaron conjuntos de datos del mercado inmobiliario correspondientes a:

- REMAX 2026.
- Properati histórico.
- Properati 2017.

Los datos incluyen información sobre precios, superficies, ubicación, tipos de propiedad y otras características inmobiliarias.

## Metodología

### 1. Preparación de datos

- Integración de diferentes fuentes inmobiliarias.
- Estandarización de nombres y categorías.
- Tratamiento de valores faltantes.
- Revisión de registros duplicados.
- Normalización de formatos y variables.
- Construcción de una base consolidada.

### 2. Análisis exploratorio con Python

- Inspección de la estructura del DataFrame.
- Estadísticas descriptivas.
- Evaluación de valores faltantes y duplicados.
- Análisis de variables numéricas y categóricas.
- Estudio de relaciones entre variables.
- Elaboración de visualizaciones.

### 3. Visualización de resultados

Se desarrollaron gráficos para analizar:

- Evolución del precio promedio en USD por año.
- Precio promedio en USD según tipo de propiedad.
- Los 10 barrios con mayores precios promedio.
- Evolución del precio promedio por metro cuadrado.

### 4. Dashboard en Power BI

Se elaboró un tablero para presentar indicadores y gráficos del mercado inmobiliario, facilitando la interpretación y comparación de los resultados.

## Estructura del repositorio

\`\`\`text
dashboard/
    Proyecto_Final_Mercado_Inmobiliario.pbix
    README.md

data/
    raw/
        Dataset original del proyecto

notebooks/
    Proyecto_Final_Real_Estate.ipynb
    README.md

LICENSE
README.md
\`\`\`

## Archivos principales

- [Notebook de análisis exploratorio](notebooks/Proyecto_Final_Real_Estate.ipynb)
- [Dashboard de Power BI](dashboard/Proyecto_Final_Mercado_Inmobiliario.pbix)
- [Datos originales](data/raw/)

## Alcance y limitaciones

El análisis integra fuentes de distintos períodos, por lo que las comparaciones temporales deben interpretarse considerando posibles diferencias de cobertura, composición y representatividad entre los datasets.

Los resultados tienen finalidad exploratoria y académica; no constituyen una tasación inmobiliaria ni una estimación causal de la evolución del mercado.

## Formación académica

**Institución:** Universidad Tecnológica Nacional (UTN.BA) — Centro de e-Learning.

**Curso:** Herramientas básicas para el Análisis de Datos.

**Duración:** 9 semanas.

**Carga horaria:** 67 horas.

**Año:** 2026.

## Autor

**Diego Pignocchi**

Ingeniero en Alimentos | Formación en Data Analytics y Data Science

[Perfil de GitHub](https://github.com/pignocchidiego)

---

Proyecto desarrollado con fines académicos como trabajo final integrador del curso de UTN.BA.
