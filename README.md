
<!-- README.md is generated from README.Rmd. Please edit that file -->
lubridateExtras <img src="man/figures/logo.svg" align="right" height="120" width="139" />
=========================================================================================

Convenience functions for the lubridate package

<!-- Placeholder for build status, CRAN status, and coverage status -->
Overview
--------

Lubridate makes it easier to work with date-time data in R and provides new capabilities. LubridateExtras builds on top of lubridate to provide a number of convenience functions, primarily focused on abstracting patterns in ways that improve code readability and reduce copying and pasting code.

Installation
------------

``` r
# lubridateExtras is not currently on CRAN
# Please install the development version from GitHub:
# install.packages("devtools")
devtools::install_github("ellisvalentiner/lubridateExtras")
```

If you encounter a clear bug, please file a minimal reproducible example on [github](https://github.com/ellisvalentiner/lubridateExtras/issues).

Usage
-----

``` r
library(lubridateExtras)

days_ago(7)  # equivalent to lubridate::today() - lubridate::days(7)
#> [1] "2017-09-14"

days_hence(7)  # equivalent to lubridate::today() + lubridate::days(7)
#> [1] "2017-09-28"
```
