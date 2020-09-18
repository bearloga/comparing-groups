Simulation study of statistical methods for comparing groups
================

Examples and informal evaluations of various statistical significance
tests for comparing observations generated from different distributions
and families.

| status           | content                                                     | code           |
|:-----------------|:------------------------------------------------------------|:---------------|
| work in progress | [CC BY-SA](https://creativecommons.org/licenses/by-sa/4.0/) | [MIT](LICENSE) |

Setup
-----

Installing dependencies in R:

    install.packages(c(
      "rmarkdown", "tidyverse", "remotes",
      "ggdist", "gt", "patchwork"
    ))
    remotes::install_github("rstudio/distill")

Knitting the R Markdown source document to an HTML page, which requires
a local copy of [Wikipedia Context
Cards](https://github.com/joakin/context-cards):

    # wget https://unpkg.com/context-cards/dist/context-cards.js
    R -e "rmarkdown::render('index.Rmd')"
