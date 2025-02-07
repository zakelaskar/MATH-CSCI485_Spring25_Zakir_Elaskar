Readme
This project focuses on feature selection on the Diabetes dataset using Recursive Feature Elimination (RFE) with a Linear Regression model to identify the most relevant features for predicting disease progression.

Steps Performed

Dataset Exploration - Loaded the Diabetes dataset, analyzed features, and split data (80% training, 20% testing).
Linear Regression Model - Trained and evaluated a model using R² score.
Recursive Feature Elimination (RFE) - Iteratively removed features, tracked R² score, and visualized results.
Feature Importance Analysis - Identified key features, compared rankings, and analyzed their significance.
Reflection & Insights - Compared RFE with LASSO, interpreted selected features, and derived dataset insights.
Results • Top 3 Features: S1 (931.49), S5 (736.20), BMI (542.43) – key indicators of diabetes progression. • Feature Ranking: Initial ranking highlighted BMI, S5, and S1 as most important. • Final Selection: All features were retained, but S1, S5, and BMI had the highest impact. • Key Takeaways: RFE effectively identified crucial predictors, aligning with medical insights, and provided better interpretability than LASSO.
