---
title: Super Resolution, un vistazo
date: 2022-10-17T13:49:38.485Z
tags:
  - GAN
  - super-resolution
---
El fin de semana el [Punksolid](https://twitter.com/punksolid) me alborotó mostrándome repositorios con modelos para mejorar la calidad y resolució de imágenes y videos. Eso me llevó a un agujero sin fondo y descubrí algunas cosas interesantes como que el problema es llamado *Image/Video Super Resolution*.

Descubrí que para este problema se usan *Generative Adversarial Networks* (GAN). Aquí listo algunos de los links más interesantes que encontré, definitivamente va a ser un tema que estudiaré en los próximos meses.

* [BasicSR, Repositorio de Github](https://github.com/XPixelGroup/BasicSR)
* [Real ESRGAN Github](https://github.com/xinntao/Real-ESRGAN)
* [El Paper de ESRGAN](https://arxiv.org/pdf/1809.00219.pdf)
* [Video Restoration Transformer](https://github.com/JingyunLiang/VRT), el [paper fue publicado recientemente](https://arxiv.org/pdf/2201.12288.pdf) y se mira muy prometedor, usa GANs y Transformers
* [BasicVSR++](https://ckkelvinchan.github.io/projects/BasicVSR++/)
* [Upscale Wiki](https://upscale.wiki/wiki/Main_Page), un wiki para aumentar la resolución de imágenes usando redes neurales particularmente ESRGAN
* [Una implementación de Real-ESRGAN en huggingface](https://huggingface.co/spaces/akhaliq/Real-ESRGAN/tree/main)
* [REDS dataset](https://paperswithcode.com/dataset/reds)