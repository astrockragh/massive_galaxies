# The most massive galaxies in the early universe

Code to replicate paper (ArXiv link coming soon) where we calculat the distribution of most massive galaxies in single fields in the early universe, taking into account cosmic (field-to-field + super - Poissonian) variance. 

The main point is that cosmic variance matters a lot, changing both the center and shape of the posteriors!

The CDF of the posterior is calculated in ```make_distributions.ipynb```, and can be visualized in ```make_figures.ipynb```. ```make_figures.ipynb``` also contains a comparison to the Extreme Value Statistics (EVS) approach.

This project makes use of a rewritten cosmic variance calculator in ```Python```, which is also released alongside the paper. The package can be found on [PyPi](https://pypi.org/project/cosmic-variance/) (for pip install) or on [GitHub](https://github.com/astrockragh/cosmic_variance). The ```get_cosmic_variance.ipynb``` notebook contains a short example of how to use the calculator.
