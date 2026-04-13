# DCC-GNGARCH_coding

This repository includes the codes used for the simulation and implementation of the paper: A new implementation of Network GARCH Model for stock volatility and co-volatility forecasting, all plots and parameter fitting results are included in these notebook files, and stock data are downloaded from Yahoo Finance (https://finance.yahoo.com/markets/stocks/most-active/), using `yfinance` directly in Python.

Specifically, 'Model simulation and parameter fitting.ipynb' is the file for the reproduction of Section 3: GNGARCH Model Specification and Simulation; codes for Section 4 are all in the form as (networkname_network_construction), for carrying robustness checks under alternative network constructions, different proxy choices, error specifications and sparsity levels, and the 'Appendix.ipynb' is the file for Appendix. Note that some figures and tables containing the parameter fitting results come from the other two .ipynb files.

These files also allow you to test the model with different settings. For example, you can choose different random seeds (rather than default 0) in 'Model simulation and parameter fitting.ipynb' for model simulaiton, and examine the model conditional variance and covariance among different stocks (rather than default NVDA) in any related codes for Section 4, by just changing corresponding variables in the respective functions.

Hope you can use the codes successfully to see the necessary figures and parameter fitting results. If there are any unclarity please email: peiyi.zhou21@imperial.ac.uk, or ucakpz0@ucl.ac.uk.
