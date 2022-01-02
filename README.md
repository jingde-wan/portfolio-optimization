# Single-Period Stock Portfolio Optimization with Mean-Variance Analysis
In this project, we apply optimization techniques to customize the investment portfolio with multiple real-world features and constraints, including linear/fixed transaction costs, and then to maximize the expected wealth at the end of current trading period under Markowitz's Modern Portfolio Theory framwork. We consider a more complicated model based on MPT but involving more constraints including variance constraints, shortfall risk constraints, shortselling constraints, diversification constraints, as well as the budget constraints, etc. We modeled the transaction cost as the combination of linear transaction cost and fixed transaction cost, both are varied depending on the operation (buying or selling). When we eventually formulated our optimization model, we considered three optimization problems: expected end wealth maximization problem with linear but not fixed transaction cost, expected end wealth maximization problem with linear and fixed transaction cost, and finally a minimization problem with respect to the total transaction cost.
