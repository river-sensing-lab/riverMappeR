
<!-- README.md is generated from README.Rmd. Please edit that file -->

# riverMapper

<!-- badges: start -->
<!-- badges: end -->

R Package designed for the automated mapping and functional analysis of river corridors and is specifically tailored to the needs of data-scarce environments and the use of globally available data. To achieve this, the package integrates the functionality for terrain analysis of GRASS and SAGA GIS with the capabilities of R to conduct statistical analysis and data visualization. This initial release includes channel network extraction the delineation of corridors/riparian zones as well as corridor segmentation and aggregation as described in [Betz et al. (2018)](https://doi.org/10.1016/j.geomorph.2018.01.024) and [Betz et al. (2020)](https://doi.org/10.3390/rs12162533). The Google Earth Engine integration will be released publically soon, so keep an eye on the Github. For the moment please contact Florian Betz (fbetz.geo@gmail.com) if you want to use it. 

## Installation

You can install the development version of riverMapper from GitHub. Due to the dependencies on GIS software, currently no CRAN submission is planned:

``` r
library(remotes)
remotes::install_github("river-sensing-lab/riverMapper")
```

