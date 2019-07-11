
<!-- README.md is generated from README.Rmd. Please edit that file -->

# VISCtemplates

The goal of VISCtemplates is to …

## Installation

You can install the released version of VISCtemplates from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("VISCtemplates")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
## basic example code
```

## Spell Check

When the template is generated, it creates a list of custom words that
are frequently ignored in VISC reports. This is saved in
`inst/WORDLIST`. You can check spelling of files and update `WORDLIST`
using the [`spelling` package](https://docs.ropensci.org/spelling/). The
`spelling` package only spell checks text blocks, not code chunks.

``` r
install.packages("spelling")

library(spelling)

spell_check_files("BAMA/pt_report/BAMA_pt_report.Rmd")
```
