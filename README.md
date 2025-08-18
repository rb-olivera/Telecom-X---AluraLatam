# Telecom X – PARTE UNO

Este proyecto forma parte del Challenge de Alura Latam – Data Science. El objetivo fue analizar datos de clientes de Telecom X con el fin de comprender los factores que influyen en la evasión de clientes (churn) y generar insights estratégicos que permitan diseñar acciones de retención.

### 🚀 Objetivos

Importar datos desde una API y aplicar un proceso ETL (Extracción, Transformación y Carga).

Realizar un Análisis Exploratorio de Datos (EDA) con foco en los patrones de cancelación.

Generar visualizaciones estratégicas que expliquen tendencias clave.

Extraer insights accionables y proponer recomendaciones de negocio para reducir el churn.

### 🛠️ Tecnologías utilizadas

Python 3.11

Bibliotecas: pandas, numpy, matplotlib, seaborn

Google Colab (entorno principal de ejecución)

### 📂 Estructura del repositorio

TelecomX_ParteUno.ipynb: Notebook principal con el ETL, EDA, visualizaciones y el informe final.

data/: Carpeta opcional para almacenar datasets locales (si fuera necesario).

### 🔎 Principales hallazgos

Los clientes con contratos mensuales muestran mayor probabilidad de churn.

La antigüedad (tenure) baja se asocia fuertemente con evasión.

Cargos mensuales altos sin servicios de valor agregado incrementan la tasa de cancelación.

Los clientes con pagos automáticos y facturación digital presentan mayor retención.

Bundles de servicios adicionales (internet premium, streaming, soporte) reducen significativamente el churn.

### 💡 Recomendaciones

Incentivar la migración de contratos mensuales a planes anuales mediante descuentos o beneficios.

Crear un programa de retención temprana en los primeros 90 días de servicio.

Ofrecer paquetes de valor (bundles con servicios extra) para mejorar la percepción de beneficio.

Fomentar el uso de pagos automáticos para reducir la fricción en la experiencia.

Desarrollar un modelo predictivo de churn como siguiente paso.

### 📈 Próximos pasos

Implementar un modelo de Machine Learning (ejemplo: regresión logística, Random Forest) para predecir qué clientes tienen mayor riesgo de churn.

Integrar métricas de satisfacción del cliente y calidad de servicio para mejorar la precisión.

Diseñar campañas de retención segmentadas en base a perfiles de riesgo.

### 👩‍💻 Autora

Proyecto desarrollado por Rebeca Olivera como parte del programa de formación en Data Science – Alura Latam & Oracle.
