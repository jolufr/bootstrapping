# ⛽ Optimización en la Explotación Petrolera

## 🔍 Introducción
Desarrollar un modelo predictivo para validar los datos recogidos de distintos pozos y proyectar la cantidad de barriles de crudo que ofrece cada uno.  

## 🎯 Objetivo
Identificar las regiones con mayor rentabilidad para la explotación petrolera, minimizando riesgos y maximizando beneficios.  

## 🛠️ Tecnologías Utilizadas
- **Procesamiento de Datos**: pandas, numpy  
- **Modelado Predictivo**:  
  - Preprocesamiento: StandardScaler  
  - Modelo utilizado: Regresión Lineal (LinearRegression)  
  - Validación: Bootstrapping con 1000 iteraciones  
  - Evaluación: Mean Squared Error (MSE) y R² Score  
- **Visualización**: matplotlib  

## 📈 Pasos Clave (Metodología)
### 1️⃣ Limpieza y Análisis de Datos
- Validación de valores y eliminación de datos inconsistentes.  
- Exploración inicial para entender la distribución de los datos.  

### 2️⃣ Modelado Predictivo
- División de datos en entrenamiento y prueba.  
- Aplicación de regresión lineal para estimar la producción de barriles.  
- Evaluación del modelo con métricas de error y precisión.  

### 3️⃣ Análisis de Riesgo y Beneficio
- Simulación de 1000 escenarios con bootstrapping.  
- Cálculo del promedio de beneficio esperado.  
- Estimación del intervalo de confianza y nivel de riesgo de inversión.  

## 📊 Resultados
Este análisis permite:  
- Proyectar la producción de barriles de crudo por pozo.  
- Identificar las regiones con mayor potencial para explotación.  
- Reducir los riesgos asociados a la inversión petrolera.  

## 🚀 Cómo Ejecutarlo
```bash
Clonar este repositorio.
