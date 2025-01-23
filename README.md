# Optimización en la Explotación Petrolera

En este proyecto se desarrolló un modelo predictivo con el propósito de validar los datos recogidos de distintos pozos y proyectar la cantidad de barriles de crudo que ofrece cada uno. Asimismo, se busca determinar cuál de las regiones estudiadas representa el mejor escenario para llevar a cabo la explotación petrolera.

El proceso incluye la limpieza y análisis de los datos para garantizar la validez de los valores y la precisión de los resultados obtenidos. El modelo predictivo fue entrenado utilizando el algoritmo **LinearRegression**, y para evaluar el promedio del beneficio, el intervalo de confianza y el nivel de riesgo de la inversión, se realizaron 1000 pruebas mediante el método de **bootstrapping**.

Los resultados entregados en este proyecto permitirán minimizar los riesgos asociados a la inversión al momento de ejecutar la explotación de petróleo en los 200 pozos seleccionados.

## Librerías Usadas

### Procesamiento de Datos
- `pandas`
- `numpy`

### Modelado Predictivo
- `sklearn.preprocessing.StandardScaler`
- `sklearn.linear_model.LinearRegression`
- `sklearn.model_selection.train_test_split`
- `sklearn.metrics.mean_squared_error`
- `sklearn.metrics.r2_score`

### Visualización
- `matplotlib.pyplot`

---

## Cómo Ejecutar el Proyecto

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/usuario/proyecto-oilygiant.git
   cd proyecto-oilygiant
