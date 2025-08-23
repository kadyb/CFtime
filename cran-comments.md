## R CMD check results

0 errors | 0 warnings | 0 notes

* Additional checks have been performed with GHA and devtools::check(remote = TRUE, manual = TRUE)
and devtools::check_win_devel().

* This minor release 1.7.0 has some new functions and fixes an error.

## revdepcheck results

We checked 5 reverse dependencies, comparing R CMD check results across CRAN and dev versions of this package.

 * We saw 0 new problems
 * We failed to check 1 packages

Issues with CRAN packages are summarised below.

### Failed to check

* dacc (NA): This package uses a CFtime function that has been deprecated over a year ago and removed in this release. The maintainer was notified of this change, including the required (and very trivial) change in the code of that package.
