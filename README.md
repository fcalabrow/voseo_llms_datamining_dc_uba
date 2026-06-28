Este repositorio incluye el código y los datos necesarios para reproducir los resultados del artículo "'¿Vos qué sabés?' Conocimiento implícito del voseo en LLMs pequeños y medianos", realizado por Facundo Calabró como trabajo final de la Especialización en Explotación de Datos y el Descubrimiento del Conocimiento (FCEN-UBA).

# Datos
- `input_scores.csv`: el dataset utilizado para obtener los scores (deltas) referidos en el artículo.
- `input_regresion.csv`: los scores obtenidos por registro y modelo, que se utilizan como input en la regresión.

# Scripts
- `scores.ipynb`: funciones utilizadas para cargar los modelos y obtener los scores.
- `regresion.ipynb`: funciones utilizadas para ajustar la regresión multinivel.