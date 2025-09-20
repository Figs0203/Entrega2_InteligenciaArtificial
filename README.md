# Proyecto: Predicción de Alzheimer

Este repositorio contiene el desarrollo de un proyecto de Machine Learning para predecir la presencia de la enfermedad de Alzheimer en pacientes, a partir de datos clínicos, demográficos y de estilo de vida.

---

## Contenido del repositorio

* `alzheimers_disease_data.csv`: Dataset con información de pacientes, incluye variables clínicas, hábitos de vida y resultados de pruebas cognitivas.
* `desarrollo.ipynb`: Notebook con el análisis exploratorio de datos (EDA), limpieza, preprocesamiento y pruebas  de modelos de Machine Learning.
* `README.md`: Documento con la descripción general del proyecto, su estructura y objetivos.

---

## Objetivo del proyecto

El propósito de este proyecto es desarrollar un modelo de Machine Learning capaz de predecir el diagnóstico de Alzheimer en pacientes. A partir de características clínicas y de estilo de vida, se busca:

* Explorar y comprender los factores asociados al Alzheimer.
* Construir modelos que permitan detectar la enfermedad de forma temprana.
* Evaluar la calidad y precisión de distintos algoritmos de clasificación.

---

## Hallazgos del Análisis Exploratorio (EDA)

En el notebook `desarrollo.ipynb` se realizó un análisis exploratorio para entender la distribución de los datos y las relaciones entre las variables. A continuación se describen algunos de los diagramas y hallazgos clave que se podrían documentar:

*   **Distribución de Diagnósticos:** Un gráfico de barras para visualizar la proporción de pacientes en cada categoría de diagnóstico (ej. No Dementes, Dementes Leves, etc.). Esto es crucial para identificar el desbalance de clases.

*   **Correlación entre Variables Numéricas:** Un mapa de calor (heatmap) que muestre la correlación de Pearson entre variables como `Age`, `MMSE` (Mini-Mental State Examination), `EducationLevel`, etc. Ayuda a identificar multicolinealidad y variables predictivas importantes.

*   **Distribución de Características por Diagnóstico:** Diagramas de caja (boxplots) o de violín para comparar la distribución de variables numéricas clave (como `Age` o `MMSE`) entre los diferentes grupos de diagnóstico. Permiten observar si existen diferencias significativas entre los grupos.

*   **Análisis de Variables Categóricas:** Gráficos de barras para analizar la relación entre variables categóricas (como `Gender`, `Smoking`, `AlcoholConsumption`) y el diagnóstico.

---

## Tecnologías utilizadas

* **Lenguaje:** Python
* **Bibliotecas principales:**

  * `pandas`, `numpy` para manipulación y análisis de datos.
  * `matplotlib`, `seaborn` para visualización de datos.
  * `scikit-learn` para modelado y evaluación de algoritmos de Machine Learning.
  * `tensorflow`, `keras` para construcción y entrenamiento de modelos de Deep Learning.
  * `imblearn` para generación de muestra artificial

---

## Cómo ejecutar el proyecto

1. Clonar el repositorio:

   ```bash
   git clone <url-del-repositorio>
   ```
2. Abrir y ejecutar el notebook `desarrollo.ipynb` paso a paso.
3. Explorar el dataset `alzheimers_disease_data.csv` y seguir los pasos del flujo de trabajo en el notebook.

---

## Autores

 * Agustín Figueroa
 * Estebán Álvarez
 * Alejandro Sepúlveda

Estudiantes de Ingeniería de Sistemas - Universidad EAFIT
