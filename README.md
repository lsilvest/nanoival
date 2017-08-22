Interval type with nanosecond precision for R

### Motivation

Thanks to the package
[nanotime](https://cran.r-project.org/web/packages/nanotime/index.html)
R now has vector of time points with nanosecond precision. `nanoival`
is an interval type that allows complex subsetting into such a vector
of time, for example to keep only specific portions of a time point
vector.

### Demo

### Examples

### Status

The package is in the very early stages and is largely untested.

See the [issue tickets](https://github.com/lsilvestri/nanoival/issues)
for an up to date list of potentially desirable, possibly planned, or
at least discussed items.

### Installation

```r
remotes::install_github("lsilvestri/nanoival")
```

### Author

Leonardo Silvestri

### License

GPL (>= 2)
