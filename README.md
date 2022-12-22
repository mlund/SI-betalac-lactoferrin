[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mlund/template-for-supporting-information/HEAD)

# β-lactoglobulin dimer ↔︎ Lactoferrin Association

In this notebook we explore the interaction between lactoferrin and a β-lactoglobulin dimer using Metropolis-Hastings Monte Carlo (MC) simulations

## Layout

Description of the directory layout.

- `with_bias`. This contains a notebook for running and analysing MC simulations with a biasing potential to allow to
  better sampling along the protein mass-center separation.

## Requirements

To run the Notebooks online, click on the _Launch Binder_ logo above. Alternatively, if you want to run on your own computer,
install python using e.g. [Miniconda](https://conda.io/miniconda.html) or [Anaconda](https://docs.conda.io))
and make sure all required packages are loaded by issuing the following terminal commands

``` bash
    conda env create -f environment.yml
    source activate my_environment
    jupyter-notebook
```
