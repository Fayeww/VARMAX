# Short-term Prediction of Multiple Stocks Prices


## Model

The model chosen for this prediction is the VARMAX model. It is the go-to model for multivariate time series. The VARMAX model adds a moving average component to the VAR model and can include external, or exogenous, variables as well. The components in the VARMAX model are:

- **V** for vector, indicating that it’s a multivariate model
- **AR** for autoregression
- **MA** for moving average
- **X** for the use of exogenous variables (in addition to the endogenous variables)
