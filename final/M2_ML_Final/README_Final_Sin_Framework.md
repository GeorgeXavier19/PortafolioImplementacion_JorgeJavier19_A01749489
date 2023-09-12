# Titanic Logistic Regression

Este proyecto implementa un modelo de regresión logística para predecir la supervivencia en el Titanic utilizando el conjunto de datos del Titanic.

## Descripción del Modelo

El modelo utilizado en este proyecto es un modelo de regresión logística. Utiliza la función de hipótesis logística para realizar predicciones. El modelo se entrena utilizando un conjunto de datos que incluye características como el género (Sex) de los pasajeros para predecir si un pasajero sobrevivió (Survived) o no.

### Hiperparámetros del Modelo

- `theta`: Lista de parámetros iniciales del modelo.
- `alpha`: Tasa de aprendizaje (learning rate) utilizada para actualizar los parámetros del modelo.
- `h`: Función de hipótesis logística.
- `ite`: Número de iteraciones para el entrenamiento del modelo.

## Descripción del Dataset

El conjunto de datos utilizado en este proyecto es el conjunto de datos del Titanic. Contiene información sobre pasajeros del Titanic, incluyendo características como la edad (Age), género (Sex), tarifa (Fare), entre otros.

### Información del Dataset

- Tamaño del conjunto de datos: Número total de muestras en el conjunto de datos.
- Características utilizadas: Lista de características utilizadas en el modelo (por ejemplo, 'Sex' y 'Survived').

## Uso del Código

El código proporcionado se utiliza para entrenar un modelo de regresión logística en el conjunto de datos del Titanic. Para utilizar el código, sigue estos pasos:

1. Asegúrate de tener todas las bibliotecas requeridas instaladas, como numpy y matplotlib.
2. Ajusta los hiperparámetros del modelo, como `alpha` y `ite`, según tus necesidades.
3. Ejecuta el código para entrenar el modelo y realizar predicciones.
4. Se generará una matriz de confusión y se calcularán métricas de desempeño como la precisión, la recuperación y el puntaje F1.

## Resultados y Conclusiones

Los resultados del modelo se evalúan utilizando métricas de desempeño como la precisión, la recuperación y el puntaje F1. Estos resultados se utilizan para determinar la efectividad del modelo en la predicción de la supervivencia en el Titanic.

## Contribuciones y Mejoras Futuras

Si deseas contribuir a este proyecto o realizar mejoras futuras, considera las siguientes áreas:

- Exploración de más características del conjunto de datos para mejorar el rendimiento del modelo.
- Experimentación con diferentes algoritmos de clasificación además de la regresión logística.
- Optimización de hiperparámetros para lograr un mejor rendimiento del modelo.

## Autor

[Jorge Javier Sosa Briseño]






