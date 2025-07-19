# Examen de Clasificación de Diabetes - Análisis y Modelado Predictivo

## 📚 Descripción General del Proyecto

Este repositorio contiene la resolución del examen de clasificación de diabetes, utilizando el "Diabetes Dataset" disponible en Kaggle. El objetivo principal de este proyecto es desarrollar y evaluar modelos predictivos capaces de identificar si un paciente padece diabetes basándose en diversas características de salud.

El proyecto abarca las siguientes fases clave:
1.  **Preparación del Entorno y Carga de Datos:** Configuración inicial y carga del dataset.
2.  **Limpieza y Preprocesamiento de Datos:** Manejo de valores duplicados, verificación de tipos de datos, y tratamiento específico de valores cero anómalos (que representan datos faltantes) en columnas clave, imputándolos con la mediana.
3.  **Exploración de Datos (EDA):** Análisis descriptivo, visualizaciones univariadas y multivariadas para entender las distribuciones de las características, identificar patrones y relaciones, y observar el balance de la variable objetivo.
4.  **Implementación de Modelos de Clasificación:** Entrenamiento de dos modelos robustos: **Random Forest** y **XGBoost**.
5.  **Evaluación de Modelos:** Medición del rendimiento de ambos modelos utilizando métricas clave como Accuracy, Precision, Recall, F1-Score y ROC-AUC, acompañadas de matrices de confusión y curvas ROC.
6.  **Comparación y Discusión Final:** Un análisis comparativo de los modelos y una conclusión sobre cuál sería el más adecuado para este problema, priorizando la minimización de falsos negativos.

## 📁 Contenido del Repositorio

* `examen_diabetes_final.ipynb`: El notebook Jupyter que contiene todo el código fuente del análisis, preprocesamiento, modelado y evaluación.
* `diabetes.csv`: El dataset original utilizado para este proyecto.
* `README.md`: Este archivo, proporcionando una descripción general del proyecto.

## 🛠️ Requisitos y Dependencias

Para ejecutar este notebook y replicar el análisis, necesitarás tener instalado Python y las siguientes librerías:

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`
* `xgboost`

Puedes instalar estas dependencias usando pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
