# Prácticas de R

Este repositorio reúne las prácticas y análisis realizados en R como parte del curso, en formato R Markdown (`.Rmd`). Cada semana se agrega un nuevo archivo con el trabajo correspondiente.

## Archivos

### `Introducción_a_R.Rmd`
Práctica introductoria a R. Cubre conceptos básicos del lenguaje: creación de fragmentos de código, asignación y redefinición de variables (`<-`), la función `seq()` para generar secuencias, y una primera aproximación a graficar con `plot()` (incluyendo el uso del parámetro `type`).

### `analisis_pizza.Rmd`
Primer análisis exploratorio sobre el dataset `pizza_delivery.csv`. Incluye carga de datos con `readr`, medidas de tendencia central y dispersión de la variable `temperature` (`mean`, `median`, `var`, `sd`, rango), y tablas de frecuencia y proporciones para las variables `branch` y `driver` (`table`, `prop.table`). Cada bloque de código tiene su explicación en texto justo debajo.

### `Pizza_Delivery_2_0.Rmd`
Segunda versión del análisis del dataset `pizza_delivery.csv`, reorganizada en secciones: cada bloque de código agrupa 1 o 2 funciones afines, con la explicación como texto en Markdown antes del bloque. Incluye tabla y gráficos de frecuencia del conductor, histograma y boxplot de `temperature`, cálculo de cuartiles, y detección de valores atípicos moderados y extremos mediante el rango intercuartílico.

- Cada semana se añade un nuevo `.Rmd` con la práctica o análisis correspondiente.
