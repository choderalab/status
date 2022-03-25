Maintainer Dashboard
====================

Inspired by https://github.com/openforcefield/status

### Openeye Status Check
[![Openeye License Check](https://github.com/choderalab/argos/actions/workflows/openeye-license-check.yaml/badge.svg)](https://github.com/choderalab/argos/actions/workflows/openeye-license-check.yaml)

### Chodera Lab Repositories

| Package | Tests | Documentation | Coverage | conda-forge | Install Check |
|---|---|---|---|---|---| 
| [**Perses**](https://github.com/choderalab/perses/) | [![CI](https://github.com/choderalab/perses/actions/workflows/CI.yaml/badge.svg)](https://github.com/choderalab/perses/actions/workflows/CI.yaml) [![self-hosted-gpu-test](https://github.com/choderalab/perses/actions/workflows/self-hosted-gpu-test.yml/badge.svg)](https://github.com/choderalab/perses/actions/workflows/self-hosted-gpu-test.yml) | [![Documentation Status](https://readthedocs.org/projects/perses/badge/?version=latest)](http://perses.readthedocs.io/en/latest/?badge=latest) | [![codecov](https://codecov.io/gh/choderalab/perses/branch/main/graph/badge.svg)](https://codecov.io/gh/choderalab/perses/branch/main) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/perses.svg)](https://anaconda.org/conda-forge/perses) | [![Perses Install Check](https://github.com/choderalab/argos/actions/workflows/perses-install-test.yaml/badge.svg)](https://github.com/choderalab/argos/actions/workflows/perses-install-test.yaml) |
| [**openmmtools**](https://github.com/choderalab/openmmtools) | [![CI](https://github.com/choderalab/openmmtools/actions/workflows/CI.yml/badge.svg)](https://github.com/choderalab/openmmtools/actions/workflows/CI.yml) | [![Documentation Status](https://readthedocs.org/projects/openmmtools/badge/?version=latest)](https://openmmtools.readthedocs.io/en/latest/?badge=latest) | | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/openmmtools.svg)](https://anaconda.org/conda-forge/openmmtools) |

### Important Upstream Repositories

| Package | Tests | Documentation | Coverage | conda-forge | Install Check |
|---|---|---|---|---|---|
| [**openmm**](https://github.com/openmm/openmm) | [![GH Actions Status](https://github.com/openmm/openmm/workflows/CI/badge.svg)](https://github.com/openmm/openmm/actions?query=branch%3Amaster+workflow%3ACI) | | | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/openmm.svg)](https://anaconda.org/conda-forge/openmm) | |


#### Future Work
* Use a yaml file + jinja template to build the README.md programmatically 
* Some workflow/bot commands to re-run CI
* Automate issue creation when status changes
* For each package, figure out which python versions we want to support
* Check to see if caching downloads is a bad idea or not
