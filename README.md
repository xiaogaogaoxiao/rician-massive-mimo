Massive MIMO with Spatially Correlated Rician Fading Channels
==================

This is a code package is related to the follow scientific article:

Özgecan Özdogan, Emil Björnson, Erik G. Larsson, “[Massive MIMO with Spatially Correlated Rician Fading Channels](https://arxiv.org/abs/1805.07972),” IEEE Transactions on Communications, To appear.

The package contains a simulation environment, based on Matlab, that reproduces some of the numerical results and figures in the article. *We encourage you to also perform reproducible research!*


## Abstract of Article

This paper considers multi-cell massive multiple-input multiple-output systems, where the channels are spatially correlated Rician fading. The channel model is composed of a deterministic line-of-sight path and a stochastic non-line-of-sight component describing a practical spatially correlated multipath environment. We derive the statistical properties of the minimum mean squared error (MMSE), element-wise MMSE, and least-square channel estimates for this model. Using these estimates for maximum ratio combining and precoding, rigorous closed-form uplink (UL) and downlink (DL) achievable spectral efficiency (SE) expressions are derived and analyzed. The asymptotic SE behavior, when using the different channel estimators, are also analyzed. The numerical results show that the SE is higher when using the MMSE estimator than that of the other estimators, and the performance gap increases with the number of antennas.


## Content of Code Package

The article contains 6 simulation figures, numbered 1-6. Figure X is generated by the Matlab script mainFileFigureX.m for X=1,...,6.
The package also contains 16 Matlab functions that are used by some of the scripts.

See each file for further documentation.


## Acknowledgements

This work was supported in part by ELLIIT and in part by the Swedish Research Council.


## License and Referencing

This code package is licensed under the GPLv2 license. If you in any way use this code for research that results in publications, please cite our original article listed above.
