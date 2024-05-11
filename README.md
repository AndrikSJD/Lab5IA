# Laboratorio Número 5 - Inteligencia Artificial

Este repositorio contiene el trabajo realizado para el Laboratorio Número 5 del curso de Inteligencia Artificial en el Tecnológico de Costa Rica.

## Autores

Este laboratorio fue realizado por:

- Andrik Solano
- Ronald Arce

## Descripción

Este proyecto tiene como objetivo realizar una clasificación de un rostro humano para determinar si tiene o no una mascarilla. Para ello, se requiere un conjunto de datos (dataset) con imágenes de rostros que tengan o no tengan mascarilla para su entrenamiento.

El modelo utilizado para este proyecto es una red neuronal convolucional (Convolutional Neural Network, CNN) implementada con TensorFlow. Este tipo de modelo es especialmente eficaz para tareas de clasificación de imágenes, como la detección de mascarillas en rostros humanos. Las CNN son capaces de aprender automáticamente y generalizar características de las imágenes, lo que las hace muy adecuadas para este tipo de tareas.

El modelo consta de varias capas convolucionales y de agrupación máxima (MaxPooling) para extraer características de las imágenes. Luego, estas características se aplanan y se pasan a través de una capa densa con activación ReLU. Se aplica un Dropout del 50% para ayudar a prevenir el sobreajuste. 

## Requisitos

Para este proyecto necesitarás:

- Python 10
- Anaconda
- Jupyter Notebook
- TensorFlow

Puedes seguir los siguientes videos para instalar Anaconda, Jupyter Notebook y TensorFlow.

https://www.youtube.com/watch?v=QUjtDIalh0k 

https://www.youtube.com/watch?v=BXsgHC8qTac

## Instrucciones de Uso

1. Clona este repositorio.
2. Instala las dependencias necesarias.
3. Crea una carpeta llamada `data` en la raíz del proyecto.
4. Coloca tus datos en la carpeta `data`.
5. Ejecuta el código.
