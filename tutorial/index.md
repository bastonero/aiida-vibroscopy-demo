---
sd_hide_title: true
---

# Vibroscopy Demonstration

This tutorial is a demonstration of the AiiDA-Vibroscopy package.
It is intended to:

1. Give a brief overview of ab-initio phonons and vibrational spectra (IR and Raman), in the non-resonant first-order regime.
2. Show how the results of these workflows can be explored and easily post-processed.
3. Demonstrate the general framework using different functionals, among which DFT+U+V.

```{toctree}
:hidden:
:numbered:

1_what_is_vibroscopy
2_polar
3_iraman
4_iraman_functionals
5_next_steps
glossary
```

## Interacting with the tutorial

The tutorial is divided into a number of sections, most of which are written Jupyter notebook, that can be run within the [Conda environment](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) provided in {download}`environment.yaml <../environment.yml>`.

### Using Binder

The easiest way to run the notebooks is to click on the Binder badge below, which will launch a Binder instance with the environment pre-installed.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/chrisjsewell/aiida-qe-demo/main?labpath=tutorial)

Alternatively, any page with a 🚀 icon can be launched in Binder by clicking on it.

### Locally

Alternatively, you can run the tutorial locally, by following the instructions below.

#### Install the tutorial

First, clone the tutorial repository:

    git clone

Then, install the tutorial environment using [mamba](https://mamba.readthedocs.io):

    mamba env create -f environment.yml

Finally, activate the environment:

    mamba activate aiida-vibroscopy-demo

Then, start the Jupyter notebook server:

    jupyter lab
