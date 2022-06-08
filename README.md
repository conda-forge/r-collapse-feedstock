About r-collapse
================

Home: https://sebkrantz.github.io/collapse/, https://github.com/SebKrantz/collapse, https://twitter.com/collapse_R

Package license: GPL-2.0-or-later

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-collapse-feedstock/blob/main/LICENSE.txt)

Summary: A C/C++ based package for advanced data transformation and statistical computing in R that is extremely fast, flexible and parsimonious to code with, class-agnostic and programmer friendly. It is well integrated with base R, 'dplyr' / (grouped) 'tibble', 'data.table', 'plm' (panel-series and data frames), 'sf' data frames, and non-destructively handles other matrix or data frame based classes (such as 'ts', 'xts' / 'zoo', 'timeSeries', 'tsibble', 'tibbletime' etc.) --- Key Features: --- (1) Advanced statistical programming: A full set of fast statistical functions supporting grouped and weighted computations on vectors, matrices and data frames. Fast and programmable grouping, ordering, unique values / rows, factor generation and interactions. Fast and flexible functions for data manipulation, data object conversions, and memory efficient R programming. (2) Advanced aggregation: Fast and easy multi-data-type, multi-function, weighted, parallelized and fully custom data aggregation. (3) Advanced transformations: Fast row / column arithmetic, (grouped) replacing and sweeping out of statistics, (grouped, weighted) scaling / standardizing, between (averaging) and (quasi-)within (demeaning) transformations, higher-dimensional centering (i.e. multiple fixed effects or polynomials), linear prediction, model fitting and testing exclusion restrictions. (4) Advanced time-computations: Fast (sequences of) lags / leads, and (lagged / leaded, iterated, quasi-, log-) differences and (compounded) growth rates on (irregular) time series and panel data. Multivariate auto-, partial- and cross-correlation functions for panel data. Panel data to (ts-)array conversions. (5) List processing: (Recursive) list search, splitting, extraction / subsetting, data-apply, and generalized recursive row-binding / unlisting in 2D. (6) Advanced data exploration: Fast (grouped, weighted, panel-decomposed) summary statistics for complex multilevel / panel data.

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=15498&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-collapse-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_r_base4.0</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=15498&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-collapse-feedstock?branchName=main&jobName=linux&configuration=linux_64_r_base4.0" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_r_base4.1</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=15498&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-collapse-feedstock?branchName=main&jobName=linux&configuration=linux_64_r_base4.1" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.0</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=15498&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-collapse-feedstock?branchName=main&jobName=osx&configuration=osx_64_r_base4.0" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.1</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=15498&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-collapse-feedstock?branchName=main&jobName=osx&configuration=osx_64_r_base4.1" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_r_base4.0</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=15498&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-collapse-feedstock?branchName=main&jobName=win&configuration=win_64_r_base4.0" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_r_base4.1</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=15498&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-collapse-feedstock?branchName=main&jobName=win&configuration=win_64_r_base4.1" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--collapse-green.svg)](https://anaconda.org/conda-forge/r-collapse) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-collapse.svg)](https://anaconda.org/conda-forge/r-collapse) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-collapse.svg)](https://anaconda.org/conda-forge/r-collapse) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-collapse.svg)](https://anaconda.org/conda-forge/r-collapse) |

Installing r-collapse
=====================

Installing `r-collapse` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `r-collapse` can be installed with `conda`:

```
conda install r-collapse
```

or with `mamba`:

```
mamba install r-collapse
```

It is possible to list all of the versions of `r-collapse` available on your platform with `conda`:

```
conda search r-collapse --channel conda-forge
```

or with `mamba`:

```
mamba search r-collapse --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search r-collapse --channel conda-forge

# List packages depending on `r-collapse`:
mamba repoquery whoneeds r-collapse --channel conda-forge

# List dependencies of `r-collapse`:
mamba repoquery depends r-collapse --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [Anaconda-Cloud](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-collapse-feedstock
=============================

If you would like to improve the r-collapse recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-collapse-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@SebKrantz](https://github.com/SebKrantz/)
* [@conda-forge/r](https://github.com/conda-forge/r/)

