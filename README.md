📊 Análisis de Clientes y Patrones de Uso Telefónico
🧠 Objetivo del Proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de una empresa de telecomunicaciones a partir de información demográfica y de uso, con el fin de:

Evaluar la calidad y fiabilidad de los datos.

Identificar patrones de uso en llamadas y mensajes.

Analizar el comportamiento de los usuarios por rango de edad y nivel de consumo.

Detectar posibles oportunidades para estrategias de retención, adquisición y segmentación de clientes.

📁 Datasets Utilizados

El análisis se realizó utilizando tres conjuntos de datos:

plans.csv
Contiene información sobre los planes ofrecidos por la empresa (características y costos).

users.csv
Incluye información demográfica de los usuarios, como edad, ciudad, fecha de registro y fecha de cancelación (churn).

usage.csv
Registra el uso de los servicios por parte de los usuarios, incluyendo llamadas, mensajes, duración y tipo de actividad.

🔍 Etapas del Análisis Realizadas

Exploración inicial de los datos

Revisión de estructura, tipos de datos y dimensiones.

Identificación de columnas clave y consistencia de la información.

Análisis y tratamiento de valores nulos

Identificación de columnas con alta proporción de valores faltantes.

Justificación para conservar o excluir variables según su relevancia.

Clasificación de valores faltantes bajo el patrón MAR (Missing At Random).

Detección y manejo de valores inválidos

Identificación de sentinelas como edades con valor -999.

Evaluación de valores cero en variables de uso.

Propuesta de winsorización para mejorar la calidad del análisis.

Estandarización de formatos

Conversión de columnas a formatos correctos (fechas y numéricos).

Verificación de fechas irreales o futuras.

Segmentación de usuarios

Segmentación por rango de edad.

Segmentación por nivel de uso (bajo, medio y alto).

Análisis descriptivo

Comparación de llamadas y mensajes por grupos de edad.

Identificación de patrones homogéneos de comportamiento.

Análisis de outliers como usuarios de alto consumo.

Conclusiones y recomendaciones

Interpretación de resultados desde una perspectiva de negocio.

Propuestas para estrategias de retención y atracción de clientes.
