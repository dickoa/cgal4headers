[![GitLab CI Build
Status](https://gitlab.com/dickoa/cgal4headers/badges/master/pipeline.svg)](https://gitlab.com/dickoa/cgal4headers/pipelines)
[![](http://www.r-pkg.org/badges/version/cgal4headers)](http://www.r-pkg.org/pkg/cgal4headers)


# cgal4headers

R interface to the C++ header-only [CGAL](https://www.cgal.org) version 4 library

This package is using the version 4.14.3 of CGAL.

## Install


Install the development version with the `remotes` R package

```
remotes::install_gitlab("dickoa/cgal4headers")
```

## Using cgal4headers


To use `cgal4headers` in your own package, add a dependency to `cgal4headers` to your cpp files **before** a call to `#include <Rcpp.h>`

```
// [[Rcpp::depends(cgal4headers)]]

#include <Rcpp.h>
```

## License

This package is provided under the double [GPL-3](https://www.gnu.org/licenses/gpl-3.0.en.html) | [LGPL-3](https://www.gnu.org/licenses/lgpl-3.0.en.html) license like CGAL.
