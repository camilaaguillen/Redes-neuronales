# Redes-neuronales

# Clasificación y predicción de dígitos

Este proyecto entrena un modelo para reconocer dígitos del 0 al 9 usando el dataset MNIST y permite hacer predicciones en tiempo real con la cámara.

## Instrucciones

### 1. Google Colab
Primero se entrena el modelo en Google Colab.
Ahí se normalizan las imágenes (dividiendo entre 255) y se guarda el modelo como mnist_model.h5.

### 2. Jupyter Notebook
Después, en Jupyter, se cargan imágenes personalizadas (fondo blanco, letra negra) para probar el modelo y comprobar su precisión.

### 3. Predicción en tiempo real
Por último, se ejecuta real_time_prediction.py para usar la cámara y predecir los dígitos que se muestren en pantalla.  
Presiona **q** para cerrar la cámara.

