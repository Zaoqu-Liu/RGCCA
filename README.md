### Provenance

This repository is an **unmodified copy of RGCCA 2.1** (published on CRAN 2017-01-22; authors Arthur Tenenhaus and Vincent Guillemot; license GPL (>= 2)), kept here so that [MOFS](https://github.com/Zaoqu-Liu/MOFS) can install this version with `devtools::install_github()`. Every file except this README is identical to `RGCCA_2.1.tar.gz` from the [CRAN archive](https://cran.r-project.org/src/contrib/Archive/RGCCA/) (checked with `diff -r`). The current CRAN release (3.x) is a different version; for general use of RGCCA install it from [CRAN](https://CRAN.R-project.org/package=RGCCA) instead.

### Installation
```r
devtools::install_github("Zaoqu-Liu/RGCCA")
```

### Citation
Tenenhaus et al. Variable Selection For Generalized Canonical Correlation Analysis. 2013. Submitted to Biostatistics.

Tenenhaus M., Tenenhaus A. and Groenen PJF (2017), Regularized generalized canonical correlation analysis: A framework for sequential multiblock component methods, Psychometrika, in press

Tenenhaus A., Philippe C., & Frouin V. (2015). Kernel Generalized Canonical Correlation Analysis. Computational Statistics and Data Analysis, 90, 114-131.

Tenenhaus A. and Tenenhaus M., (2011), Regularized Generalized Canonical Correlation Analysis, Psychometrika, Vol. 76, Nr 2, pp 257-284.

Schafer J. and Strimmer K., (2005), A shrinkage approach to large-scale covariance matrix estimation and implications for functional genomics. Statist. Appl. Genet. Mol. Biol. 4:32.
