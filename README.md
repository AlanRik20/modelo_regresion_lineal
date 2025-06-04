
#  Modelo de Regresión Lineal con Scikit-Learn 

## Descripción del Proyecto
Este proyecto tiene como objetivo aplicar un modelo de regresión lineal para predecir la cantidad de calorías quemadas durante el ejercicio físico. Utilizamos un dataset real extraído de Kaggle que contiene datos de personas que realizaron distintas rutinas de ejercicio.

## Dataset
- Fuente: Kaggle (https://www.kaggle.com/datasets/ruchikakumbhar/calories-burnt-prediction)
- Cantidad de registros: más de 1500 filas
- Columnas utilizadas como características (features):
  - Gender (género: codificado como 0 para masculino, 1 para femenino)
  - Age (edad)
  - Height (altura en cm)
  - Weight (peso en kg)
  - Duration (duración del ejercicio en minutos)
  - Heart_Rate (frecuencia cardíaca)
  - Body_Temp (temperatura corporal)
- Variable objetivo: Calories (calorías quemadas)

## Pasos Realizados
1. **Carga y limpieza de datos**
   - Se codificó la columna "Gender" a formato numérico.
   - Se seleccionaron las columnas relevantes para el modelo.
2. **División del dataset**
   - 80% de los datos se usaron para entrenamiento.
   - 20% se usaron para pruebas.
3. **Entrenamiento del modelo**
   - Se utilizó la clase `LinearRegression` de la librería Scikit-learn.
4. **Evaluación del modelo**
   - Se calcularon las métricas de desempeño: MSE y R².
5. **Visualización**
   - Se generó un gráfico de dispersión comparando calorías reales vs. calorías predichas.

## Librerías a utilizar
- Pandas
- Scikit-learn
- Matplotlib

## Resultado Esperado
El modelo predice la cantidad de calorías quemadas en función de las variables personales y del ejercicio. El gráfico generado muestra qué tan cercanas están las predicciones a los valores reales.

