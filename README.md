# Telecom-X-Parte-1-

Telecom X – Análisis de Evasión de Clientes (Parte 1)
Descripción del Proyecto

En este proyecto, se analiza la evasión de clientes (Churn) de Telecom X, una empresa de telecomunicaciones que enfrenta una alta tasa de cancelaciones. El objetivo es comprender los factores que influyen en la pérdida de clientes y generar información valiosa que sirva de base para futuros modelos predictivos y estrategias de retención.

Durante el análisis se trabajó con datos demográficos, tipo de servicio contratado, estado de cuenta y comportamiento de los clientes, aplicando técnicas de ETL, limpieza de datos y análisis exploratorio (EDA).

Objetivos

Importar y manipular datos desde la API de Telecom X.

Limpiar y transformar los datos para asegurar coherencia y consistencia.

Explorar la distribución de la evasión de clientes y su relación con variables demográficas, de servicio y financieras.

Identificar patrones y tendencias mediante visualizaciones estratégicas.

Generar un informe con insights accionables para reducir la evasión.

Metodología

Carga y normalización de datos: Se importaron los datos en formato JSON desde la API y se convirtieron a un DataFrame de Pandas.

Limpieza y tratamiento:

Eliminación de valores nulos o inconsistentes.

Estandarización de nombres de columnas y categorías.

Conversión de variables numéricas y categóricas al formato adecuado para análisis.

Análisis exploratorio de datos (EDA):

Distribución de clientes según Churn.

Comparación de variables numéricas como tiempo de contrato y gasto total entre clientes activos y cancelados.

Distribución de variables categóricas como tipo de contrato, género y método de pago.

Visualización: Se generaron gráficos de barras, boxplots e histogramas para facilitar la interpretación de los resultados.

Identificación de insights: Se determinaron los factores más relevantes asociados a la cancelación de clientes.

Principales hallazgos

Los clientes con menos tiempo de contrato y gastos totales más bajos presentan mayor riesgo de cancelación.

La presencia de servicios adicionales (como seguridad online y soporte técnico) disminuye la probabilidad de Churn.

Algunos patrones se repiten de manera consistente entre variables numéricas y categóricas, lo que facilita la toma de decisiones estratégicas.

Tecnologías y Herramientas Utilizadas

Python

Pandas

Matplotlib & Seaborn

Jupyter Notebook

Resultado

El análisis permitió generar un informe claro con insights accionables para Telecom X, sirviendo como base para la Parte 2: Modelos Predictivos de Cancelación, donde se desarrollarán modelos de Machine Learning para anticipar la evasión de clientes.
