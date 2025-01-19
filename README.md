# AQ_and_Health_Impact_Analysis
Air pollution poses a significant threat to public health, contributing to respiratory and cardiovascular illnesses and increased hospital admissions. This project aims to analyze air quality data and predict its health impacts using advanced statistical and machine learning techniques. Through Exploratory Data Analysis (EDA), we uncover patterns and correlations, while predictive modeling allows for accurate forecasting of health impact scores, offering actionable insights for policymakers, healthcare providers, and environmental agencies.
•	Dataset Source: The dataset used for this project is the Air Quality and Health Impacts dataset, sourced from Kaggle.
Model Selection
The following models were implemented:
1.	Linear Regression
2.	ElasticNet
3.	Decision Tree
4.	Random Forest
5.	Support Vector Regression (SVR)
6.	K-Nearest Neighbors (KNN)
7.	LightGBM
Training and Testing
•	Dataset split: 80% training, 20% testing.
•	All models trained using scaled features for consistency.
![image](https://github.com/user-attachments/assets/239776bb-991b-47bd-898f-1ec9c00f60b5)

Results Summary
•	Light GBM was the best-performing model, with an RMSE of 2.37 and an R² of 0.96, indicating that it explained 96% of the variance in the health impact score.
•	Random Forest also performed well but slightly overfit compared to Light GBM.
•	Linear models like ElasticNet and Linear Regression struggled to capture non-linear relationships in the data.
