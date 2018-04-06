# PyMT Demos

## Install Python

    $ curl https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh > miniconda.sh # Mac
    $ curl https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh > miniconda.sh # Linux
    $ bash ./miniconda.sh -b -f -p $(pwd)/conda
    $ export PATH=$(pwd)/conda/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/etc:/usr/lib

## Install an environment for the pymt-demo

    $ conda env create -f environment.yml
