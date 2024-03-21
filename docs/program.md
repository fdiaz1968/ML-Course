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
  - Lesson 2: Statistical Learning (https://online.stat.psu.edu/stat508/lesson/2)
  - ISLP 2
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
  - ISLP 3.1-3.4 (linear regression), 7.1 (polynomial regression)
  - Lesson 3: Linear Regression (https://online.stat.psu.edu/stat508/lesson/3)
  - Bansal G. (2020). What are the four assumptions of linear regression? (https://blog.uwgb.edu/bansalg/statistics-data-analytics/linear-regression/what-are-the-four-assumptions-of-linear-regression/)
  - Vigen T. (2015). Spurious Correlations (https://www.tylervigen.com/spurious-correlations)

#### C. Remuestreo
- **Cross Validation**
  - El set de validación, LOOCV, k-FCV, CV en problemas de clasificación
- **Bootstrapping**
  - Non-Parametric Bootstrapping, Bootstrapped Standard Errors, p-values
- **Lecturas**
  - ISLP 5

#### D. Selección y Regularización
- **Selección de Variables**
  - Aplicaciones, técnicas y metodología, best subset selection, stepwise, backward & forward selection

- **Shrinkage Methods o Métodos de Reducción**
  - Reducción versus Selección, L1 versus L2 Regularization, LASSO Regression, RIDGE Regression, Elastic Net Regression

- **Lecturas**
  - ISLP sections 6.1 (Subset selection), 6.2 (Shrinkage methods), 6.4 (High Dimension)
  - Lesson 4: Variable Selection (https://online.stat.psu.edu/stat508/lesson/4)
  - Lesson 5: Shrinkage Methods (https://online.stat.psu.edu/stat508/lesson/5)
  - Deol G. (2019). An introduction to ridge, lasso, and elastic-net regression (https://hackernoon.com/an-introduction-to-ridge-lasso-and-elastic-net-regression-cca60b4b934f)

#### E. Modelos No Lineales de Regresión

  - **Arboles de Decisión**
  - Arboles de Regresión, Ensamblajes, Bagging, Random Forest, Boosting

- **Lecturas**
  - ISLR Cap 8
  - Lesson 11: Tree-based Methods (https://online.stat.psu.edu/stat508/lesson/11)
  - Analytics Vidha (2016). Tree Based Algorithms: A Complete Tutorial from Scratch (in R & Python) (https://www.analyticsvidhya.com/blog/2016/04/tree-based-algorithms-complete-tutorial-scratch-in-python/)
  - Brownlee, J. (2020).  Bagging and Random Forest Ensemble Algorithms for Machine Learning (https://machinelearningmastery.com/bagging-and-random-forest-ensemble-algorithms-for-machine-learning/)


#### F. Modelos de Clasificación
- **Logistic Regression – Probit Regression**
  - ¿Qué es la clasificación?, técnica y metodología, medición del rendimiento del modelo, la curva ROC, TPR & FPR

- **Generative Models**
  - Conceptos básicos, The Naïve Bayesian Classifier

- **Modelos No Lineales**
  - Support Vector Machines, Arboles de Clasificación

- **Lecturas**
  - ISLP sections 4.1, 4.2, 4.3, 4.6.2
  - ISLP Cap 8, 9
  - Lesson 9.1: Logistic Regression (https://online.stat.psu.edu/stat508/lesson/9/9.1)
  - Lesson 10: Support Vector Machines (https://online.stat.psu.edu/stat508/lesson/10)
  - Lesson 11: Tree-based Methods (https://online.stat.psu.edu/stat508/lesson/11)
  - Asiri S. (2018). Machine Learning Classifiers (https://towardsdatascience.com/machine-learning-classifiers-a5cc4e1b0623)
  - Noble, W. S. (2006). What is a support vector machine?. Nature biotechnology, 24(12), 1565-1567.
  - Bansal, M., Goyal, A., & Choudhary, A. (2022). A comparative analysis of K-Nearest Neighbour, Genetic, Support Vector Machine, Decision Tree, and Long Short Term Memory algorithms in machine learning. Decision Analytics Journal, 100071.

#### G. Aprendizaje Profunfo
- **Redes Neuronales**
  - Artitificial Neural Networks, pereceptrón, estructura, métodos
  - Entrwenamiento de modelos, optimización

- **Lecturas**
  - ISLP Cap 10
  - LeCun, Y. & A. Canziani (2020). Deep Learning (https://atcold.github.io/pytorch-Deep-Learning/)
  - Fumo, D. (2017). A Gentle Introduction To Neural Networks Series (https://towardsdatascience.com/a-gentle-introduction-to-neural-networks-series-part-1-2b90b87795bc)

  ### V. Evaluaciones

  Se realizarán evaluaciones periódicas, idealmente después de cada módulo (ver calendario propuesto en AULA)
