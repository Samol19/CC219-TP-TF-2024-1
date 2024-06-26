# CC219-TP-TF-2024-1

# Proyecto de Clasificación y Análisis de Sentimientos de Reseñas de Productos

## Objetivo del Trabajo

El objetivo del negocio propuesto es mejorar la satisfacción del cliente y optimizar la experiencia del usuario. Esto se traduce en un problema de minería de datos: desarrollar un sistema que clasifique automáticamente el sentimiento de las reseñas y prediga de una manera más acertada la calificación basada en el contenido de los comentarios. La correcta clasificación y valoración de las reseñas permitirá a la empresa tomar decisiones estratégicas informadas, mejorar la reputación y evitar pérdidas financieras y de clientes.

## Alumnos Participantes

| Alumno                                 | Rol             | Trabajo Principal                              |
|----------------------------------------|-----------------|-----------------------------------------------|
| Andres Joshua Rodriguez Guerrero - u202121973 | Data Scientist  | Desarrolla modelos de NLP                     |
| Fernando Samuel Paredes Espinoza - u202122837 | Data Analyst    | Análisis EDA - Procesamiento de textos        |
| Anthony Hans Tarrillo Ayllón - u202114233  | Data Scientist  | Interpretar métricas de desempeño del modelo  |

## Descripción del Dataset

Este conjunto de datos contiene documentos de productos de Amazon que incluyen categorías de productos y varios metadatos, así como la principal forma de clasificarlos por reseña. Cada reseña cuenta con un puntaje brindado por el usuario que servirá como punto base para determinar la actitud general de la misma reseña, ya sea positiva, negativa o neutra.

El dataset cuenta con un total de 11 columnas y 4914 filas y fue extraído de la plataforma Kaggle:
[Amazon Product Review Dataset](https://www.kaggle.com/datasets/tarkkaanko/amazon/data)

### Características del Dataset

| Característica       | Descripción                                                                                   |
|----------------------|-----------------------------------------------------------------------------------------------|
| reviewerName         | Nombre del usuario que realizó la reseña.                                                     |
| overall              | Puntaje brindado por la reseña (1-5).                                                         |
| reviewText           | Reseña brindada por el usuario.                                                               |
| reviewTime           | Fecha de publicación de la reseña.                                                            |
| day_diff             | Diferencia de días entre producto adquirido y reseña realizada.                               |
| helpful_yes          | Total de usuarios que les fue útil la reseña.                                                 |
| helpful_no           | Total de usuarios que no les fue útil la reseña.                                              |
| total_vote           | Votos totales de aprobación por la reseña brindada.                                           |
| score_pos_neg_diff   | Diferencia entre el puntaje de reseñas positivas y negativas.                                 |
| score_average_rating | Promedio de calificaciones de puntajes dados.                                                 |
| wilson_lower_bound   | Métrica brindada que representa un intervalo de confianza para la reseña.                     |

## Conclusiones

El trabajo realizado en la clasificación y análisis de sentimientos de reseñas de productos demuestra la importancia de esta técnica para los comercios electrónicos. Se implementaron cuatro modelos de machine learning para la clasificación de sentimientos, entre los cuales BERT se destacó como el más efectivo, mientras que los modelos de Scikit-Learn mostraron imprecisiones al analizar reseñas fuera de los conjuntos de prueba y entrenamiento. Los resultados obtenidos permiten identificar el sentimiento de un usuario independientemente del rating proporcionado, proporcionando una valiosa herramienta para la toma de decisiones estratégicas. A futuro, se recomienda continuar optimizando los modelos y ampliar el conjunto de datos etiquetados para mejorar la precisión y la capacidad de generalización de los modelos. Además, sería beneficioso explorar técnicas de análisis de temas y características para abordar divergencias en las opiniones de los clientes.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Para más detalles, consulte el archivo LICENSE en este repositorio.
