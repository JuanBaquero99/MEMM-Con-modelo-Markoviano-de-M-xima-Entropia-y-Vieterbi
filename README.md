# Algoritmo de Viterbi para Secuenciación

Este proyecto implementa el algoritmo de Viterbi para secuenciación usando un modelo de clasificación y codificación one-hot. El algoritmo de Viterbi es utilizado para encontrar la secuencia de estados más probable en una serie de observaciones, basado en un modelo probabilístico.

## Descripción

El algoritmo de Viterbi es un algoritmo dinámico utilizado en el procesamiento de señales y en modelos de cadenas de Markov ocultas (HMMs) para encontrar la secuencia de estados más probable. Este código implementa el algoritmo de Viterbi en Python utilizando un modelo de clasificación que predice las probabilidades de transición entre estados.

### Componentes del Código

- **`viterbi(observaciones, modelo, onehot_encoder, etiqueta_dict)`**: Función que implementa el algoritmo de Viterbi. Utiliza un modelo de clasificación para predecir probabilidades de transición entre estados y devuelve la secuencia de etiquetas más probable para una serie de observaciones.

### Parámetros de Entrada

- **`observaciones`**: Lista de observaciones (secuencias de entrada) que se desean etiquetar.
- **`modelo`**: Modelo de clasificación que se usa para predecir probabilidades de transición entre estados.
- **`onehot_encoder`**: Codificador one-hot que transforma las observaciones en vectores one-hot.
- **`etiqueta_dict`**: Diccionario que mapea índices numéricos a etiquetas originales.

### Salida

- **Secuencia más probable de etiquetas**: Lista de etiquetas correspondientes a la secuencia de observaciones dada.

## Instalación

Este proyecto requiere `numpy` y `scikit-learn`. Puedes instalarlos utilizando pip:

```bash
pip install numpy scikit-learn

