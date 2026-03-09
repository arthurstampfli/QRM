## Project Description

This project studies risk modeling for financial assets by building and backtesting several Value-at-Risk (VaR) and Expected Shortfall (ES) models. 

Using daily returns of AAPL, META, and JPM, we estimate different risk models, compare their performance, and evaluate their accuracy through statistical backtests.

## Models Implemented

The following risk models are implemented and compared:

- Historical Simulation
- Gaussian parametric model
- Student-t parametric model
- AR(0) – GARCH(1,1) conditional volatility model
- Filtered Historical Simulation (FHS)
- Copula-based portfolio simulation (Gaussian and Student-t copulas)

## Backtesting

The models are evaluated using several backtesting procedures:

- Kupiec Proportion-of-Failures (POF) test
- Christoffersen independence test
- Conditional coverage test
- Acerbi–Székely Z1 test for Expected Shortfall

The code is at the end of the PDF
