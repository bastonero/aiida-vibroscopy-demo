# aiida-vibroscopy demo

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bastonero/aiida-vibroscopy-demo/HEAD)

A demonstration tutorial on using aiida-vibroscopy (with the style adapted from the [aiida-qe-demo](https://aiida-qe-demo.readthedocs.io/en/latest/)).

## Building the documentation

To build the documentation, first install the dependencies in a conda environment (using mamba to resolve dependencies):

    mamba env create -f environment.yml
    conda activate aiida-vibroscopy-demo

Then, build the documentation:

    sphinx-build -nW --keep-going -b html tutorial tutorial/_build/html

Note that the first time you build the documentation, it will take a while to execute all the notebooks.
But subsequent builds will be much faster, as the notebooks will be cached.
