# Scikit-learn Tutorial

Original tutorial material from

*Jake VanderPlas*

- email: <jakevdp@uw.edu>
- twitter: [@jakevdp](https://twitter.com/jakevdp)
- github: [jakevdp](http://github.com/jakevdp)

This repository contains notebooks and other files associated with the
[Scikit-learn](http://scikit-learn.org) tutorial.

This tutorial has been updated by NeSI (http://github.com/nesi/sklearn_tutorial.git) to run with recent
versions of Python and its dependencies.

## Installation Notes
This tutorial requires the following packages:

- Python version 3.8 or later
- `numpy` version 1.19 or later: http://www.numpy.org/
- `scipy` version 1.4 or later: http://www.scipy.org/
- `matplotlib` version 3.0 or later: http://matplotlib.org/
- `scikit-learn` version 0.22 or later: http://scikit-learn.org

Read NESI.md to find out how to run the notebooks on NeSI. All the above packages are already 
installed on NeSI's [jupyter hub](https://jupyter.nesi.org.nz/).

If you prefer to run on your laptop then we recommend that you download and install [miniconda](http://conda.pydata.org/miniconda.html).
Once this is installed, the following command will install all required packages in your Python environment (2021):
```
$ conda create -n skl_tut install numpy scipy pywidgets matplotlib scikit-learn ipython-notebook pillow jupyterlab
$ conda activate skl_tut
```

## Downloading the Tutorial Materials
We have already installed all the notebooks on NeSI's [jupyter hub](https://jupyter.nesi.org.nz/). However,
if you prefer to run on your laptop, you will need to clone the repository:
```
git clone https://github.com/nesi/sklearn_tutorial.git
```
or 
```
git clone git@github.com:nesi/sklearn_tutorial.git
```

Note also that some of the code in these notebooks will not work outside the
directory structure of this tutorial, so it is important to clone the full
repository if possible.


## Notebook Listing

```
jupyter lab 
```
Then navigate the directory structure. The notebooks are under the directory `notebooks`. Click on `index.ipynb` to get started.
