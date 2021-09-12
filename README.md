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

The easiest way to get these is to use the [conda](https://store.continuum.io/) environment manager.
I suggest downloading and installing [miniconda](http://conda.pydata.org/miniconda.html).

Once this is installed, the following command will install all required packages in your Python environment (2021):
```
$ conda create -n skl_tut install numpy scipy pywidgets matplotlib scikit-learn ipython-notebook pillow jupyterlab
$ conda activate skl_tut
```

## Downloading the Tutorial Materials
I would highly recommend using git, not only for this tutorial, but for the
general betterment of your life.  Once git is installed, you can clone the
material in this tutorial by using the git address shown above:

```
git clone git://github.com/nesi/sklearn_tutorial.git
```

If you can't or don't want to install git, there is a link above to download
the contents of this repository as a zip file.  I may make minor changes to
the repository in the days before the tutorial, however, so cloning the
repository is a much better option.

Note also that some of the code in these notebooks will not work outside the
directory structure of this tutorial, so it is important to clone the full
repository if possible.


## Notebook Listing

```
jupyter lab 
```
Then navigate the directory structure. The notebooks are under the directory `notebooks`. Click on `index.ipynb` to get started.
