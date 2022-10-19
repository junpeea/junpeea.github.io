---
layout: default
title: Spatial Statistics
parent: Research
nav_order: 1
---

Spatial statistics is generally viewed as being comprised of three bajor branches: (1) countinuous spatial variation (point-referenced data); (2) discrete spatial variation (lattice or areal-unit data); and (3) spatial point patterns. [reference](https://doi.org/10.1201/9781420072884)

## Nonparametric Spectral Bayesian Spatial Regression 

Paper  link : [Jun and Lim (2021)](https://doi.org/10.1007/s42952-021-00156-y)\
Github link : [NSBSR](https://github.com/junpeea/NSBSR)\
Abstract :\
We consider modeling of Fourier coefficients, known as a spectral density function to represent spatial dependence of a stationary spatial random field and use it for spatial regression under a Bayesian framework. Especially, we switch from the space domain to the frequency domain and introduce a Gaussian process prior to the log spectral density. As we do not impose any further assumption on log spectral density, resulting covariance function is not of a parametric form and/or isotropic assumption. Simulation study supports that our approach is robust over various parametric covariance models. Also, our approach gives comparable or better prediction results over conventional spatial prediction under most parametric covariance models that we considered. Even though we need to estimate spectral density at all Fourier frequencies during the Bayesian procedure, our approach does not lose much computational efficiency compared to estimating only a few parameters in the parametric covariance models. We also compare our approach with some other existing spatial prediction approaches using two datasets of Korean ozone concentration. Our approach performs reasonably good in terms of mean absolute error and root mean squared error.

## Nonparametric Spectral Bayesian Temporal Regression

Paper  link : [Jun, Lim, and Kim (2022+)](https://doi.org/10.48550/arXiv.2210.07457)\
Github link : [NSBTR](https://github.com/junpeea/NSBTR)\
Abstract :\
Autocovariance of the error term in a time series model plays a key role in the estimation and inference for the model that it belongs to. Typically, some arbitrary parametric structure is assumed upon the error to simplify the estimation, which inevitably introduces potential model-misspecification. We thus conduct nonparametric estimation of it. To avoid the difficult bandwidth selection issue under the traditional nonparametric truncation approach, this paper conducts the Bayesian estimation of its spectral density in a frequency domain. To this end, we consider two cases: fixed error variance and time-varying one. Each approach is taken to estimate the spectral density of the autocovariance and the model parameters. The methodology is applied to exchange rate forecasting and proves to compete favorably against some benchmark models, including the random walk without drift.

