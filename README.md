[![Binder](http://binder.pangeo.io/badge.svg)](http://binder.pangeo.io/v2/gh/nbren12/2018-11-06-python-in-geosciences/master)

# Using python for machine learning with large gridded datasets

In this talk, I will discuss the tools behind some of my recent work building
machine-learned components for climate models. A typical machine learning
pipeline consists of three stages: 1) data munging , 2) model training, and 3)
model evaluation. The corresponding libraries I use for each of these stages
are 1) xarray, 2) scikit-learn and PyTorch, and 3) HoloViews and matplotlib for
visualization. I will demonstrate how all these tools come together on a simple
example problem. Time permitting, I will also discuss how to embed python-based
machine learning models within a Fortran climate model. 

# The Dataset

The data we use is coarse-grained subset of a high resolution atmospheric
simulation. Here is a video:

<iframe src="https://player.vimeo.com/video/299128849" width="640" height="320"
frameborder="0" webkitallowfullscreen mozallowfullscreen
allowfullscreen></iframe>
<p><a href="https://vimeo.com/299128849">ngaqua_eqx_QOBS_days100-180_cld</a>
from <a href="https://vimeo.com/user91419549">Noah Brenowitz</a> on <a
href="https://vimeo.com">Vimeo</a>.</p>
