**Question:** What orbital and physical parameters are most important in detecting an oblate exoplanet in transit?

This is a project that aims to predict the signal-to-noise (SNR) ratio of a transit from properties of an oblate planet. Using [`squishyplanet`](https://github.com/ben-cassese/squishyplanet) and my own code [`oblate_lc`](https://github.com/vegajustin26/oblate_lc), I simulated the orbits of ~630000 different kinds of exoplanets varying six different (important!) parameters. The SNR was also calculated according to [Kipping 2023](https://arxiv.org/abs/2305.06790). From this dataset, we can now build an emulator to use as a tool for detectability.

The following notebook details several methods for estimating transit SNR from six orbital parameters of an exoplanet.
