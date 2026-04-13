## Descripción
Este proyecto aplica técnicas de **modelos predictivos** sobre un dataset de letras del alfabeto inglés.  
El objetivo es explorar métodos de clasificación binaria y multiclase, evaluar su desempeño y analizar cómo la selección de atributos y la validación cruzada impactan en los resultados.

## Contenido
- **Dataset**: `TP02-EnglishTypeAlphabet.csv` con 26 letras (a–z), cada una con 1016 variantes en formato de matriz 28x28.  
- **Exploración inicial**: análisis de cantidad de variantes por letra y visualización de ejemplos en grillas.  
- **Clasificación binaria**: comparación entre letras específicas (ej. O vs L), selección de atributos relevantes mediante mapas de calor y evaluación con KNN.  
- **Clasificación multiclase**: entrenamiento de modelos para las 26 letras utilizando árboles de decisión y KNN.  
- **Validación cruzada**: uso de K-folding con 5 folds para comparar hiperparámetros de árboles de decisión (profundidad, cantidad de atributos, criterio de impureza).  

## Resultados principales
- Visualización de ejemplos de letras y sus variantes.  
- El modelo KNN mostró mejoras al aumentar la cantidad de atributos relevantes.
- Impacto de la selección de atributos en la precisión. 
- La validación cruzada permitió seleccionar hiperparámetros óptimos y evitar overfitting  

## Autoría
Trabajo realizado en conjunto con otros dos compañeros de la carrera de Ciencias de la Computación (UBA).
