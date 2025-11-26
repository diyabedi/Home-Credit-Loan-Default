# Home-Credit-Loan-Default
The objective of this project is to explore the power of boosting methods like Gradient Boost, Extreme Gradient Boost and Light Gradient Boost. I have used the Home Credit Default Risk Dataset, where I predicted whether an applicant would repay a loan or not. This is a standard supervised classification task. 

Our best model, LightGBM, achieves a test PR-AUC of 0.2489 compared to 0.1945 for the baseline decision tree, representing a 33% improvement. Through controlled experiments on learning rate and number of estimators, we provide empirical evidence of the bias-variance trade-off and demonstrate how boosting algorithms navigate this fundamental machine learning challenge.

Key Findings:

Boosting methods improve PR-AUC by 20-35% over single decision trees
Learning rates between 0.05-0.1 provide optimal bias-variance balance
Early stopping prevents overfitting by identifying the optimal iteration count
LightGBM provides 1.2X training speedup over XGBoost with comparable accuracy
