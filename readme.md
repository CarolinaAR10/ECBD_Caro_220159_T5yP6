# Tarea 05, Práctica 06, Práctica 07 y Práctica 08

## Elaborado por Carolina Arias Reyes  
Grupo: 9A IDGS  
Fecha: 24/06/2025  
Asignatura: Extracción de Conocimientos de Base de Datos  
Profesor: Marco A. Ramírez Hernández

---

### 📌 Descripción General del Proyecto

Este conjunto de prácticas se enfoca en el desarrollo de habilidades para la **extracción, transformación, análisis y visualización de datos** provenientes de diversas fuentes estructuradas y no estructuradas, aplicando herramientas como **Python, Pandas, SQLAlchemy, PyMongo, Scikit-learn y Seaborn**, ejecutadas principalmente en **Jupyter Notebook**. Las actividades simulan entornos reales de integración de datos (ETL) y análisis exploratorio con fines predictivos.

---

### 🎯 Objetivo General

Aplicar el proceso ETL y técnicas de análisis exploratorio de datos sobre diferentes fuentes (MySQL, API REST, MongoDB) con el fin de preparar datasets confiables para tareas de modelado, visualización y toma de decisiones.

---

### 🔄 Práctica 06 y Tarea 05: Proceso ETL Multifuente

**Fuentes de datos utilizadas:**
- 🗃️ **MySQL**: Extracción desde la tabla `salaries_ia`, limpieza de nulos, conversión de tipos y transformación de columnas.
- 🔗 **API REST (Pokémon)**: Obtención de datos vía `requests`, desanidamiento JSON, creación de columnas derivadas.
- 🍃 **MongoDB Atlas**: Carga de colección `salaries_ia`, procesamiento con `pymongo`, exportación de documentos a MySQL con `SQLAlchemy`.

**Actividades clave:**
- Conexión y extracción desde fuentes relacional, API y NoSQL ✅
- Limpieza y transformación con Pandas ✅
- Creación de tabla temporal en MySQL ✅
- Exportación entre motores ✅
- Validación y pruebas por etapa ✅

---

### 📊 Práctica 07: Análisis Salarial en Ciencia de Datos

Se desarrolló un análisis basado en un conjunto simulado del dataset “AI, ML & Data Science Salaries”, replicando el flujo del notebook original de Kaggle.

**Pasos realizados:**
1. **Limpieza y estandarización de datos** (títulos, países, experiencia).  
2. **Análisis descriptivo**: media, mediana, rango y desviación estándar.  
3. **Comparaciones** por nivel de experiencia, tipo de empleo y ubicación.  
4. **Visualizaciones**: `barplot`, `boxplot`, `scatter`, etc.  
5. **Modelo predictivo**: regresión lineal con `LinearRegression`.  
6. **Clustering**: segmentación de salarios con `KMeans`.

**Herramientas:** pandas, matplotlib, seaborn, sklearn

---

### 📈 Práctica 08: Investigación de Skewness y Kurtosis

En esta actividad se estudió el comportamiento de dos medidas estadísticas:

- 📐 **Skewness (Asimetría)**: Identificación de la inclinación de la distribución.
- ⛰️ **Kurtosis (Curtosis)**: Medición del grado de concentración en los extremos.

**Incluye:**
- Explicación teórica de ambos conceptos (definición, uso, ventajas, desventajas y ejemplos).
- Implementación práctica en Python con `scipy.stats`, `numpy` y `matplotlib`.
- Gráficas para tres casos en cada medida: normal, alta y baja asimetría/curtosis.

**Resultados:** se observaron distribuciones con comportamientos reales comunes en ciencia de datos: distribuciones sesgadas (asimetría) y colas pesadas o ligeras (curtosis).

---

### ✅ Conclusión

Estas prácticas consolidan el dominio de la manipulación de datos en múltiples entornos, preparación para modelos analíticos y aplicación de estadística descriptiva avanzada. Se cumplió con los objetivos del curso de forma progresiva, reforzando tanto el conocimiento técnico como analítico.
