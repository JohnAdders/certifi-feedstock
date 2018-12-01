About certifi
=============

Home: http://certifi.io/

Package license: ISC

Feedstock license: BSD 3-Clause

Summary: Python package for providing Mozilla's CA Bundle.

Certifi is a curated collection of Root Certificates for validating the
trustworthiness of SSL certificates while verifying the identity of TLS
hosts.


Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/JohnAdders/certifi-feedstock/master.svg?label=Linux)](https://circleci.com/gh/JohnAdders/certifi-feedstock)
[![OSX](https://img.shields.io/travis/JohnAdders/certifi-feedstock/master.svg?label=macOS)](https://travis-ci.org/JohnAdders/certifi-feedstock)
[![Windows](https://img.shields.io/appveyor/ci/JohnAdders/certifi-feedstock/master.svg?label=Windows)](https://ci.appveyor.com/project/JohnAdders/certifi-feedstock/branch/master)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-certifi-green.svg)](https://anaconda.org/johnad/certifi) | [![Conda Downloads](https://img.shields.io/conda/dn/johnad/certifi.svg)](https://anaconda.org/johnad/certifi) | [![Conda Version](https://img.shields.io/conda/vn/johnad/certifi.svg)](https://anaconda.org/johnad/certifi) | [![Conda Platforms](https://img.shields.io/conda/pn/johnad/certifi.svg)](https://anaconda.org/johnad/certifi) |

Installing certifi
==================

Installing `certifi` from the `johnad` channel can be achieved by adding `johnad` to your channels with:

```
conda config --add channels johnad
```

Once the `johnad` channel has been enabled, `certifi` can be installed with:

```
conda install certifi
```

It is possible to list all of the versions of `certifi` available on your platform with:

```
conda search certifi --channel johnad
```




Updating certifi-feedstock
==========================

If you would like to improve the certifi recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`johnad` channel, whereupon the built conda packages will be available for
everybody to install and use from the `johnad` channel.
Note that all branches in the JohnAdders/certifi-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.
