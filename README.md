# Minimum Variance Portfolio

This project analyzes a diversified asset universe and constructs a minimum variance portfolio and a tangency portfolio (market protfolio) using historical daily returns.

## Assets
COST, GLD, TSM, VNQ, VXUS, XLE, XLU, XLV

## Methods
- Daily return, expected return, and variance calculation
- Covariance matrix estimation
- Minimum variance portfolio construction
- Market portfolio construction
- Backtesting over the last 3 months

## Backtest Results (Last 3 Months)
The figure below compares the mean daily return and standard deviation of the individual assets, the minimum variance portfolio, and the market portfolio over the most recent 3-month period. The black point represents the risk-free asset, assumed to have an annual return of 4%. The line connecting the risk-free asset and the market portfolio is the Capital Market Line (CML), which illustrates the set of achievable risk-return combinations formed by combining the risk-free asset with the market portfolio. This figure provides a visual summary of the trade-off between risk and return.

![Expected Return vs Standard Deviation](Expected_Return_vs_Standard_Deviation.png)
