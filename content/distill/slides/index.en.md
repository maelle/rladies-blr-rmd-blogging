---
outputs:
- Reveal
title: distill
hidden: true
layout: list
weight: 1
output: hugodown::md_document
countdown: true
rmd_hash: 4abbe659ffb07bd5

---

Distill
=======

------------------------------------------------------------------------

[Distill](rstudio.github.io/distill/) is both a framework and an R package.

> Distill for R Markdown is a web publishing format optimized for scientific and technical communication.

------------------------------------------------------------------------

-   Output format for single documents

-   Websites

-   Blogs, like websites but with blog posts than aren't re-rendered automatically.

------------------------------------------------------------------------

Helpers like [`distill::create_post()`](https://rdrr.io/pkg/distill/man/create_post.html)

------------------------------------------------------------------------

From Rmd to website
===================

Under the hood

{{<mermaid align="left">}}
graph LR;
    A[Rmd] -->|"R ( distill :package:) & Pandoc & Distill framework" | B[HTML]
{{< /mermaid >}}

<small>Inspired by [Emi Tanaka's post](https://emitanaka.org/r/posts/2018-12-12-scientific-and-technical-blogging-radix-vs-blogdown/)</small>

------------------------------------------------------------------------

From Rmd to website
===================

What you do

{{<mermaid align="left">}}
graph LR;
    A[Rmd] -->|" :large_blue_circle: knit button" | B[HTML]
{{< /mermaid >}}

------------------------------------------------------------------------

:train: Time for a demo!

[Notes on the course website](/distill/demo/)

------------------------------------------------------------------------

Scientific Rmd Blog Checklist

-   [x] R Markdown
-   [x] Syntax highlighting (for all knitr-supported languages)
-   [x] Modern
-   [x] .bib
-   [x] Citation for posts
-   [x] Equations

------------------------------------------------------------------------

Sustainability
==============

Created by:

<div class="highlight">

JJ Allaire ), Rich Iannone \[aut\], Alison Presmanes Hill \[aut\] (), Yihui Xie \[aut\] ()

</div>

Used for [RStudio AI blog](https://blogs.rstudio.com/ai/), in particular.

Active development.

------------------------------------------------------------------------

Limitations?
============

-   Content stored as html (harder to migrate?)

-   Limited possibilities for customization (blessing in disguise?) but awesome docs about theming!

------------------------------------------------------------------------

Further resources
=================

[Listed on the course website](/distill/further-resources/) :books:

------------------------------------------------------------------------

Questions, comments?
====================

Write them in the chat!

------------------------------------------------------------------------

Time for a break :coffee:
=========================

<!--html_preserve-->

<div id="timer_5ee3a3da" class="countdown" style="top:100;left:0;" data-warnwhen="0">

<code class="countdown-time"><span class="countdown-digits minutes">05</span><span class="countdown-digits colon">:</span><span class="countdown-digits seconds">00</span></code>

</div>

<!--/html_preserve-->

