# bdglm
An R package on Generalized Linear Models for Counts Data under Balanced Discrete Distribution Families

# Description
Fitting and assessing generalized linear models for count data using balanced discrete distributions.

Routines are offered to build count models starting from continuous distributions which are discretized to handle integer valued response variables.

The key advantage of balanced discrte models is their straightforward mean-parametrization.

The currently available balanced distributions include: Gamma, Generalized Gamma, Lognormal, Inverse-Gaussian, Gaussian and Beta.

Except for the discrete Beta and Generalized Gamma families which are three-parameter models, the distributions are two-parameter models with a scale parameter which can be observation specific and allows full dispersion flexibility.

For model comparison purposes, the popular Double-Poisson and Gamma-Count models are also implemented under mean-parametrizations.
