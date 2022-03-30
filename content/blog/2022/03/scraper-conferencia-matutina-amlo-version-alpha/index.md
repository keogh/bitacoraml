---
title: Scraper - Conferencia Matutina AMLO version alpha
date: 2022-03-30T15:47:26.382Z
tags:
  - scraper
  - dataset
  - ""
---
Hice un scraper para sacar las [versiones estenográficas de las conferencias matutinas y otros discursos del Presidente de México Andrés Manuel López Obrador (AMLO)](https://presidente.gob.mx/secciones/version-estenografica/). Esta es la primera versión, guarda el título and el contenido en archivos txt en carpetas ordenadas por fecha.

Traté de obtener todas las desde hoy hasta 2018 pero que no pude obtener debido a que mi scraper se basa en la fecha del link y algunos links de 2018 y principios de 2019 no tienen ese formato, también hay varias que tienen mal la fecha, fuera de esos detalles que solucionaré luego pude sacar 55 MB de texto.

Los próximos pasos son: mejorar el scraper, subir el código a github, subir el dataset a kaggle (o plataformas similares), jugar con el dataset y crear algunos modelos NLP.

Por lo pronto aquí comparto el [link a la primera versión de este dataset](https://drive.google.com/file/d/1zegsB2TONiqd3TwubeSyfXQjccK3CBbY/view?usp=sharing).