---
title: Clasificador de Texto real
date: 2022-07-16T14:15:21.991Z
tags:
  - NLP
  - ""
---
Ya hace varias semanas un amigo me proporcionó un dataset donde una persona entra un texto y selecciona una categoría para clasificar ese texto. La idea es poder clasificar ese texto automáticamente.

Hice dos modelos: el primero un *baseline* con una capa de Embedding y una capa Fully-Connected, y otra con una capa de Embedding y una simple RNN (Recurrent Neural Network)

El modelo me dio un *accuracy* de 90% en ambos lo cual me pareció muy raro, después de analizar me di cuenta que el dataset esta desbalanceado la mayoría de los labels son de una sola categoría, mi conclusión por lo tanto es que estoy usando la métrica equivocada. 

En estos días lo voy a intentar de nuevo pero usando *micro f1 score* como métrica.