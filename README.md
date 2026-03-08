Car Price Prediction using Linear RegressionThis project builds a predictive model to estimate used car prices. By performing detailed Exploratory Data Analysis and categorical feature engineering, the model achieves a strong baseline performance.

📊 Performance MetricsModel:
Linear RegressionR-squared ($R^2$)
Score: 0.86
Goal: Explain 86% of the variance in car pricing based on physical and mechanical attributes.

🛠️EDA: 
The dataset was preprocessed to ensure the Linear Regression model could interpret categorical relationships effectively:
One-Hot Encoding: Applied to categorical features including Car Model, Fuel Type, and Transmission to convert them into numerical format.
Feature Selection: Included Engine Size and other numerical variables to capture mechanical influence on price.
Visualizations: Created Correlation Heatmaps to identify which features (like Year or Engine Size) had the strongest impact on Price.Used Scatter Plots and Box Plots to detect outliers and visualize price distribution across different car models.

🚀 Tech Stack
Language: Python
Data Manipulation: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Machine Learning: Scikit-Learn
