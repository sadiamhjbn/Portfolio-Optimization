**Project Summary: Portfolio Optimization with Monte Carlo Simulation**

**Objective:**
The goal of this project is to optimize a financial portfolio consisting of four technology stocks (AAPL, GOOG, MSFT, AMZN) using Monte Carlo Simulation and modern portfolio theory.

**Steps:**

1. **Data Retrieval:**
   - Stock data for the selected companies is obtained from Yahoo Finance using the `yfinance` library.

2. **Data Preparation:**
   - Relevant columns (Date, Close price) are extracted, and the data is structured into a DataFrame.

3. **Portfolio Metrics Calculation:**
   - Daily log returns are calculated from the closing prices.
   - Random portfolio weights are generated, and the portfolio's expected returns, volatility, and Sharpe ratio are computed.

4. **Monte Carlo Simulation:**
   - 5000 portfolios are simulated with random weights.
   - For each portfolio, returns, volatility, and Sharpe ratio are calculated.

5. **Results Analysis:**
   - The portfolios are visualized on a scatter plot, where the x-axis represents volatility, the y-axis represents returns, and color represents the Sharpe ratio.
   - The portfolios with the maximum Sharpe ratio and minimum volatility are identified.

6. **Optimization:**
   - The project uses optimization techniques to find the portfolio with the maximum Sharpe ratio, which represents the optimal risk-adjusted return.

**Key Outputs:**
   - Visualization of portfolios on a scatter plot.
   - Identification of the portfolio with the maximum Sharpe ratio.
   - Portfolio weights and metrics for the optimized portfolio.

**Conclusion:**
   - The project demonstrates the application of Monte Carlo Simulation and optimization techniques to construct an efficient financial portfolio.
   - The optimization results provide insights into the allocation of assets for maximizing returns and managing risk.

**Future Enhancements:**
   - Include additional financial instruments for a more diverse portfolio.
   - Incorporate real-time data for more accurate predictions.
   - Implement advanced optimization algorithms for improved efficiency.
