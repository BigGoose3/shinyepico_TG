
<!-- README.md is generated from README.Rmd. Please edit that file -->
ShinyÉPICo
==========

<!-- badges: start -->
[![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental) <!-- badges: end -->

ShinyÉPICO is a web interface based on Shiny that makes it easy to do differentially methylated CpGs analysis from Illumina EPIC methylation arrays. This program allows following a standard pipeline of normalization (with minfi package), model creation and statistical analysis (with limma package), with different options in each step and plots to be able to choose properly. Moreover, you can select different options in the final heatmap and download an RMarkdown report with all the steps chosen.

Installation
------------

Nowadays, you have to download the source package from the github repository and install the package manually.

``` r
install.packages("shinyepico")
```
