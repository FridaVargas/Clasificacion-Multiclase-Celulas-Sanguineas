# 🩸Clasificación automática de células sanguíneas a partir de imágenes
<p align="center">
<img width="1009" height="514" alt="imagen" src="https://github.com/user-attachments/assets/314a0019-8b53-4698-8af9-63ce99335ba0" />
</p>
  
> Diferentes tipos de células sanguíneas, presentes en el _dataset_ de las imágenes que se desean clasificar.

**Autora:** Frida Michelle Vargas Bautista  
**Curso:** Introducción a la Ciencia de Datos Aplicada a Escenarios Médico-Biológicos  
**Facultad de Ciencias, UNAM — Semestre 2026-1**

## 🩸Descripción

<p align="center">
  <img src="https://github.com/user-attachments/assets/bff43201-f3b3-4aa6-b1de-a2c3cba0289a" width="45%">
  <img src="https://github.com/user-attachments/assets/c28491f1-fc26-431b-8e56-beb1b7b8b16a" width="45%">
</p>

> Matrices de confusión de predicciones realizadas por una máquina de soporte vectorial con kernel SBF y la otra por una red neuronal convolucional.

Este proyecto explora la **clasificación automática de células sanguíneas** a partir de imágenes microscópicas, comparando dos enfoques:

- Modelos clásicos entrenados sobre **atributos texturales GLCM**
- Un enfoque de **aprendizaje profundo** mediante una **Red Neuronal Convolucional (CNN)**

El objetivo es analizar **qué tan informativo es cada enfoque* y cuáles son sus ventajas y limitaciones en un contexto médico-biológico.

## 🩸Dataset

Se utiliza un dataset público de Kaggle con **17,092 imágenes** de células sanguíneas, etiquetadas por hematólogos clínicos expertos.  
Las imágenes fueron adquiridas con el analizador **CellaVision DM96**.

> El dataset no se incluye directamente en este repositorio pero puede ser consultado [aquí](https://www.kaggle.com/datasets/unclesamulus/blood-cells-image-dataset/data)

## 🩸Metodología (resumen)

- Extracción de atributos GLCM (contraste, disimilaridad, homogeneidad, energía, correlación)
- Modelos clásicos: Regresión logística, Random Forest, Gradient Boosting, XGBoost y SVM
- CNN entrenada directamente sobre imágenes (128×128) con data augmentation
- Evaluación con métricas de clasificación multiclase (F1-score, precisión y recall)

## 🩸Reproducibilidad
La forma más facíl y la recomendada es descargar una copia en _Google Colab_ del notebook disponible [aquí](https://github.com/FridaVargas/Clasificacion-Multiclase-Celulas-Sanguineas/blob/main/ClasificacionCelulasSanguineas.ipynb).
De esta forma se utiliza directamente la API de _kaggle_  y se descarga de manera más fácil las paqueterías más python.


## Agradecimientos

Este proyecto fue desarrollado con la **asesoría y orientación del profesor David Alexis García Espinosa**,  
cuyas sugerencias, observaciones y explicaciones fueron clave.


> Este trabajo tiene un **enfoque académico y exploratorio** y no pretende ser una herramienta diagnóstica.

