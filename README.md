This is a small project that aims to build an emulator for the signal-to-noise ratio of a transiting exoplanet that is slightly oblate. Using [`squishyplanet`](https://github.com/ben-cassese/squishyplanet) and my own code ['oblate_lc'](https://github.com/vegajustin26/oblate_lc), I simulated about ~630000 different kinds of exoplanets in a 6-dimensional parameter space, and recorded their transit SNRs according to [Kipping 2023](https://arxiv.org/abs/2305.06790).

The following details several methods one could use to estimate a transit SNR from six parameters of an exoplanet's orbit.
