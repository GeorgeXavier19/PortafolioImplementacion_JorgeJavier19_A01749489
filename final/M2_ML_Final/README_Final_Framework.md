# Modelo KNeighborsClassifier para Clasificación de Dígitos Escritos a Mano

## Descripción del Modelo
Este repositorio contiene una implementación del modelo KNeighborsClassifier para la clasificación de dígitos escritos a mano. El modelo utiliza el conjunto de datos "digits" proporcionado por la librería Scikit-learn. El objetivo es predecir la etiqueta numérica correspondiente a imágenes de dígitos escritos a mano.

## Descripción del Dataset
El conjunto de datos utilizado en este proyecto es el "digits" dataset proporcionado por la librería Scikit-learn. Este conjunto de datos contiene imágenes en escala de grises de dígitos escritos a mano, donde cada imagen está asociada con una etiqueta numérica que representa el dígito que se muestra en la imagen. El dataset consta de 1,797 imágenes de 8x8 píxeles, abarcando dígitos del 0 al 9.

### Información del Dataset
- Nombre: digits dataset
- URL: [digits dataset en Scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html)
- Cantidad de Imágenes: 1,797
- Tamaño de las Imágenes: 8x8 píxeles
- Etiquetas: Dígitos del 0 al 9

## Uso del Código
El código en este repositorio implementa el modelo KNeighborsClassifier para entrenar y evaluar la capacidad del modelo para clasificar dígitos escritos a mano. El código carga automáticamente el conjunto de datos "digits" de Scikit-learn y realiza la separación en conjuntos de entrenamiento y prueba. Luego, se entrena el modelo y se evalúa su desempeño utilizando métricas como la precisión, el recall y el F1-score.

## Resultados y Conclusiones
El análisis del desempeño del modelo KNeighborsClassifier en el conjunto de datos "digits" revela resultados prometedores. Las métricas de evaluación, como la precisión y el F1-score, demuestran un rendimiento satisfactorio en la clasificación de dígitos escritos a mano. El análisis también incluye diagnósticos de sesgo, varianza y nivel de ajuste del modelo, lo que proporciona una comprensión completa de su adaptación y capacidad de generalización.

## Contribuciones y Mejoras Futuras
Este proyecto es un punto de partida para la implementación y evaluación de modelos de clasificación en el contexto de dígitos escritos a mano. Las mejoras futuras podrían incluir la optimización de parámetros del modelo, la exploración de diferentes algoritmos de clasificación y la visualización detallada de resultados.

## Cambios realizados a partir de la retro
- El reporte incluye el nombre del dataset utilizado
- El reporte incluye un enlace al lugar donde se puede encontrar el dataset utilizado
- El reporte incluye una descripción breve de los datos incluidos en el dataset (cantidad de registros/muestras, número de características, número de clases de salida o rango de valores de salida)
- El dataset se separa en entrenamiento, validación, y prueba
- Evalúa el modelo con un conjunto de prueba
- El conjunto de validación se utiliza para escoger el modelo final (refinamiento de hiper-parámetros)

## Autor
[Jorge Javier Sosa Briseño]





