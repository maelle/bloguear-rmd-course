---
outputs:
- Reveal
title: Hugo & hugodown
hidden: true
layout: list
weight: 1
output: hugodown::md_document
countdown: true
rmd_hash: 84aa84291013414e

---

Hugo y hugodown
===============

Un generador de sitios muy fuerte, un paquete experimental muy practico.

------------------------------------------------------------------------

[Hugo](https://gohugo.io/)
==========================

Generador de sitios muy rapido y que permite hacer muchas cosas.

So se tiene que instalar un punto exe :tada:

------------------------------------------------------------------------

[hugodown](https://hugodown.r-lib.org/)
=======================================

[R :package:](https://hugodown.r-lib.org/)

-   Un formate de output de R Markdown

-   Funcionas para ayudar el flujo de trabajo (para instalar Hugo, incrustar tuits...)

Experimental però por el momento sigue siendo lo que recomano. A ver qué pasa con blogdown, puede cambiar!

------------------------------------------------------------------------

Desde Rmd hasta un sitio
========================

Entre bastidores

{{<mermaid align="left">}}
graph LR;
    A[Rmd] --> |"R ( hugodown :package:, </br> downlit :package:) </br> & Pandoc"| B{md}
    B --> |"Hugo (Goldmark, Chroma)"| C[HTML]
{{< /mermaid >}}

<small>Inspirado por [Emi Tanaka's post](https://emitanaka.org/r/posts/2018-12-12-scientific-and-technical-blogging-radix-vs-blogdown/)</small>

------------------------------------------------------------------------

Desde Rmd hasta un sitio
========================

Lo que hacen Ustedes

{{<mermaid align="left">}}
graph LR;
    A[Rmd] --> |":large_blue_circle: knit button"| B{md}
    B --> |"hugo build (locally or cloud)"| C[HTML]
{{< /mermaid >}}

------------------------------------------------------------------------

Sin resaltado de sintaxis :expressionless:

<pre><code>ggplot2::ggplot()
</code></pre>

Resaltado de sintaxis por Chroma :+1:

```r
ggplot2::ggplot()
```

Resaltado de sintaxis con downlit :smiley:

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nf'>ggplot2</span><span class='nf'>::</span><span class='nf'><a href='https://ggplot2.tidyverse.org/reference/ggplot.html'>ggplot</a></span><span class='o'>(</span><span class='o'>)</span>
</code></pre>

</div>

------------------------------------------------------------------------

{{< figure src="/images/highlight.jpg" alt="A meme to explain why downlit is great" height="550" >}}

Inspirado por [Mara Averick](https://twitter.com/dataandme/status/1255510799273132032)

------------------------------------------------------------------------

Resaltado de sintaxis en hugodown
=================================

-   downlit para R :tada:

-   Chroma para otros lenguajes (YAML, Python...) :sparkles:

------------------------------------------------------------------------

:mountain_cableway: ¡Ahora lo probamos!

[Notas en el sitio del curso](/hugo/demo/)

------------------------------------------------------------------------

Viabilidad
==========

Creado por:

<div class="highlight">

Hadley Wickham \[aut, cre\]

</div>

Usado para [tidyverse.org](https://tidyverse.org).

[Desarrollo activo](https://github.com/r-lib/hugodown/) (però quedará simple).

------------------------------------------------------------------------

Limitationes?
=============

-   hugodown es experimental. Por el momento solo hay un tema facil de utilizar (un tema genial) però a) pronto habrá un secundo b) hay documentación para utilizar hugodown con otros temas.

-   Hugo cambia mucho (però hugodown protege su sitio de este riesgo dado que clava una versión de Hugo al sitio)

------------------------------------------------------------------------

¿Y blogdown?
============

De hecho hay muchos cambios en blogdown estos dias que le darán fuerzas similares a hugodown... ¡a ver!

Cambio posible, y conceptos similares.

------------------------------------------------------------------------

Más recursos
============

[Lista en el sitio del curso](/hugo/further-resources/) :ledger:

------------------------------------------------------------------------

Preguntas, comentarios?
=======================

Chat de Zoom, issues en el repositorio del sitio del curso.

------------------------------------------------------------------------

¡Descanso! :tea:
================

<!--html_preserve-->

<div id="timer_hugo" class="countdown" style="top:100;left:0;" data-warnwhen="0">

<code class="countdown-time"><span class="countdown-digits minutes">05</span><span class="countdown-digits colon">:</span><span class="countdown-digits seconds">00</span></code>

</div>

<!--/html_preserve-->

