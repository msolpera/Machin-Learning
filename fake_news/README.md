# Detector de Fake News 

Este repositorio contiene un sistema completo para la detección de noticias falsas (fake news) utilizando técnicas de procesamiento de lenguaje natural (NLP) y algoritmos de machine learning.

## Conjunto de Datos

El proyecto utiliza dos conjuntos de datos:
- `Fake.csv`: Contiene noticias etiquetadas como falsas
- `True.csv`: Contiene noticias etiquetadas como verdaderas

  Cada conjunto incluye los siguientes campos:
- `title`: Título de la noticia
- `text`: Contenido de la noticia
- `subject`: Tema de la noticia
- `date`: Fecha de publicación

##  Tecnologías Utilizadas

- **Lenguaje de Programación**: Python 3.9
- **Bibliotecas Principales**:
  - pandas & numpy: Manipulación de datos
  - scikit-learn: Algoritmos de machine learning y evaluación
  - NLTK & spaCy: Procesamiento de lenguaje natural
  - TensorFlow/Keras: Modelos neuronales (preparados en el código)
  - matplotlib & seaborn: Visualización de datos
  - joblib: Serialización de modelos
 
## Resultados

El sistema evalúa diferentes modelos de machine learning:
- Passive Aggressive Classifier
- Linear SVC
- Logistic Regression
- Multinomial Naive Bayes
- Gradient Boosting Classifier

Los resultados detallados de la evaluación, incluyendo la matriz de confusión y las métricas de rendimiento, se generan en el directorio `output_fakenews/reports/`.
