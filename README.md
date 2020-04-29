# SPTPol-montepython

**Contributors:** Anton Chudaykin

There are the complete SPTPol likelihoods for the MCMC sampler [Montepython](https://github.com/brinckmann/montepython_public). They represent measurements of TE/EE power spectrum and lensing potential power spectrum of the cosmic microwave background (CMB) using 150 GHz data from the 500 Square Degrees of SPTpol survey. Our code address astrophysical foregrounds, instrumental calibration, beam uncertainty, bandpower window functions and covariance matrixes. The original likelihoods written for different MCMC sampler CosmoMC were analyzed in the following papers

* [*Measurements of the Temperature and E-Mode Polarization of the CMB from 500 Square Degrees of SPTpol Data*](https://arxiv.org/abs/1707.09353)
* [*Constraints on Cosmological Parameters from the 500 deg2 SPTpol Lensing Power Spectrum*](https://arxiv.org/abs/1910.07157)

Our code was tested with [Montepython v3.2.0](https://baudren.github.io/montepython.html).

The repo includes: 

* Measurements of the E-mode polarization angular power spectrum and temperature-E-mode cross power spectrum (TE) over the multipole range 50<l<8000
* Measurements of the lensing potential power spectrum in the multipole
range 100<l<2000. The lensing potential is reconstructed from a minimum-variance quadratic estimator that combines both the temperature and polarization CMB maps

# Using the code

You can use SPTPol-likelihoods freely, provided that in your publications you cite arXiv:2004.13046. 
