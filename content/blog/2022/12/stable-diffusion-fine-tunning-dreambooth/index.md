---
title: "Stable Diffusion fine-tunning usando Dreambooth"
date: 2022-12-18
# image: apple.png
tags:
  - stable-difussion
  - dreambooth
---

Dreambooth es un técnica con la cuál podemos hacer un ajuste o afinación al modelo pre-entrenado de Stable Diffusion. Coloquialmente esto también es conocido como re-entrenar el modelo.

Básicamente se trata de darle un número "pequeño" de fotos de una persona, cosa, estilo, etc. También hay que indicar que es la foto y cual es su identificador. Con esta información se meten estos nuevos conceptos tanto como al text-encoder como la UNET, ambos partes de Stable Diffusion.

Usando un par de Google Colab notebooks disponibles en github puedes crear un modelo de Stable Diffusion que sabe como dibujar tu cara, cuerpo, tu estilo de pintura o cine.

Después de algunos intentos e invertir $208 MXN en Compute Engines para Google Colab (la memoria del GPU no era suficiente en la versión gratuita) pude entrenar un modelo con algunas fotos de mi cara y generar unos pocos avatares muy buenos.

* Repositorio con los notebooks y dependencias para ajustar y usar tus propios modelos de stable diffusion: https://github.com/TheLastBen/fast-stable-diffusion

* [Notebook para ajustar el modelo usando Dreambooth](https://colab.research.google.com/github/TheLastBen/fast-stable-diffusion/blob/main/fast-DreamBooth.ipynb)

* [Notebook para cargar modelos y usar todas las opciones de Stable Diffusion](https://colab.research.google.com/github/TheLastBen/fast-stable-diffusion/blob/main/fast_stable_diffusion_AUTOMATIC1111.ipynb)

