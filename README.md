# Dog-Breed-Classifier
Red neuronal recurrente LSTM para discriminar noticias falsa a partir de la composición y estructura de su texto.

## Dogs dataset 
https://www.kaggle.com/datasets/gpiosenka/70-dog-breedsimage-data-set/data
*-Licenced : CC0: Public Domain*

## Resumen del proyecto
El objetivo de este proyecto es construir una red neuronal convolucional para la clasificación de razas de perros.

Por motivos de almacenamiento disponible en GitHub reduje la base de datos a solamente 3 razas de perros 
(Las 3 razas más con mayor número de imágenes disponibles en el dataset):
- Labrador
- Shih-Tzu
- Lhasa


La base de datos descargada de Kaggle cuenta con 2 archivos separados:
- dogs.csv
- 3 carpetas con imágenes ya clasificadas de validación, entrenamiento y prueba.

En el archivo "DogsBreed.ipynb" se desarrolla en python:
- Tratamiento previo de los datos.
- Creación del modelo utilizando Tensorflow.
- Entrenamiento del modelo.
- Gráficas de la evolución del error y la precisión para los conjuntos de eentrenamiento y validación
- Precisión final para los datos de prueba.
- Matríz de confusión.
- Conclusiones.
