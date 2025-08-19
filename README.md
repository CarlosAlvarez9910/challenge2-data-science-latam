# challenge2-data-science-latam
# Análisis de Cancelación de Clientes (Churn) en TelecomX

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar los factores que influyen en la cancelación de clientes (churn) para la empresa de telecomunicaciones TelecomX. Se utilizan técnicas de análisis de datos y modelado predictivo para identificar a los clientes en riesgo de abandonar el servicio y proponer estrategias de retención basadas en los hallazgos.

## Contenido del Repositorio

*   `TelecomX_Data.json`: Archivo de datos original utilizado para el análisis.
*   `tu_notebook.ipynb`: El notebook de Google Colab que contiene el código para la carga de datos, limpieza, preprocesamiento, modelado y evaluación. (Reemplaza `tu_notebook.ipynb` con el nombre real de tu archivo de notebook).
*   `README.md`: Este archivo.

## Cómo Ejecutar el Notebook

1.  Clona este repositorio en tu máquina local o descárgalo como un archivo ZIP.
2.  Sube el archivo `TelecomX_Data.json` y el archivo del notebook (`tu_notebook.ipynb`) a tu entorno de Google Colab.
3.  Abre el notebook en Google Colab.
4.  Ejecuta las celdas del notebook en secuencia para replicar el análisis. Asegúrate de tener instaladas las bibliotecas necesarias (pandas, scikit-learn, seaborn, matplotlib). Si usas Google Colab, la mayoría ya estarán preinstaladas.

## Fuente de Datos

Los datos utilizados en este análisis provienen del archivo `TelecomX_Data.json`.

## Metodología

El análisis incluye las siguientes etapas:

1.  **Carga y Exploración de Datos:** Carga del archivo JSON y comprensión de la estructura de los datos.
2.  **Limpieza y Preprocesamiento:** Normalización de columnas anidadas, manejo de valores nulos y vacíos, y codificación de variables categóricas.
3.  **Análisis Exploratorio de Datos (EDA):** Visualización de la distribución de variables y exploración de relaciones entre ellas, especialmente con la variable objetivo 'Churn'.
4.  **División de Datos:** División del conjunto de datos en conjuntos de entrenamiento y prueba.
5.  **Modelado Predictivo:** Entrenamiento de modelos de clasificación (Regresión Logística y Árbol de Decisión) para predecir la cancelación.
6.  **Evaluación del Modelo:** Evaluación del rendimiento de los modelos utilizando métricas como Exactitud, Precisión, Recall, F1-score y Matriz de Confusión.
7.  **Análisis de Importancia de Variables:** Identificación de las variables más relevantes para la predicción de la cancelación según cada modelo.
8.  **Informe y Estrategias de Retención:** Elaboración de un informe con los hallazgos clave y propuestas de estrategias de retención.
##**Autor**
***Jose Carlos Alvarez Onofre***
