---
permalink: /research/
title: "Research"
author_profile: true
redirect_from: 
  - /md/
  - /research.html
---
## Nonparametric bootstrap correction for incidental parameter bias in maximum likelihood and (G)MM estimation, with Geert Dhaene
*This is my job market paper and you can find the latest version [here](http://yitianli.github.io/files/GMM.pdf).*

We show that the nonparametric bootstrap can be used to remove the leading bias term of maximum likelihood, method of moments, and generalized method of moment estimates of panel data models with incidental parameters. The bootstrap can also be iterated to remove higher-order bias terms, and it can be applied to improve estimates of other parameters of interest, such as average marginal effects or the variance of the unobserved heterogeneity. We discuss several examples and also compare the bootstrap with the jackknife.



## Panel probit: Three ways to reduce the incidental parameter bias
I examine three approaches to alleviate the incidental parameter problem in the panel probit model with fixed effects: conditional likelihood, correlated random effects, and uniform-integrated likelihood after orthogonalization. I study the bias reduction properties under various settings when $T=2$ and find that all three methods reduce the incidental parameter bias by 80% to 100%. The correlated random effects approach performs best, even when the correlated random effects model is misspecified.

## Panel Tobit: Some analytical results on the incidental parameter bias, with Geert Dhaene
The maximum likelihood estimator in nonlinear panel data models with fixed effects often suffers from the incidental parameter problem when the number of time periods, $T$, is small and fixed. Greene ([2004](https://econpapers.repec.org/article/tafemetrv/v_3a23_3ay_3a2004_3ai_3a2_3ap_3a125-147.htm)) shows by Monte Carlo simulations that in the fixed-effect panel Tobit model the maximum likelihood estimator of the error variance, $\sigma ^{2}$, is severely biased while that of the regression slope coefficients, $\beta $, is nearly unbiased. We complement Greene's simulations with theoretical results in a simple setup with $T=2$ and a single binary regressor. We find that the incidental parameter bias for $\beta $ is bounded and typically very small, while the relative bias for $\sigma ^{2}$ is negative and unbounded as the probability of censoring approaches $1$.