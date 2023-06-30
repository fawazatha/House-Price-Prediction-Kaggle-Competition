# House Price Prediction Kaggle Competition (top 5%)
This Jupyter notebook presents a comprehensive solution to the Kaggle competition, "House Prices: Advanced Regression Techniques." The primary objective of this competition is to develop a robust predictive model that accurately estimates the sale price of residential properties. Through extensive data exploration, preprocessing, feature engineering, and model selection, my goal is to create a high-performing model capable of providing precise predictions for house sale prices.

## Table of Contents 

## Dataset Description
The dataset used for this project is sourced from the Kaggle competition, "House Prices: Advanced Regression Techniques." It comprises a training set and a test set. The training set consists of a diverse range of houses with known sale prices, while the test set includes houses without the sale price information.

## ## Approach
My approach for solving the house price prediction problem involved the following steps:
1. Exploratory Data Analysis: I conducted a thorough analysis of the dataset to gain insights into the relationships between the features and the target variable. This involved visualizations, statistical summaries, and correlation analysis.
2. Feature Engineering: In the feature engineering phase, i employed various techniques to enhance the dataset and improve the predictive power of our models. Some of the key feature engineering steps we performed include:
Creating Derived Features: We generated new features by combining or transforming existing variables. This involved techniques such as creating interaction terms, polynomial features, or extracting meaningful information from date or text columns.
Encoding Categorical Variables: We utilized the LabelEncoder technique to convert categorical variables into numeric representations. This allowed our models to effectively utilize these variables in the predictive process.
Handling Skewed Numeric Variables: Skewed numeric variables can negatively impact the performance of regression models. To address this, we applied techniques such as Boxcox transformation or Log transformation to normalize the distributions of these variables. This helped to mitigate the effects of skewness and improve the linearity assumptions of the models.
