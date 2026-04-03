## 📌 Descripción
Se analiza estadísticamente el tiempo de ejecución de la función Fibonacci y cómo cambia en función de la carga de tarea pedida.

El estudio incluye:

- Medición simple y en lote (batch) de tamaño m.

- Evaluación de cómo varían estadísticos (media, mediana) de los tiempos al aumentar n y m.

- Tests sobre las distribuciones de tiempos para comparar ambos métodos de medición.

## 🎯 Hipótesis nulas testeadas
- Las distribuciones de tiempos siguen una distribución normal.

- Para un valor fijo de n, las medias de las distribuciones de tiempos con m = 1 y m > 1 son iguales.

- La variabilidad de las distribuciones de tiempos con m = 1 y m > 1 es igual.

## 📊 Metodología
- Simulación de tiempos de ejecución con distintos parámetros.

- Análisis de resultados mediante regresión lineal simple ordinaria para estudiar la relación entre tiempo de ejecución, tamaño del lote (m) y valor de n.

## 👥 Autores
Trabajo realizado en conjunto con otros dos compañeros de la carrera de Ciencias de la Computación (UBA).