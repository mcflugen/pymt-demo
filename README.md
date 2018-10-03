# PyMT Demos

## Install Python

The easiest way to install `pymt` is through [`conda`](https://conda.io/docs/),
the package manager for the [Anaconda python distribution](https://anaconda.com).
You can either [install the full version of Anaconda](https://www.anaconda.com/download) (which includes hundreds of
open source packages) or a minimal version using [miniconda](https://conda.io/docs/user-guide/install))

## Optional: Create an new environment

Before installing the packages necessary for this demo, you may want to create
a new environment into which to install them. This can be done through the
conda command,

    conda create -n pymt python=3.6
    conda activate

## Install pymt

With Anaconda installed, installing `pymt` from the `conda-forge` channel
can be achieved by adding `conda-forge` to your channels with:

  conda config --add channels conda-forge

Once the `conda-forge` channel has been enabled, `pymt` can be installed with:

  conda install pymt

For this demo, you will also need to install `sedflux` and `child`,

  conda install sedflux child

## Open the notebook

    $ jupyter notebook 'Example 1 and 2.ipynb'
