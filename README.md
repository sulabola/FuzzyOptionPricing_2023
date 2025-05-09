# Fuzzy Option Pricing for Jump Diffusion Model using Neuro Volatility Models

Recently, there has been a growing interest in studying fuzzy option pricing using Monte Carlo (MC) methods for diffusion models. The traditional volatility estimator has a larger asymptotic variance. In this paper, data-driven neuro-volatility estimates with smaller variances are used to obtain direct volatility forecasts. Asymmetric nonlinear adaptive fuzzy numbers are used to address ambiguity and vagueness associated with volatility estimates. This study uses fuzzy set theory and data-driven volatility forecasts to study call option prices of the S&P 500 index.

The PDF copy of the paper can be downloaded from here: [Download Paper](https://ieeexplore.ieee.org/abstract/document/10196980) 

A preprint version of the paper is available in the repository.

Programming Language: [R](https://cran.r-project.org/bin/windows/base/) / [RStudio](https://posit.co/downloads/) / [WinBUGS](https://www.mrc-bsu.cam.ac.uk/software/bugs-project)

Data: The option price data and treasury bill rates used are available in the CSV file in the repository. The source of data is [Bloomberg](https://www.bloomberg.com/canada)

### Findings

Four modeling approaches have been considered: the Black-Scholes (BS) model, the Monte Carlo option pricing with normal / $t$ errors, and the Jump-Diffusion (JD) model. Fuzzy $\alpha$-cuts of option prices are presented and discussed under different parameter values. The experimental study suggests that the JD model predicts the call option price more accurately compared to BS, normal errors, and $t$ errors using the volatility estimate obtained using the Bayesian approach.
