# Monte-Carlo-Portfolio-Optimization
This project features the following concepts:

1. **Monte Carlo Simulation**
* Instead of relying on a single static calculation, this project runs thousands of iterations with randomized asset weights. This approach uncovers a vast spectrum of risk and return profiles, providing a probability distribution of outcomes rather than a single point estimate.
* **Disclamer:**
  * These simulations assume "perfect" markets where historical averages (mean and covariance) persist.
  * Since real-world conditions fluctuate, feel free to adjust the underlying data to account for the factors that you're interested in testing.
    
2. **Efficient Frontier**
   * This is the set of optimal portfolios that offer the maximum possible expected return for any given level of risk (standard deviation). It represents the upper boundary of the investment opportunity set.
     
4. **The Global Minimum Variance Portfolio**
   * This is a unique point on the frontier representing the lowest possible risk (volatility) achievable using only risky assets. It is the "safest" possible combination in the model.
     
6. **The Optimal Portfolio.**
   * While the Efficient Frontier provides a range of efficient options, the Optimal Portfolio is the specific combination of assets that maximizes the Sharpe Ratio (the best risk-adjusted return).
     
8. **Capital Market Line (CML)**
   * It shows the risk/return profiles of portfolios that optimally combine a risk-free asset and the market portfolio
   * In advanced theory (incorporating a risk-free rate), the Optimal Portfolio is found where the Capital Allocation Line (CAL) is exactly tangent to the Efficient Frontier.
