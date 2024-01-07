# Predicting Airbnb Rental Prices: A Data-Driven Approach
This repository is the home of an extensive data science project titled "Predicting Airbnb Rental Prices using Statistical Learning." This project employs various statistical learning methods to predict Airbnb rental prices, with a case study focusing on listings for Austin, Texas.

## Project Overview
The goal of this research is to apply different statistical models to predict the minimum price of Airbnb rentals with high accuracy. The study aims to identify key factors that significantly impact rental pricing and evaluate the efficacy of each statistical method.

## Objectives
1. To determine which machine learning models most accurately predict rental prices and how these models vary in accuracy.
2. To identify significant variables within the Airbnb dataset that affect pricing.

## Data Collection
Data was compiled by collecting quarterly updates throughout the year 2022, capturing seasonal variations to provide a more accurate picture of the Airbnb market. Sources include Inside Airbnb and other referenced materials.

## Methodology
The project utilizes a variety of statistical learning techniques, including:
1. Linear Regression
2. Polynomial Regression
3. Spline Regression
4. Bagging
5. XGBoost
6. Random Forest

Each model's performance is evaluated using R-square values and the Root Mean Square Error (RMSE).

## Analysis & Results
1. Random Forest emerged as the best-performing model with the highest R-square (0.64) and the lowest RMSE (0.52).
2. XGBoost also performed well, indicating the importance of regularization techniques and ensemble learning.
3. The study revealed that room type, number of reviews, and listing count are among the most important factors in determining Airbnb prices.

## Key Findings
1. The Random Forest model is recommended for the dataset, given its superior predictive performance.
2. Significant predictors were identified, which can inform hosts about the most influential factors for pricing their listings.

## Future Work
1. To enhance prediction accuracy, we propose the integration of neural networks and the inclusion of more data to capture seasonal variations.
2. Economic indicators such as demand and supply dynamics could also be factored into the models to increase their predictive capability.

## Repository Contents
1. Research Paper: Full documentation of the project including methodology, analysis, and conclusions.
2. Data: The dataset used for model training and testing.
3. Scripts: R scripts for statistical analysis and model building.





