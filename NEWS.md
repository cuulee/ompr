# ompr 0.7.0.9000

* Removed `dplyr` dependency
* Added `MILPModel`, a new, vectorized backend for mixed integer linear programs that can handle very large models. It will eventually replace `MIPModel` - planned for release `0.8`.

# ompr 0.7.0

## Breaking changes

* `ompr` now uses sparse constraint matrices. `extract_constraints` now returns a sparse matrix and `objective_function` returns a sparse vector.
* The minimum supported R version is now `3.3.0`
* Fixed an issue with `Rcpp`. The minimum `Rcpp` version is now `0.12.12`

## Minor changes

* New progress bar based on the `progress` package.

# ompr 0.6.0

* First version on CRAN


