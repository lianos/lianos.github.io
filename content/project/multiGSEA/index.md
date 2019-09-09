---
date: "2019-08-31"
# Optional external URL for project (replaces project detail page).
external_link: ""
# add "featured.jpg" in this folder to 
# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart
# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
# slides: example
summary: An R package built to reduce the friction in running gene set analyses, with interactive views over their results.
tags:
- oss
title: multiGSEA
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

<!--
description
-->

[multiGSEA][mg] is an R package that removes some of the friction when
running gene set enrichment analyses. It provides:

1. The `multiGSEA()` funtion acts as a front end from which you can call a
   plethora of GSEA methods using a single front end.
2. A `GeneSetDb()` class which stores geneset collections in a tidy
   format, with convenience functions to retrieve MSigDB, reactome, and other
   well known gene set collections.
3. A `scoreSingleSamples` which provides a front end to get gene set scores
   per sample, using a number of common methods.

There is a sister [multiGSEA.shiny][mgshiny] package that enables users to
interactively explore GSEA results.

This is a stand-alone package for performing and analyzing gene set enrichment
analyses. You might be interested in using this functionality within
[the facileverse][fverse], via the [`FacileAnalysis::ffsea()`][ffsea] function.
This will enable you to perfrom and analyze differential expression and gene set
enrichment anlayses in an interactive and unified manner.

[mg]: https://github.com/lianos/multiGSEA
[mgshiny]: https://github.com/lianos/multiGSEA.shiny
[fverse]: https://facileverse.org
[ffsea]: https://facileverse.github.io/FacileAnalysis/reference/ffsea.html




