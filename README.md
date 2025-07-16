# Examen_de_Certificacion---Intento-2

Este proyecto utiliza el Bank Marketing Dataset para realizar un análisis de datos y construir modelos de clasificación que predicen si un cliente suscribirá un depósito a plazo. 

Se utilizan dos data sets, la versión full se aplicará a modelo de árboles de decisión suelen ser eficientes para manejar datasets de tamaño moderado a grande, además usar el dataset completo (más datos) ayuda al árbol a aprender patrones más robustos y precisos. Para el otro modelo (Support Vector Machine (SVM)) la versión reducida ya que entrenar un SVM con esta muestra es mucho más factible en hablando de tiempo y recursos.

## 1. Carga y Limpieza de Datos
   - Se cargaron los datasets 
   - Se eliminaron duplicados y se trataron outliers 
## 2. Exploración de Datos (EDA)
   - Se realizaron análisis estadísticos y visualizaciones (histogramas, boxplots, mapas de calor, scatterplots) para entender la distribución y relaciones entre variables.
   - Se identificaron correlaciones relevantes.
- 
## 3. Modelado
   - Se probaron dos modelos de clasificación.
   - 
## 4. Evaluación
   - Se evaluó el desempeño de los modelos usando accuracy y matrices de confusión.
   - 
| Métrica                     |       DecisionTreeClassifier            | SVC        |
| --------------------------- | ------------------------------------- | -------------------- |
| accuracy                | 0.9006                                  | 0.9014                 |
| precision no   | 0.92 | 0.92 |
| precision yes | 0.65                                    |       0.59               |


## 5. Exportación de Modelos
   - El modelo seleccionada se exporta en formato `.pkl` para su uso futuro.

## Conclusión Final y Comparación de Rendimiento:

Amos modelos presentaron un excelente rendimiento y aunque el accuracy o rendimiento general del es levemente superior en el modelo SVC, cuando se trata de predecir el valor "yes" de la variable objetivo posee un comportamiento un tanto inferior al modelo de clasifiación Decision Tree, por lo que este ultimo es el mejor modelo para este problema.

Autor del codigo: Sofia Osorio Urrutia