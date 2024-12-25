### Newspaper Vendor Model Optimization

This project explores an enhanced optimization framework for production and pricing decisions using the **Newsvendor Model (NVM)**. The traditional NVM assumes consistent demand, which often fails in dynamic markets. Our advanced model integrates **data-driven approaches** such as regression analysis, Quadratic Programming (QP), and bootstrapping to address these limitations.

#### Key Highlights:
- **Exploratory Data Analysis**: Analyzed demand patterns and price elasticity, observing significant variability and price sensitivity.
- **Regression Modeling**: Built a linear regression model to estimate baseline demand and quantify price-demand sensitivity.
- **Baseline NVM Optimization**: Implemented linear programming to optimize production quantity for fixed pricing.
- **Extensions**:
  - **Extension 1**: Optimized production quantities under uncertain demand using linear programming with enhanced constraints.
  - **Extension 2**: Jointly optimized price and production quantity using Quadratic Constrained Programming (QCP).
- **Bootstrapping for Sensitivity Analysis**: Assessed the robustness of the model by generating multiple demand scenarios and recalculating optimal solutions.

#### Results:
- Optimal production quantities: ~500–550 units across demand scenarios.
- Optimal pricing: $0.94–$0.96.
- Projected profits: Stable range of $230–$250 across simulations.
- Improved operational flexibility and profitability compared to the traditional NVM.

#### Tools & Technologies:
- Python (Pandas, NumPy, Matplotlib)
- Gurobi Optimizer
- Linear and Quadratic Programming techniques

#### Future Scope:
- Integrating machine learning for demand prediction.
- Incorporating additional cost factors like storage and logistics.
- Exploring edge cases and disruption scenarios for robust decision-making.
