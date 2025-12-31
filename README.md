# 📊 Análisis de Deserción en Telecomunicaciones (Churn Analysis)

Este repositorio contiene un análisis exhaustivo de datos orientado a identificar los factores que influyen en la salida de clientes de la compañía de telecomunicaciones Telecom X. El proyecto abarca desde la extracción de datos vía API hasta la generación de recomendaciones estratégicas basadas en hallazgos estadísticos.
## 📝 Descripción del Proyecto

El objetivo principal es entender por qué los clientes abandonan la compañía, evaluando variables como el tipo de contrato, la antigüedad, los cargos mensuales y los servicios adicionales. El análisis permite segmentar a los usuarios vulnerables y proponer planes de fidelización efectivos.
## 🚀 Tecnologías Utilizadas

* Lenguaje: Python 3.x

* Librerías principales:

* Pandas: Manipulación y limpieza de datos.

* Matplotlib & Seaborn: Visualización de datos y gráficos estadísticos.

* NumPy: Operaciones matemáticas avanzadas.

* Requests: Extracción de datos desde APIs externas.

* Entorno: Google Colab / Jupyter Notebook.

## 🔍 Hallazgos Principales

Tras el procesamiento de los datos, se identificaron los siguientes puntos críticos:

* Vulnerabilidad por Antigüedad: El segmento de clientes con menos de 29 meses de permanencia.

* Modelos de Contrato: El formato de contrato "mes a mes" es un facilitador de la fuga de clientes.

* Sensibilidad al Precio: Altas bajas en usuarios con cargos mensuales de hasta $94.2 USD.

* Servicios de Valor: La falta de servicios como seguridad online y soporte técnico correlaciona positivamente con la deserción.

## 🛠️ Estructura del Notebook

El archivo Telecom.ipynb sigue el siguiente flujo de trabajo:

* Preparación del ambiente: Importación de dependencias.

* Extracción (API): Obtención de datos en formato JSON.

* Limpieza y Transformación: Manejo de datos nulos y normalización.

* Análisis Exploratorio (EDA): Visualización de distribución de bajas y comportamiento de consumo.

* Conclusiones y Estrategia: Recomendaciones de negocio.


## ⚙️ Cómo ejecutar

* Sube el archivo Telecom X.ipynb a Google Colab.

* Asegúrate de tener conexión a internet para que la celda de requests.get() pueda obtener los datos de la API.

* Ejecuta las celdas en orden secuencial.
