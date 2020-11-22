About pybind11-stubgen
======================

Home: https://github.com/sizmailov/pybind11-stubgen

Package license: BSD-3-Clause

Feedstock license: [BSD-3-Clause](https://github.com/sdvillal/pybind11-stubgen-feedstock/blob/master/LICENSE.txt)

Summary: PEP 561 type stubs generator for pybind11 modules

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
        <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/pybind11-stubgen-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pybind11--stubgen-green.svg)](https://anaconda.org/sdvillal/pybind11-stubgen) | [![Conda Downloads](https://img.shields.io/conda/dn/sdvillal/pybind11-stubgen.svg)](https://anaconda.org/sdvillal/pybind11-stubgen) | [![Conda Version](https://img.shields.io/conda/vn/sdvillal/pybind11-stubgen.svg)](https://anaconda.org/sdvillal/pybind11-stubgen) | [![Conda Platforms](https://img.shields.io/conda/pn/sdvillal/pybind11-stubgen.svg)](https://anaconda.org/sdvillal/pybind11-stubgen) |

Installing pybind11-stubgen
===========================

Installing `pybind11-stubgen` from the `sdvillal` channel can be achieved by adding `sdvillal` to your channels with:

```
conda config --add channels sdvillal
```

Once the `sdvillal` channel has been enabled, `pybind11-stubgen` can be installed with:

```
conda install pybind11-stubgen
```

It is possible to list all of the versions of `pybind11-stubgen` available on your platform with:

```
conda search pybind11-stubgen --channel sdvillal
```




Updating pybind11-stubgen-feedstock
===================================

If you would like to improve the pybind11-stubgen recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`sdvillal` channel, whereupon the built conda packages will be available for
everybody to install and use from the `sdvillal` channel.
Note that all branches in the sdvillal/pybind11-stubgen-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@sdvillal](https://github.com/sdvillal/)

