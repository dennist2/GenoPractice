
<!-- README.md is generated from README.Rmd. Please edit that file -->

# GenoPractice

<!-- badges: start -->
<!-- badges: end -->

The goal of GenoPractice is to …

## Installation

You can install the released version of GenoPractice from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("GenoPractice")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("dennist2/GenoPractice")
```

## Example

This is a basic example which shows you how to test rcpp code:

``` r
devtools::install_github("dennist2/SheepData")

library(GenoPractice)
library(SheepData)

sheep <- SheepData::sheep
GenoPractice:::rollmean(sheep$Population,3)

```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this. You could also
use GitHub Actions to re-render `README.Rmd` every time you push. An
example workflow can be found here:
<https://github.com/r-lib/actions/tree/master/examples>.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
