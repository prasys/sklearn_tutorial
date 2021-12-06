# Scikit-learn Tutorial

Original tutorial material from *Jake VanderPlas*

- email: <jakevdp@uw.edu>
- twitter: [@jakevdp](https://twitter.com/jakevdp)
- github: [jakevdp](http://github.com/jakevdp)

This repository contains notebooks and other files associated with the
[Scikit-learn](http://scikit-learn.org) tutorial. The notebooks have been 
updated by NeSI (http://github.com/nesi/sklearn_tutorial.git) to run with recent
versions of Python and dependencies.


## Downloading the Tutorial Materials

We have already installed all the notebooks on NeSI's [jupyter hub](https://jupyter.nesi.org.nz/).
However, if you prefer to run on your laptop, you will need to clone the repository:
```
git clone https://github.com/nesi/sklearn_tutorial.git
```

Note also that some of the code in these notebooks will not work outside the
directory structure of this tutorial, so it is important to clone the full
repository if possible.


## Installation Notes

Read [NESI.md](NESI.md) to find out how to run the notebooks on NeSI.
All the packages required by the tutorial are already installed on NeSI's [jupyter hub](https://jupyter.nesi.org.nz/).

If you prefer to run on your own computer then we recommend that you download and
install [miniconda](http://conda.pydata.org/miniconda.html). Once `miniconda` is
installed, navigate to your local copy of the repository and use the following
command to install all required packages in your Python environment:
```
conda env create -f environment.yml
```
Then activate your environment:
```
conda activate skl_tut
```

The tutorial material has been tested on NeSI with the following package versions:
- Python version 3.8.1
- `numpy` version 1.19.1: https://www.numpy.org
- `scipy` version 1.4.1: https://www.scipy.org
- `matplotlib` version 3.0.3: https://matplotlib.org
- `scikit-learn` version 0.22.1: https://scikit-learn.org
- `jupyterlab` version 3.9.1: https://jupyterlab.readthedocs.io
- `ipywidgets` version 7.5.1: https://ipywidgets.readthedocs.io
- `pandas` version 1.1.0: https://pandas.pydata.org/


## Notebook Listing

If you have followed the installation instructions to run on your laptop, start `JupyterLab`:
```
jupyter lab 
```
Then navigate the directory structure. The notebooks are under the directory `notebooks`.
Click on `Index.ipynb` to get started.
