## Trabajo de Análisis de Datos con Modelos de Clasificación Binaria

### Enunciado del Problema

Cada grupo **(mínimo 3 personas, máximo 4 personas)** debe seleccionar una base de datos de su elección en la que el objetivo (target) sea una variable categórica binaria (es decir, con dos posibles valores, como "sí/no", "aprobado/reprobado", etc.). Considere que debe explicar la relevancia del trabajo y el contexto en el que se desarrolla. El trabajo consiste en realizar un análisis completo de la base de datos, siguiendo los siguientes puntos:

1. **Limpieza de Datos**
   - Identificación y tratamiento de valores faltantes.
   - Identificación y tratamiento de valores atípicos.
   - Codificación de variables categóricas (si aplica).
   - Normalización o estandarización de variables numéricas (si aplica).

2. **Análisis Descriptivo**
   - Descripción general de la base de datos.
   - Análisis univariado y bivariado de las variables.
   - Visualización de las distribuciones de las variables más relevantes.

3. **Preparación de los Datos para el Modelo**
   - División del conjunto de datos en conjunto de entrenamiento y conjunto de prueba.
   - Imputación de valores faltantes (si aplica).
   - Selección y transformación de características (feature selection y feature engineering).

4. **Modelado**
   - Implementación de modelos de regresión logística, árboles de decisión y random forest.
   - Evaluación de cada modelo utilizando validación cruzada.
   - Optimización de hiperparámetros utilizando GridSearchCV.

5. **Evaluación de Modelos**
   - Comparación de los modelos utilizando las siguientes métricas:
     - Matriz de confusión.
     - Precisión (Precision).
     - Recall.
     - AUC-ROC.
   - Selección del mejor modelo basado en las métricas anteriores.

6. **Presentación**
   - Cada grupo debe preparar una presentación síncrona de 20 minutos.
   - La presentación debe cubrir todos los puntos mencionados anteriormente.
   - Al final de la presentación, se realizará una sesión de preguntas enfocadas en el desarrollo del problema, las librerías utilizadas, las métricas de error etc.

### Rúbrica de Evaluación (100 puntos)

| **Criterio**                            | **Puntos** |
|-----------------------------------------|------------|
| **Limpieza de Datos**                   |            |
| - Identificación y tratamiento de valores faltantes | 5          |
| - Identificación y tratamiento de valores atípicos  | 5          |
| - Codificación de variables categóricas (si aplica) | 5          |
| - Normalización/estandarización (si aplica)         | 5          |
| **Análisis Descriptivo**                |            |
| - Descripción general de la base de datos           | 5          |
| - Análisis univariado y bivariado                   | 5          |
| - Visualización de distribuciones                   | 5          |
| **Preparación de los Datos**            |            |
| - División en conjunto de entrenamiento y prueba    | 5          |
| - Imputación de valores faltantes (si aplica)       | 5          |
| - Selección y transformación de características     | 5          |
| **Modelado**                            |            |
| - Implementación de regresión logística             | 5          |
| - Implementación de árboles de decisión             | 5          |
| - Implementación de random forest                  | 5          |
| - Validación cruzada                              | 5          |
| - Optimización de hiperparámetros                  | 5          |
| **Evaluación de Modelos**                |            |
| - Comparación de modelos con métricas              | 10         |
| - Matriz de confusión                              | 5          |
| - Precisión (Precision)                            | 5          |
| - Recall                                          | 5          |
| - AUC-ROC                                         | 5          |
| **Presentación**                        |            |
| - Claridad y organización de la presentación       | 10         |
| - Conocimiento del desarrollo del problema         | 10         |
| - Respuestas a las preguntas                       | 10         |

### Total: 100 puntos

### Consideraciones

- El uso de librerías como `pandas`, `numpy`, `scikit-learn`, y `matplotlib`/`seaborn` es altamente recomendado.
- La presentación debe incluir visualizaciones claras y relevantes para cada sección.
- Los grupos deben asegurarse de que cada miembro participe activamente en la presentación y en la sesión de preguntas.
- La fecha de presentación la puede decidir desde el momento de recibir esta evaluación, con coordinación del profesor (sin pasar la fecha límite de cierre del semestre).

Buena suerte y éxito en su análisis de datos.
