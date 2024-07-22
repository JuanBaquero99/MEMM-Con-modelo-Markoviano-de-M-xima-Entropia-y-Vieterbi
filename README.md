# Modelo Markoviano de Máxima Entropía con Viterbi e Interfaz Web

Este repositorio contiene la implementación de un Modelo Markoviano de Máxima Entropía (MEMM) con el algoritmo de Viterbi, expuesto a través de una API Flask. Además, incluye una interfaz web simple para interactuar con el modelo, permitiendo ingresar secuencias de observaciones y obtener la secuencia más probable de etiquetas.

## Características

- **Modelo MEMM**: Implementación de un modelo Markoviano de Máxima Entropía utilizando `scikit-learn`.
- **Algoritmo de Viterbi**: Algoritmo de Viterbi para encontrar la secuencia más probable de etiquetas.
- **API Flask**: API construida con Flask para exponer el modelo y permitir interacciones mediante solicitudes HTTP.
- **Interfaz Web**: Página HTML simple que interactúa con la API para recibir entradas del usuario y mostrar resultados.

## Contenidos del Repositorio

- `app.py`: Script de Python que contiene la implementación del modelo MEMM, el algoritmo de Viterbi y la API Flask.
- `index.html`: Archivo HTML que proporciona una interfaz de usuario simple para interactuar con la API.
- `README.md`: Documentación del proyecto (este archivo).

## Requisitos

- Python 3.x
- Flask
- scikit-learn
- numpy
- flask-ngrok (para pruebas en Google Colab)
