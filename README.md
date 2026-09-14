#Prácticas de R

Este repositorio reúne las prácticas y análisis realizados en R como parte del curso, en formato R Markdown (.Rmd). Cada semana se agrega un nuevo archivo con el trabajo correspondiente.

##Archivos

###Introducción_a_R.Rmd Práctica introductoria a R. Cubre conceptos básicos del lenguaje: creación de fragmentos de código, asignación y redefinición de variables (<-), la función seq() para generar secuencias, y una primera aproximación a graficar con plot() (incluyendo el uso del parámetro type).

###analisis_pizza.Rmd Primer análisis exploratorio sobre el dataset pizza_delivery.csv. Incluye carga de datos con readr, medidas de tendencia central y dispersión de la variable temperature (mean, median, var, sd, rango), y tablas de frecuencia y proporciones para las variables branch y driver (table, prop.table). Cada bloque de código tiene su explicación en texto justo debajo.

###Pizza_Delivery_2_0.Rmd Segunda versión del análisis del dataset pizza_delivery.csv, reorganizada en secciones: cada bloque de código agrupa 1 o 2 funciones afines, con la explicación como texto en Markdown antes del bloque. Incluye tabla y gráficos de frecuencia del conductor, histograma y boxplot de temperature, cálculo de cuartiles, y detección de valores atípicos moderados y extremos mediante el rango intercuartílico.

###Experimento.Rmd Práctica sobre distribuciones de probabilidad discretas. Cubre la diferencia entre los prefijos d, p y q en R (densidad puntual, acumulada y quantil respectivamente) y el uso de dbinom y pbinom sobre la distribución binomial. Incluye ejercicios de probabilidad acumulada, probabilidad de un rango mediante resta de acumuladas, y el cálculo del complemento para resolver probabilidades del tipo "mayor que".

###Experimento2.Rmd Continuación de la práctica sobre distribuciones de probabilidad. Retoma la binomial (probabilidad puntual y acumulada, valor esperado y varianza) y agrega su aproximación mediante la distribución Normal con corrección por continuidad. Incluye un ejercicio con n grande resuelto por dos métodos (suma manual con dbinom en un ciclo for y directamente con pbinom) para comparar resultados, y cierra con ejercicios de distribución de Poisson usando dpois y ppois (probabilidad puntual, acumulada y complemento).

Cada semana se añade un nuevo .Rmd con la práctica o análisis correspondiente.
