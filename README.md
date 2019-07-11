About bluesky
=============

Home: https://github.com/NSLS-II/bluesky

Package license: BSD

Feedstock license: BSD 3-Clause

Summary: 



Current build status
====================


<table><tr>
    <td>Appveyor</td>
    <td>
      <a href="https://ci.appveyor.com/project/buijennifer/bluesky-feedstock/branch/master">
        <img alt="windows" src="https://img.shields.io/appveyor/ci/buijennifer/bluesky-feedstock/master.svg?label=Windows">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/buijennifer/nsls2/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/buijennifer/nsls2/_apis/build/status/bluesky-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_python3.6</td>
              <td>
                <a href="https://dev.azure.com/buijennifer/nsls2/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/buijennifer/nsls2/_apis/build/status/bluesky-feedstock?branchName=master&jobName=linux&configuration=linux_python3.6" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_python3.7</td>
              <td>
                <a href="https://dev.azure.com/buijennifer/nsls2/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/buijennifer/nsls2/_apis/build/status/bluesky-feedstock?branchName=master&jobName=linux&configuration=linux_python3.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python3.6</td>
              <td>
                <a href="https://dev.azure.com/buijennifer/nsls2/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/buijennifer/nsls2/_apis/build/status/bluesky-feedstock?branchName=master&jobName=osx&configuration=osx_python3.6" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python3.7</td>
              <td>
                <a href="https://dev.azure.com/buijennifer/nsls2/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/buijennifer/nsls2/_apis/build/status/bluesky-feedstock?branchName=master&jobName=osx&configuration=osx_python3.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_python3.6</td>
              <td>
                <a href="https://dev.azure.com/buijennifer/nsls2/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/buijennifer/nsls2/_apis/build/status/bluesky-feedstock?branchName=master&jobName=win&configuration=win_python3.6" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_python3.7</td>
              <td>
                <a href="https://dev.azure.com/buijennifer/nsls2/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/buijennifer/nsls2/_apis/build/status/bluesky-feedstock?branchName=master&jobName=win&configuration=win_python3.7" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
![ppc64le disabled](https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg)
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-bluesky-green.svg)](https://anaconda.org/-/bluesky) | [![Conda Downloads](https://img.shields.io/conda/dn/-/bluesky.svg)](https://anaconda.org/-/bluesky) | [![Conda Version](https://img.shields.io/conda/vn/-/bluesky.svg)](https://anaconda.org/-/bluesky) | [![Conda Platforms](https://img.shields.io/conda/pn/-/bluesky.svg)](https://anaconda.org/-/bluesky) |

Installing bluesky
==================

Installing `bluesky` from the `-` channel can be achieved by adding `-` to your channels with:

```
conda config --add channels -
```

Once the `-` channel has been enabled, `bluesky` can be installed with:

```
conda install bluesky
```

It is possible to list all of the versions of `bluesky` available on your platform with:

```
conda search bluesky --channel -
```




Updating bluesky-feedstock
==========================

If you would like to improve the bluesky recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`-` channel, whereupon the built conda packages will be available for
everybody to install and use from the `-` channel.
Note that all branches in the buijennifer/bluesky-feedstock are
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


