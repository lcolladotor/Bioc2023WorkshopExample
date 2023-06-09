
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Bioc2023WorkshopExample

<!-- badges: start -->

[![GitHub
issues](https://img.shields.io/github/issues/lcolladotor/Bioc2023WorkshopExample)](https://github.com/lcolladotor/Bioc2023WorkshopExample/issues)
[![GitHub
pulls](https://img.shields.io/github/issues-pr/lcolladotor/Bioc2023WorkshopExample)](https://github.com/lcolladotor/Bioc2023WorkshopExample/pulls)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![Bioc release
status](http://www.bioconductor.org/shields/build/release/bioc/Bioc2023WorkshopExample.svg)](https://bioconductor.org/checkResults/release/bioc-LATEST/Bioc2023WorkshopExample)
[![Bioc devel
status](http://www.bioconductor.org/shields/build/devel/bioc/Bioc2023WorkshopExample.svg)](https://bioconductor.org/checkResults/devel/bioc-LATEST/Bioc2023WorkshopExample)
[![Bioc downloads
rank](https://bioconductor.org/shields/downloads/release/Bioc2023WorkshopExample.svg)](http://bioconductor.org/packages/stats/bioc/Bioc2023WorkshopExample/)
[![Bioc
support](https://bioconductor.org/shields/posts/Bioc2023WorkshopExample.svg)](https://support.bioconductor.org/tag/Bioc2023WorkshopExample)
[![Bioc
history](https://bioconductor.org/shields/years-in-bioc/Bioc2023WorkshopExample.svg)](https://bioconductor.org/packages/release/bioc/html/Bioc2023WorkshopExample.html#since)
[![Bioc last
commit](https://bioconductor.org/shields/lastcommit/devel/bioc/Bioc2023WorkshopExample.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/Bioc2023WorkshopExample/)
[![Bioc
dependencies](https://bioconductor.org/shields/dependencies/release/Bioc2023WorkshopExample.svg)](https://bioconductor.org/packages/release/bioc/html/Bioc2023WorkshopExample.html#since)
[![R-CMD-check-bioc](https://github.com/lcolladotor/Bioc2023WorkshopExample/actions/workflows/R-CMD-check-bioc.yaml/badge.svg)](https://github.com/lcolladotor/Bioc2023WorkshopExample/actions/workflows/R-CMD-check-bioc.yaml)
[![Codecov test
coverage](https://codecov.io/gh/lcolladotor/Bioc2023WorkshopExample/branch/devel/graph/badge.svg)](https://app.codecov.io/gh/lcolladotor/Bioc2023WorkshopExample?branch=devel)
<!-- badges: end -->

The goal of `Bioc2023WorkshopExample` is to …

## Installation instructions

Get the latest stable `R` release from
[CRAN](http://cran.r-project.org/). Then install
`Bioc2023WorkshopExample` from [Bioconductor](http://bioconductor.org/)
using the following code:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE)) {
    install.packages("BiocManager")
}

BiocManager::install("Bioc2023WorkshopExample")
```

And the development version from
[GitHub](https://github.com/lcolladotor/Bioc2023WorkshopExample) with:

``` r
BiocManager::install("lcolladotor/Bioc2023WorkshopExample")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library("Bioc2023WorkshopExample")
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub!

## Citation

Below is the citation output from using
`citation('Bioc2023WorkshopExample')` in R. Please run this yourself to
check for any updates on how to cite **Bioc2023WorkshopExample**.

``` r
print(citation("Bioc2023WorkshopExample"), bibtex = TRUE)
#> To cite package 'Bioc2023WorkshopExample' in publications use:
#> 
#>   lcolladotor (2023). _This is an example package_.
#>   doi:10.18129/B9.bioc.Bioc2023WorkshopExample
#>   <https://doi.org/10.18129/B9.bioc.Bioc2023WorkshopExample>,
#>   https://github.com/lcolladotor/Bioc2023WorkshopExample/Bioc2023WorkshopExample
#>   - R package version 0.99.0,
#>   <http://www.bioconductor.org/packages/Bioc2023WorkshopExample>.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {This is an example package},
#>     author = {{lcolladotor}},
#>     year = {2023},
#>     url = {http://www.bioconductor.org/packages/Bioc2023WorkshopExample},
#>     note = {https://github.com/lcolladotor/Bioc2023WorkshopExample/Bioc2023WorkshopExample - R package version 0.99.0},
#>     doi = {10.18129/B9.bioc.Bioc2023WorkshopExample},
#>   }
```

Please note that the `Bioc2023WorkshopExample` was only made possible
thanks to many other R and bioinformatics software authors, which are
cited either in the vignettes and/or the paper(s) describing this
package.

## Code of Conduct

Please note that the `Bioc2023WorkshopExample` project is released with
a [Contributor Code of
Conduct](http://bioconductor.org/about/code-of-conduct/). By
contributing to this project, you agree to abide by its terms.

## Development tools

- Continuous code testing is possible thanks to [GitHub
  actions](https://www.tidyverse.org/blog/2020/04/usethis-1-6-0/)
  through *[usethis](https://CRAN.R-project.org/package=usethis)*,
  *[remotes](https://CRAN.R-project.org/package=remotes)*, and
  *[rcmdcheck](https://CRAN.R-project.org/package=rcmdcheck)* customized
  to use [Bioconductor’s docker
  containers](https://www.bioconductor.org/help/docker/) and
  *[BiocCheck](https://bioconductor.org/packages/3.17/BiocCheck)*.
- Code coverage assessment is possible thanks to
  [codecov](https://codecov.io/gh) and
  *[covr](https://CRAN.R-project.org/package=covr)*.
- The [documentation
  website](http://lcolladotor.github.io/Bioc2023WorkshopExample) is
  automatically updated thanks to
  *[pkgdown](https://CRAN.R-project.org/package=pkgdown)*.
- The code is styled automatically thanks to
  *[styler](https://CRAN.R-project.org/package=styler)*.
- The documentation is formatted thanks to
  *[devtools](https://CRAN.R-project.org/package=devtools)* and
  *[roxygen2](https://CRAN.R-project.org/package=roxygen2)*.

For more details, check the `dev` directory.

This package was developed using
*[biocthis](https://bioconductor.org/packages/3.17/biocthis)*.
