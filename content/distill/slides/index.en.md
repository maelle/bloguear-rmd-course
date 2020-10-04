---
outputs:
- Reveal
title: distill
hidden: true
layout: list
weight: 1
output: hugodown::md_document
countdown: true
rmd_hash: 9e15832d60cc9db2

---

Distill
=======

------------------------------------------------------------------------

[Distill](rstudio.github.io/distill/) es una plantilla de sitio (HTML, CSS, JSS) y también un paquete R que permite utilizar esta plantilla.

> Distill para R Markdown es un formato para publicar en el web, optimizado para comunicación tecnica y cientifica.

------------------------------------------------------------------------

-   Formato de output para documentos R Markdown

-   Sitios web

-   Blogs, como sitios web però con articulos de blog que no estan tejidos cada vez que el sitio esta construido.

------------------------------------------------------------------------

Funciones cómo [`distill::create_post()`](https://rdrr.io/pkg/distill/man/create_post.html)

------------------------------------------------------------------------

Desde Rmd hasta un sitio
========================

Entre bastidores

{{<mermaid align="left">}}
graph LR;
    A[Rmd] -->|"R ( distill :package:) & Pandoc & Distill framework" | B[HTML]
{{< /mermaid >}}

<small>Inspirado por [Emi Tanaka's post](https://emitanaka.org/r/posts/2018-12-12-scientific-and-technical-blogging-radix-vs-blogdown/)</small>

------------------------------------------------------------------------

Desde Rmd hasta un sitio
========================

Lo que hacen Ustedes

{{<mermaid align="left">}}
graph LR;
    A[Rmd] -->|" :large_blue_circle: knit button" | B[HTML]
{{< /mermaid >}}

------------------------------------------------------------------------

:train: ¡Ahora lo probamos!

[Notas en el sitio del curso](/distill/demo/)

------------------------------------------------------------------------

Viabilidad
==========

Creado por:

<div class="highlight">

JJ Allaire \[aut, cre\], Rich Iannone \[aut\], Yihui Xie \[aut\]

</div>

y también Alison Presmanes Hill.

Usado para [RStudio AI blog](https://blogs.rstudio.com/ai/).

Desarrollo activo.

------------------------------------------------------------------------

Limitaciones?
=============

-   Contenido en HTML (no sé cómo uno podria cambiar de generador de sitios sin tejer de nuevo)

-   No se puede personalizar muchisimo però tal vez es mejor asi :grin:

-   Lo qué no habia la primera vez que di el curso en julio, ahora lo hay! :tada:

------------------------------------------------------------------------

Más recursos
============

[Lista en el sitio del curso](/distill/further-resources/) :books:

------------------------------------------------------------------------

Preguntas, comentarios?
=======================

Chat de Zoom, issues en el repositorio del sitio del curso.

------------------------------------------------------------------------

¡Descanso! :coffee:
===================

<!--html_preserve-->

<div id="timer_5ee3a3da" class="countdown" style="top:100;left:0;" data-warnwhen="0">

<code class="countdown-time"><span class="countdown-digits minutes">05</span><span class="countdown-digits colon">:</span><span class="countdown-digits seconds">00</span></code>

</div>

<!--/html_preserve-->

