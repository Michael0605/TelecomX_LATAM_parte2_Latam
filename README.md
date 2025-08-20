# TelecomX_LATAM_parte2_Latam

📄 README.md para el Repositorio de GitHub
📝 Análisis Predictivo de Cancelación de Clientes
Este repositorio contiene el código y los recursos utilizados para un proyecto de análisis y modelado predictivo enfocado en la cancelación de clientes (customer churn). El objetivo principal es identificar los factores clave que influyen en la deserción de clientes y desarrollar modelos de machine learning para predecir qué clientes tienen un alto riesgo de cancelar un servicio.

🚀 Contenido del Repositorio
datos/: Directorio que contiene el dataset original y los datos preprocesados.

notebooks/: Archivos de Jupyter Notebook (.ipynb) que documentan el proceso de análisis, preprocesamiento de datos, visualización y modelado.

1_EDA_y_Preprocesamiento.ipynb: Análisis Exploratorio de Datos (EDA) y la limpieza del dataset.

2_Modelado_Predictivo.ipynb: Creación y evaluación de varios modelos de machine learning.

scripts/: Archivos Python (.py) con funciones reutilizables.

informes/: Reportes y visualizaciones generados durante el proyecto.

Informe_Final.pdf: Resumen de los hallazgos, el rendimiento de los modelos y las estrategias de retención propuestas.

📊 Análisis Realizado
Análisis Exploratorio de Datos (EDA): Se investigó la distribución de las variables y se detectaron patrones iniciales.

Limpieza y Preprocesamiento: Se trataron valores nulos, se eliminaron variables irrelevantes y se codificaron variables categóricas.

Análisis de Correlación: Se visualizó la matriz de correlación para identificar las relaciones entre las variables numéricas y el target (Churn_Binario).

Modelado Predictivo: Se entrenaron y evaluaron los siguientes modelos de clasificación:

Regresión Logística

Random Forest

XGBoost

Árbol de Decisión

SVC

KNN

✅ Resultados Destacados
Factores de Mayor Influencia: Se encontró una fuerte correlación negativa entre la cancelación y el tenure (antigüedad del cliente), lo que sugiere que los clientes nuevos son más propensos a cancelar.

Mejor Modelo: XGBoost demostró ser el modelo con mejor rendimiento, logrando una alta precisión y una capacidad superior para predecir a los clientes que cancelan.

Estrategias de Retención: Se proponen acciones específicas basadas en los hallazgos, como programas de incorporación para clientes nuevos y ofertas personalizadas para clientes de alto riesgo.

🛠️ Tecnologías y Librerías
Python 3.x

Pandas: Manipulación y análisis de datos.

NumPy: Operaciones numéricas.

Matplotlib y Seaborn: Visualizaciones de datos.

Scikit-learn: Modelado, evaluación y preprocesamiento de machine learning.

XGBoost: Algoritmo de Gradient Boosting.

🤝 Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar el código o el análisis, por favor, crea un pull request o abre un issue para discutirlo.

Autor: Michael Ruiz Esquivel
Fecha: 18/8/25
