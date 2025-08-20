# telecomx_2
Implementación de analisis de datos en un caso real, parte 2
Predicción de Churn en Telecom X
📌 Descripción

Este repositorio contiene un proyecto de Machine Learning aplicado a datos de clientes de Telecom X, con el objetivo principal de predecir la cancelación de clientes (Churn). El proyecto abarca todo el flujo de un modelo predictivo: desde la extracción y preparación de datos, hasta el entrenamiento de distintos algoritmos, la evaluación de modelos y la interpretación de resultados para orientar estrategias de retención.

🎯 Misión

Desarrollar modelos predictivos capaces de identificar qué clientes tienen mayor probabilidad de cancelar sus servicios, permitiendo a la empresa anticiparse al problema y tomar decisiones estratégicas de retención.

🧠 Objetivos

Preparar los datos para el modelado (tratamiento, codificación, normalización).

Realizar análisis de correlación y selección de variables.

Entrenar múltiples modelos de clasificación (Regresión Logística, Random Forest, XGBoost).

Evaluar el rendimiento de los modelos con métricas como Accuracy, Recall, Precision, F1-score y AUC-ROC.

Interpretar los resultados, incluyendo la importancia de las variables.

Generar conclusiones estratégicas sobre los factores que influyen en la cancelación de clientes.

🧰 Tecnologías y Librerías Usadas

Lenguaje: Python 3.x

Librerías: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, xgboost, imblearn, pickle

Entornos compatibles: Jupyter Notebook, Google Colab

🗂️ Estructura del Proyecto
TelecomX_parte2/
├── README.md
├── Telecom_X2.ipynb           # Notebook principal con todo el análisis
├── datos_tratados.csv         # Dataset de clientes
└── champion_modelo_logistico.pkl  # Modelo entrenado

📂 Contenido del Notebook

El notebook Telecom_X2.ipynb está organizado en las siguientes secciones:

1. Extracción

Carga del dataset inicial.

2. Preparación de Datos

Codificación de variables categóricas.

Cálculo de proporción de clientes que cancelaron.

Análisis de correlación y multicolinealidad.

Balanceo de clases.

Estandarización de variables numéricas.

Análisis de relación entre variables y Churn.

3. Modelado Predictivo

Regresión Logística

Random Forest

XGBoost

4. Evaluación de Modelos

Evaluación en el conjunto de entrenamiento.

Validación cruzada y métricas de desempeño.

5. Interpretación y Conclusiones

Importancia de variables en cada modelo.

Identificación de factores de riesgo y estrategias de retención.

📊 Dataset

Fuente: Dataset ficticio de clientes de Telecom X.

Observaciones: ~7,000 clientes.

Variable objetivo: Churn (1 = cliente canceló, 0 = cliente activo).

Variables predictoras:

Datos demográficos (género, edad, etc.)

Tiempo como cliente (tenure)

Tipo de contrato (Contract)

Servicios contratados (InternetService, PhoneService, etc.)

Cargos (Charges.Monthly, Charges.Total)

🚀 Cómo ejecutar el proyecto

Clonar el repositorio:

git clone https://github.com/JotaDC/TelecomX_parte2.git
cd TelecomX_parte2


Instalar dependencias:

pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost imblearn pickle


Abrir el notebook:

Ejecutar Telecom_X2.ipynb en Jupyter Notebook o Google Colab y seguir las celdas paso a paso.

📈 Resultados esperados

Comparación del desempeño entre distintos modelos de clasificación.

Identificación de las variables más importantes para explicar el Churn.

Conclusiones que orientan la retención de clientes y recomendaciones estratégicas basadas en los factores de cancelación.
