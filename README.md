# VAR-fucntions

-The ARMA_funky3 function generates an ARMA process with the specified AR (autoregressive component) and MA (moving-average component) characteristics, as well as the duration.

-The OLSregression function utilizes ordinary-least squares (OLS) to estimate the regression. 

-The estVar function is based on OLS but for vectors with its own lags (autoregressive components) as explanatory variables, allowing to perform the estimation for multiple equations simultaneously, while also allows the interactive effects between equations

-The estVar_with_exo is simply the esVar function, but allows other use-specified exogenous variables for greater flexibility
