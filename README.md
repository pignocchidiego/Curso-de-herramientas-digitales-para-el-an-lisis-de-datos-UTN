# Análisis Exploratorio del Mercado Inmobiliario | UTN

## Descripción del proyecto

Proyecto final integrador del curso **Herramientas básicas para el Análisis de Datos**, dictado por el Centro de e-Learning de la Universidad Tecnológica Nacional (UTN.BA).

El proyecto consiste en un análisis exploratorio del mercado inmobiliario de la Ciudad Autónoma de Buenos Aires (CABA) y el Gran Buenos Aires, utilizando herramientas de procesamiento, análisis y visualización de datos.

Se integran conjuntos de datos inmobiliarios históricos y actuales para estudiar la evolución de los precios, las diferencias entre tipos de propiedades y la distribución territorial de los valores.

El trabajo combina análisis exploratorio en Python, visualizaciones estadísticas y un dashboard desarrollado en Power BI.

## Objetivos

- Analizar la evolución de los precios inmobiliarios entre 2017 y 2026.
- Comparar los precios promedio de diferentes tipos de propiedades.
- Identificar los barrios con mayores valores inmobiliarios.
- Analizar los precios promedio por metro cuadrado.
- Aplicar técnicas de limpieza, transformación y exploración de datos.
- Comunicar resultados mediante visualizaciones en Python y un dashboard en Power BI.

## Herramientas utilizadas

- **Microsoft Excel:** revisión, organización y preparación de datos.
- **Python:** procesamiento y análisis exploratorio.
- **pandas:** manipulación, limpieza y transformación de datasets.
- **matplotlib y seaborn:** elaboración de visualizaciones estadísticas.
- **Google Colab:** desarrollo y ejecución del notebook.
- **Power BI:** creación de indicadores, gráficos y dashboard.
- **GitHub:** organización, documentación y publicación del proyecto.

## Fuentes de datos

Se utilizaron tres conjuntos de datos del mercado inmobiliario:

- **REMAX 2026:** información inmobiliaria correspondiente a 2026.
- **Properati histórico:** registros inmobiliarios históricos.
- **Properati 2017:** información inmobiliaria correspondiente a 2017.

Los datasets contienen variables relacionadas con:

- Precios de propiedades expresados en USD.
- Precios promedio por metro cuadrado.
- Ubicación geográfica y barrios.
- Tipos de propiedades y operaciones.
- Superficies totales, cubiertas y descubiertas.
- Cantidad de ambientes.
- Antigüedad y estado de conservación.
- Otras características inmobiliarias.

## Metodología

### 1. Preparación y limpieza de datos

Se realizaron tareas de procesamiento para mejorar la consistencia de los datos:

- Integración de diferentes fuentes inmobiliarias.
- Estandarización de nombres de columnas y categorías.
- Normalización de barrios y ubicaciones geográficas.
- Tratamiento de valores faltantes.
- Revisión de registros duplicados.
- Normalización de formatos numéricos y temporales.
- Construcción de una base consolidada para el análisis.

### 2. Análisis exploratorio con Python

Se utilizaron herramientas de Python y pandas para:

- Inspeccionar la estructura del DataFrame.
- Obtener estadísticas descriptivas.
- Evaluar valores faltantes y registros duplicados.
- Analizar variables numéricas y categóricas.
- Explorar relaciones entre variables.
- Identificar patrones y diferencias en los precios inmobiliarios.

### 3. Visualización de resultados

Se desarrollaron gráficos para analizar:

- Evolución del precio promedio en USD por año.
- Precio promedio en USD según tipo de propiedad.
- Los 10 barrios con mayores precios promedio.
- Evolución del precio promedio por metro cuadrado.

Las visualizaciones permiten explorar tendencias y diferencias entre segmentos del mercado inmobiliario.

### 4. Dashboard en Power BI

Se desarrolló un dashboard para presentar indicadores y visualizaciones del mercado inmobiliario.

El tablero permite comunicar los principales resultados del análisis mediante una presentación visual, facilitando la interpretación y comparación de los datos.

## Estructura del repositorio

```text
Curso-de-herramientas-digitales-para-el-an-lisis-de-datos-UTN/
├── dashboard/
│   ├── Proyecto_Final_Mercado_Inmobiliario.pbix
│   └── README.md
├── data/
│   └── raw/
│       ├── Dataset Real_Estate.xlsm
│       └── README.md
├── notebooks/
│   ├── Proyecto_Final_Real_Estate.ipynb
│   └── README.md
├── LICENSE
└── README.md
```

## Archivos principales

- [Notebook de análisis exploratorio](notebooks/Proyecto_Final_Real_Estate.ipynb)
- [Dashboard de Power BI](dashboard/Proyecto_Final_Mercado_Inmobiliario.pbix)
- [Dataset original](data/raw/Dataset%20Real_Estate.xlsm)

## Alcance y limitaciones

El análisis integra fuentes correspondientes a distintos períodos, por lo que las comparaciones temporales deben interpretarse considerando posibles diferencias de cobertura, composición y representatividad entre los datasets.

Los resultados tienen una finalidad exploratoria y académica. No constituyen una tasación inmobiliaria ni una estimación causal de la evolución de los precios del mercado.

Las conclusiones se encuentran condicionadas por la calidad, disponibilidad y características de los datos utilizados.

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

Proyecto desarrollado con fines académicos como trabajo final integrador del curso Herramientas básicas para el Análisis de Datos de UTN.BA.
