
<!-- README.md is generated from README.Rmd. Please edit that file -->

# infocausality

<!-- badges: start -->

[![CRAN](https://www.r-pkg.org/badges/version/infocausality)](https://CRAN.R-project.org/package=infocausality)
[![CRAN
Release](https://www.r-pkg.org/badges/last-release/infocausality)](https://CRAN.R-project.org/package=infocausality)
<!-- [![CRAN Checks](https://badges.cranchecks.info/worst/infocausality.svg)](https://cran.r-project.org/web/checks/check_results_infocausality.html) -->
<!-- [![Downloads_all](https://badgen.net/cran/dt/infocausality?color=orange)](https://CRAN.R-project.org/package=infocausality) -->
<!-- [![Downloads_month](https://cranlogs.r-pkg.org/badges/infocausality)](https://CRAN.R-project.org/package=infocausality) -->
[![License](https://img.shields.io/badge/license-GPL--3-brightgreen.svg?style=flat)](http://www.gnu.org/licenses/gpl-3.0.html)
[![Lifecycle:
experimental](https://lifecycle.r-lib.org/articles/figures/lifecycle-experimental.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![R-CMD-check](https://github.com/stscl/infocausality/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/stscl/infocausality/actions/workflows/R-CMD-check.yaml)
[![R-universe](https://stscl.r-universe.dev/badges/infocausality?color=cyan)](https://stscl.r-universe.dev/infocausality)

<!-- badges: end -->

<a href="https://stscl.github.io/infocausality/"><img src="man/figures/infocausality.png" align="right" hspace="10" vspace="0" width="15%" alt="infocausality website: https://stscl.github.io/infocausality/"/></a>

*Information-Theoretic Measure of Causality*

`infocausality` is an R package for information-theoretic causal
analysis.  
It quantifies temporal and spatial causality through information flow,
and decomposes it into unique, redundant, and synergistic components.
The package provides native support for `data.frame`, `sf`, and
`SpatRaster` objects, offering a unified interface for both time-series
and spatial cross-sectional causal analysis.

> *Refer to the package documentation
> <https://stscl.github.io/infocausality/> for more detailed
> information.*

## Installation

- Install from [CRAN](https://CRAN.R-project.org/package=infocausality)
  with:

``` r
install.packages("infocausality", dep = TRUE)
```

- Install binary version from
  [R-universe](https://stscl.r-universe.dev/infocausality) with:

``` r
install.packages("infocausality",
                 repos = c("https://stscl.r-universe.dev",
                           "https://cloud.r-project.org"),
                 dep = TRUE)
```

- Install from source code on
  [GitHub](https://github.com/stscl/infocausality) with:

``` r
if (!requireNamespace("devtools")) {
    install.packages("devtools")
}
devtools::install_github("stscl/infocausality",
                         build_vignettes = TRUE,
                         dep = TRUE)
```
