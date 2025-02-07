## Readme
This  project focuses on feature selection on the Diabetes dataset using Recursive Feature Elimination (RFE) with a Linear Regression model to identify the most relevant features for predicting disease progression.

Steps Performed
1.	Dataset Exploration - Loaded the Diabetes dataset, analyzed features, and split data (80% training, 20% testing).
2.	Linear Regression Model - Trained and evaluated a model using R² score.
3.	Recursive Feature Elimination (RFE) - Iteratively removed features, tracked R² score, and visualized results.
4.	Feature Importance Analysis - Identified key features, compared rankings, and analyzed their significance.
5.	Reflection & Insights - Compared RFE with LASSO, interpreted selected features, and derived dataset insights.

Results
•	Top 3 Features: S1 (931.49), S5 (736.20), BMI (542.43) – key indicators of diabetes progression.
•	Feature Ranking: Initial ranking highlighted BMI, S5, and S1 as most important.
•	Final Selection: All features were retained, but S1, S5, and BMI had the highest impact.
•	Key Takeaways: RFE effectively identified crucial predictors, aligning with medical insights, and provided better interpretability than LASSO.
