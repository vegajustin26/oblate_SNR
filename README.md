This is a small project that aims to build an emulator for the signal-to-noise ratio of a transiting exoplanet that is slightly oblate. Using [`squishyplanet`](https://github.com/ben-cassese/squishyplanet) and my own code [`oblate_lc`](https://github.com/vegajustin26/oblate_lc), I simulated about ~630000 different kinds of exoplanets varying six different (important!) parameters, and calculated their transit SNRs according to [Kipping 2023](https://arxiv.org/abs/2305.06790).

The following notebook details several methods for estimating transit SNR from six orbital parameters of an exoplanet.
