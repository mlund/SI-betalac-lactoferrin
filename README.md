[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mlund/SI-betalac-lactoferrin/HEAD)
[![CC BY 4.0][cc-by-shield]][cc-by]
[![ruff](https://github.com/mlund/SI-betalac-lactoferrin/actions/workflows/ruff.yml/badge.svg)](https://github.com/mlund/SI-betalac-lactoferrin/actions/workflows/ruff.yml)

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg


# β-lactoglobulin dimer ↔︎ Lactoferrin Association

In this notebook we explore the interaction between lactoferrin and a β-lactoglobulin dimer using
Metropolis-Hastings Monte Carlo (MC) simulations

## Layout

Description of the directory layout.

- `with_bias`. This contains a notebook for running and analysing MC simulations with a biasing potential to allow to
  better sampling along the protein mass-center separation.

## Requirements

To run the Notebooks online, click on the _Launch Binder_ logo above.
Alternatively, run it locally by
installing python using e.g. [Mambaforge](https://github.com/conda-forge/miniforge#mambaforge).
An environment with the required packages is then created with:

``` bash
    mamba env create -f environment.yml
    source activate betalac
    jupyter-lab
```
