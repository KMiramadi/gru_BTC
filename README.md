GRU for predicting closing price for BTC in USD. Closing price is here defined as midnight GMT.

We predict one-day closing price of BTC using Gated Recurrent Unit, which can be thought of as a simpler version of Long-Short Term Memory networks. No external features are used here.

The prediction error it terms of MAPE is around 25% and RMSE $17962. We use a Bayesian Optimizer to find hyperparameters. 

Everything is built using Tensorflow
