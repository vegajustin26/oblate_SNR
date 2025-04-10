Question: What orbital and physical parameters are most important in detecting an oblate exoplanet in transit?

This is a small project that aims to predict the signal-to-noise (SNR) ratio of a transit from properties of a exoplanet (that is slightly oblate) and its orbit. Using [`squishyplanet`](https://github.com/ben-cassese/squishyplanet) and my own code [`oblate_lc`](https://github.com/vegajustin26/oblate_lc), I simulated about ~630000 different kinds of exoplanets varying six different (important!) parameters, and calculated their transit SNRs according to [Kipping 2023](https://arxiv.org/abs/2305.06790). From this dataset, we can then build an emulator to use as a tool for prediction.

The following notebook details several methods for estimating transit SNR from six orbital parameters of an exoplanet.
