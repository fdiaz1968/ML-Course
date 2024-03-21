# Business Data Science: Supervised Learning
## Summer 2024

### I. Identificación
**Instructor:** Fernando Díaz (fernando.diazh@usm.cl), Sebastian Azócar (sebastian.azocarm@usm.cl)  
**Código:** ICS 811  
**Créditos:** 5

### II. Descripción del Curso
La Ciencia de Datos es un campo interdisciplinario que combina métodos, técnicas y herramientas de estadística, matemáticas, informática y negocios para obtener conocimiento y generar información útil para la toma de decisiones. Se enfoca en el análisis de grandes volúmenes de datos para descubrir patrones, tendencias y relaciones latentes. Incluye recopilación, limpieza, procesamiento, análisis y visualización de datos. El Machine Learning es una parte fundamental de este campo, proporcionando algoritmos y modelos para extracción de conocimiento y toma de decisiones automatizadas.

### III. Bibliografía
- James G., Witten D., Hastie T., & Tibshirani R. (2020). _An Introduction to Statistical Learning, Third Edition_. Springer. (https://www.statlearning.com/)
- Deisenroth M. P., Faisal A. A., & Ong C. S. (2020). _Mathematics for Machine Learning_. Cambridge University Press.


### IV. Contenidos

#### A. Data
- **Aprendiendo de los Datos**
  - Concepto de aprendizaje automático
  - Aplicaciones, minería de datos, optimización, estadística
  - Diferentes tipos de datos, manipulación de datos

- **Lecturas**
  - Breiman L. (2001). Statistical modeling: The two cultures.
  - Burgess M. (2018). This is how Netflix's secret recommendation system works. (https://www.wired.co.uk/article/netflix-data-personalisation-watching)
  - Castañón J. (2019). Machine Learning Methods that Every Data Scientist Should Know. (https://towardsdatascience.com/10-machine-learning-methods-that-every-data-scientist-should-know-3cc96e0eeee9)
  - Pant A. (2019). Introduction to Machine Learning for Beginners. (https://towardsdatascience.com/10-machine-learning-methods-that-every-data-scientist-should-know-3cc96e0eeee9)
  - Zhang (2018). Data Types From A Machine Learning Perspective With Examples. .(https://towardsdatascience.com/data-types-from-a-machine-learning-perspective-with-examples-111ac679e8bc)

#### B. El Modelo de Regresión
- **El Modelo de Regresión desde ML**
  - Conceptos básicos, estimaciones de OLS, diferentes tipos de variables
  - Análisis exploratorio y preliminar de datos, ajuste de un modelo, interpretación de salida, predicción

- **Supuestos del Modelo**
  - Supuestos NICE (normality, independence, constant error variance, expectation of the error)
  - Diagnósticos, causalidad versus correlación, confounding factors

- **Lecturas**
  - ISLR sections 3.1-3.4 (linear regression), 7.1 (polynomial regression)
  - Lesson 3: Linear Regression (https://online.stat.psu.edu/stat508/lesson/3)
  - Bansal G. (2020). What are the four assumptions of linear regression? (https://blog.uwgb.edu/bansalg/statistics-data-analytics/linear-regression/what-are-the-four-assumptions-of-linear-regression/)
  - Vigen T. (2015). Spurious Correlations (https://www.tylervigen.com/spurious-correlations)


#### C. Selección
- **Selección de Variables**
  - Aplicaciones, técnicas y metodología, best subset selection, stepwise, backward & forward selection

- **Shrinkage Methods o Métodos de Reducción**
  - Reducción versus Selección, L1 versus L2 Regularization, LASSO Regression, RIDGE Regression, Elastic Net Regression

- **Lecturas**
  - ISLR sections 6.1 (Subset selection), 6.2 (Shrinkage methods)
  - Lesson 4: Variable Selection
  - Lesson 5: Shrinkage Methods
  - Deol G. (2019). An introduction to ridge, lasso, and elastic-net regression

#### D. Clasificación
- **Logistic Regression – Probit Regression**
  - ¿Qué es la clasificación?, técnica y metodología, medición del rendimiento del modelo, la curva ROC, TPR & FPR

- **Generative Models**
  - Conceptos básicos, The Naïve Bayesian Classifier, clasificación de texto, aplicación de NLP: medición del sentimiento de texto

- **Lecturas**
  - ISLR sections 4.1, 4.2, 4.3, 4.6.2
  - Lesson 9.1: Logistic Regression
  - Asiri S. (2018). Machine Learning Classifiers

#### E. Resampling Methods
- **Cross Validation**
  - El set de validación, LOOCV, k-FCV, CV en problemas de clasificación

