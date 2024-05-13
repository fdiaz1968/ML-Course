# Trabajo 2:  Análisis Estadístico y Bootstrapping en Python
## Objetivo
El objetivo de esta actividad es analizar una muestra de datos que representan los minutos que toma a los estudiantes completar un examen de matemáticas. Utilizarán tests de hipótesis estadísticos para investigar dos afirmaciones sobre la media y la desviación estándar de los tiempos de examen. Posteriormente, aplicarán la técnica de bootstrapping para reevaluar estas métricas y comparar los resultados.

## Datos
Se les proporcionará un conjunto de datos exam_times que incluye los tiempos, en minutos, que cada estudiante tomó para completar el examen.

### Parte 1: Test de Hipótesis Estadísticos
#### Importar bibliotecas necesarias
python
Copy code
import numpy as np
import scipy.stats as stats
#### Cargar los datos
Supongamos que los datos están en una lista de Python para simplificar.

```
exam_times = [data]  # Reemplazar [data] con los tiempos reales proporcionados
```
#### Hipótesis y Tests
##### Test para la media
Hipótesis:

$H_0$ : La media de los tiempos de examen es 60 minutos.
$H_1$ : La media de los tiempos de examen es mayor de 60 minutos.
Código para el test:
```
t_stat, p_value = stats.ttest_1samp(exam_times, 60, alternative='greater')
print("t-statistic:", t_stat)
print("p-value:", p_value)
```
##### Test para la desviación estándar
Hipótesis:

$H_0$ : La desviación estándar de los tiempos de examen es 10 minutos.
$H_1$ : La desviación estándar de los tiempos de examen es menor de 10 minutos.
Código para el test:

```
sample_std = np.std(exam_times, ddof=1)
std_stat, std_p_value = stats.ttest_1samp((exam_times - np.mean(exam_times)) / sample_std, 0, alternative='less')
print("Standard deviation test statistic:", std_stat)
print("p-value for standard deviation:", std_p_value)
```
### Parte 2: Bootstrapping
#### Función de Bootstrapping
Definan una función para realizar bootstrapping en la muestra:

```
def bootstrap(data, num_bootstrap, stat_func):
    bootstrap_samples = np.random.choice(data, size=(num_bootstrap, len(data)), replace=True)
    stat_samples = np.array([stat_func(sample) for sample in bootstrap_samples])
    return stat_samples
```
#### Calcular p-valores mediante Bootstrapping
# Media
```
bootstrap_means = bootstrap(exam_times, 10000, np.mean)
p_value_mean = np.mean(bootstrap_means > 60)
print("Bootstrap p-value for mean:", p_value_mean)
```

# Desviación estándar
```
bootstrap_stds = bootstrap(exam_times, 10000, np.std)
p_value_std = np.mean(bootstrap_stds < 10)
print("Bootstrap p-value for standard deviation:", p_value_std)
```
## Conclusión
Comparen los p-valores obtenidos a través de los métodos tradicionales y los obtenidos mediante bootstrapping. Discutan las implicaciones de los resultados en el contexto de la fiabilidad de los tests estadísticos.