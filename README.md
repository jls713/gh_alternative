# Probability functions for near-Gaussian distributions

This repository contains functions for the evaluation of the probability functions in Sanders & Evans (2020, submitted). 

The Gauss-Hermite series is a useful model for including weak non-Gaussianity. However, its use in a probabilistic framework is limited as it is not guaranteed to be positive-definite. In Sanders & Evans (2020, submitted) we presented alternative probability density functions which are guaranteed positive-definite and resemble the properties of a Gauss-Hermite series. The models are constructed via the convolution of a kernel K(y) with a Gaussian. Further convolutions by Gaussian uncertainties are simply incorporated.

Two kernels have proved useful. The uniform kernel which produces models with negative excess kurtosis and the Laplace kernel which produces models with positive excess kurtosis. We provide [functions](line_profiles.py) to evaluate the pdf of each of these, the logarithm of the pdf and their Fourier transforms.

A [notebook](examples.ipynb) with examples of how to use the code and reproduce some plots in Sanders & Evans (2020) is provided.
