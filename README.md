# Alura-Challenge-2-Telecom-X

Telecom X - Análisis de Evasión de Clientes

Has sido contratado como asistente de análisis de datos en Telecom X y formarás parte del proyecto "Churn de Clientes". La empresa enfrenta una alta tasa de cancelaciones y necesita comprender los factores que llevan a la pérdida de clientes.

Tu desafío será recopilar, procesar y analizar los datos, utilizando Python y sus principales bibliotecas para extraer información valiosa. A partir de tu análisis, el equipo de Data Science podrá avanzar en modelos predictivos y desarrollar estrategias para reducir la evasión.

¿Qué vas a practicar?

✅ Importar y manipular datos desde una API de manera eficiente.
✅ Aplicar los conceptos de ETL (Extracción, Transformación y Carga) en la preparación de los datos.
✅ Crear visualizaciones estratégicas para identificar patrones y tendencias.
✅ Realizar un Análisis Exploratorio de Datos (EDA) y generar un informe con insights relevantes.

¡Ahora es tu turno! 🚀 Usa tus conocimientos para transformar datos en información estratégica y ayudar a Telecom X a retener más clientes.


Informe de Análisis de Evasión de Clientes (Churn)

Introducción

El objetivo de este análisis fue explorar el problema de la evasión de clientes (Churn) en una empresa de telecomunicaciones. La evasión de clientes se refiere a la pérdida de clientes que deciden cancelar sus servicios. Comprender los factores que influyen en la decisión de los clientes de cancelar sus servicios es crucial para implementar estrategias efectivas de retención. Este análisis se centra en identificar patrones en las características de los clientes que han cancelado sus servicios en comparación con aquellos que no lo han hecho.

Limpieza y Tratamiento de Datos
Pasos Realizados:
Importación de Datos: Se cargaron los datos desde un archivo JSON utilizando la biblioteca pandas.

Clasificación de Churn: Se clasificó la columna Churn para identificar a los clientes que han cancelado sus servicios. Se asignó el valor Yes a aquellos que cumplen con ciertas condiciones y No a los demás.

Limpieza de Datos: Se revisaron y limpiaron los datos, eliminando o imputando valores faltantes y asegurando que las columnas categóricas y numéricas estuvieran en el formato adecuado.

Análisis Exploratorio de Datos
Distribución de Evasión según Variables Categóricas
Se exploró la distribución de la evasión según variables categóricas como género, tipo de contrato y método de pago. A continuación, se presentan gráficos de barras que muestran la distribución de la evasión:

Distribución de Variables Numéricas
Se analizaron variables numéricas como "Total Gastado" y "Tiempo de Contrato" para observar su relación con la evasión. Se utilizaron gráficos de violín para visualizar estas distribuciones:

Conclusiones e Insights
Patrones en Variables Categóricas: Se observó que ciertos grupos demográficos, como el género y el tipo de contrato, tienen tasas de evasión significativamente diferentes. Por ejemplo, los clientes con contratos mensuales tienden a cancelar más que aquellos con contratos anuales.

Relación con Variables Numéricas: Los gráficos de violín mostraron que los clientes que cancelaron tienden a tener un total gastado más bajo y un tiempo de contrato más corto en comparación con los que no cancelaron.

Recomendaciones

Estrategias de Retención: Implementar programas de fidelización dirigidos a clientes con contratos mensuales, ofreciendo incentivos para que consideren la renovación de sus contratos.

Análisis de Precios: Revisar la estructura de precios y los servicios ofrecidos a los clientes que han gastado menos, para identificar oportunidades de mejora y retención.

Mejorar la Experiencia del Cliente: Realizar encuestas de satisfacción para entender mejor las razones detrás de la cancelación y mejorar la experiencia del cliente.

Segmentación de Clientes: Utilizar los hallazgos para segmentar a los clientes y personalizar las ofertas y comunicaciones, enfocándose en aquellos con mayor riesgo de evasión.

