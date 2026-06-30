# NBA Player Longevity Prediction – Feature Engineering

## Overview

This project focuses on feature engineering for an NBA player longevity prediction model. Using Python and pandas, the dataset is cleaned, transformed, and prepared for machine learning by selecting relevant features, removing redundant information, handling missing values, and creating new performance-based metrics.

The objective is to predict whether an NBA player will remain in the league for at least five years (`target_5yrs`) based on their rookie season statistics.

## Project Objectives

- Define the `target_5yrs` column as the prediction target.
- Remove non-predictive features that may introduce noise or data leakage.
- Perform correlation analysis to identify and reduce multicollinearity.
- Engineer meaningful performance metrics such as Points Per Minute and Efficiency Rating.
- Handle missing values to produce a clean, model-ready dataset.
- Document all feature engineering decisions for transparency and reproducibility.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Repository Structure
├── nba_feature_engineering.ipynb
├── nba_players_feature_engineered.csv
├── README.md
└── dataset/
└── nba_players.csv

## Outcome

The final output is a cleaned and feature-engineered dataset that is ready for machine learning model development to predict NBA player career longevity.
