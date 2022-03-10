# Rhino <a href="https://appsilon.github.io/rhino/"><img src="man/figures/rhino.png" align="right" alt="Rhino logo" height="140"></a>
> _Strong bones for your [Shiny](https://shiny.rstudio.com/) apps_

<!-- badges: start -->
[![CRAN status](https://www.r-pkg.org/badges/version/rhino)](https://cran.r-project.org/package=rhino)
[![R build status](https://github.com/Appsilon/rhino/workflows/R-CMD-check/badge.svg)](https://github.com/Appsilon/rhino/actions)
[![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![License: LGPL-3.0](https://img.shields.io/badge/License-LGPL--3.0-blue.svg)](https://opensource.org/licenses/LGPL-3.0)
<!-- badges: end -->

## Installation
```r
install.packages("rhino")
```

### Installing from GitHub
To install latest development version or a specific one, run one of the following commands.
```r
# install.packages("remotes")
remotes::install_github("Appsilon/rhino")

# Installing rhino either from a specific release or a branch requires providing `ref` argument:
remotes::install_github("Appsilon/rhino", ref = "v0.5.0")
```


## Development
### Unit Tests
Unit tests can be run using `testthat::test_local()` or `devtools::test()`.

Alternatively, the package can be installed, and then tested with `testthat::test_package("rhino")`.

### Linter
Linter can be run using either `lintr::lint_package()` or `devtools::lint()`.

### `pkgdown` site
To create a `pkgdown` site locally run either `pkgdown::build_site()` or `devtools::build_site()`.
If built successfully, the website will be in `docs` directory.
