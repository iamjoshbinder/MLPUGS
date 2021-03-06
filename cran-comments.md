MLPUGS 0.2.0
------------

## Test environments
* local OS X install, R 3.3.1
* win-builder (devel and release)

## R CMD check results
There were no ERRORs or WARNINGs. There was 1 NOTE:

```
* checking CRAN incoming feasibility ... NOTE
Maintainer: ‘Mikhail Popov <mikhail@mpopov.com>’

New submission

License components with restrictions and base license permitting such:
  MIT + file LICENSE
File 'LICENSE':
  YEAR: 2015
  COPYRIGHT HOLDER: Mikhail Popov
```

## Resubmission
This is a resubmission. In this version I have:

* Added minimal examples that execute within 5 seconds.

### Previous resubmission
Previously, I have:

* Updated DESCRIPTION:
    - Switched to writing 'Multi-Label' in Title.
    - Added the initialism (CC's) after 'classifier chains' in Description
    - Single-quoted 'C50' and 'randomForest' suggestions in Description
* Corrected the LICENSE file to comply with the [MIT template](https://www.r-project.org/Licenses/MIT)
