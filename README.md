# House Price Prediction Kaggle Competition (top 20% as a beginner)
This Jupyter notebook presents a comprehensive solution to the Kaggle competition, "House Prices: Advanced Regression Techniques." The primary objective of this competition is to develop a robust predictive model that accurately estimates the sale price of residential properties. Through extensive data exploration, preprocessing, feature engineering, and model selection, my goal is to create a high-performing model capable of providing precise predictions for house sale prices.

## Dataset Description
The dataset used for this project is sourced from the Kaggle competition, "House Prices: Advanced Regression Techniques." It comprises a training set and a test set. The training set consists of a diverse range of houses with known sale prices, while the test set includes houses without the sale price information.

## Approach
My approach for solving the house price prediction problem involved the following steps:
1. Exploratory Data Analysis: I conducted a thorough analysis of the dataset to gain insights into the relationships between the features and the target variable. This involved visualizations, statistical summaries, and correlation analysis.
2. Feature Engineering: In the feature engineering phase, i employed various techniques to enhance the dataset and improve the predictive power of our models. Some of the key feature engineering steps i performed include:
- Creating Derived Features: I generated new features by combining or transforming existing variables.
- Encoding Categorical Variables: i utilized the LabelEncoder technique to convert categorical variables into numeric representations. This allowed our models to effectively utilize these variables in the predictive process.
- Handling Skewed Numeric Variables: Skewed numeric variables can negatively impact the performance of regression models. To address this, i applied techniques such as Boxcox transformation or Log transformation to normalize the distributions of these variables. This helped to mitigate the effects of skewness and improve the linearity assumptions of the models.
3. Modeling: In the modeling phase, i explored several regression algorithms and employed hyperparameter tuning to optimize their performance. The algorithms we considered for hyperparameter tuning include:

- XGBoost: Extreme Gradient Boosting
- LightGBM: Light Gradient Boosting Machine
- Gradient Boosting Regressor (GBR)
- Lasso Regression
- ElasticNet
- Support Vector Regressor (SVR)
- Kernel Ridge Regression (KRR)

  To optimize the performance of these algorithms, i performed hyperparameter tuning using techniques such as grid search or randomized search. This involved systematically exploring different combinations of hyperparameters to identify the best configuration for each algorithm.
  In addition to individual models, i also utilized an ensemble technique called StackingRegressor. This approach involved training multiple base models and then training a meta-model on their predictions. By combining the strengths of various models, the StackingRegressor aimed to improve overall prediction accuracy.
  Finally, i blended the predictions from all the models and ensembles to create a final prediction that took advantage of the diverse modeling approaches.

## Result
In the Kaggle House Price Prediction competition, my model achieved impressive results with a RMSE score of 0.11947. This score indicates our predictions' accuracy in estimating house sales prices.
The competition evaluation metric, Root-Mean-Squared-Error (RMSE), takes into account the logarithm of the predicted and observed sales prices. This ensures that errors in predicting both expensive and cheap houses have an equal impact on the evaluation, providing a fair assessment of the model's performance. By securing an impressive position at 176 out of 4,253 participants, our approach places us in the top 5% of all submissions. This remarkable achievement showcases the effectiveness and competitiveness of our model in the highly competitive Kaggle competition.

![submission](https://github.com/fawazatha/House-Price-Prediction-Kaggle-Competition-/assets/132468764/0ff340d1-a969-4d62-81c3-28959b818950)

## Acknowledgments
I would like to thank Kaggle for providing the House Prices: Advanced Regression Techniques dataset and competition. I also acknowledge the valuable contributions of the open-source data science community and the authors of the libraries used in this project.

## Contact Information
For any questions, feedback, suggestions, or collaboration opportunities, please feel free to reach out to:
Fawwaz Atha Rohmatullah
fawazzatha@gmail.com
Linkedln: [https://www.linkedin.com/in/fawwaz-atha-rohmatullah-6ab2b2262/****](https://www.linkedin.com/in/fawwaz-atha-rohmatullah-6ab2b2262/)
I appreciate your interest in my house price prediction project and hope it provides valuable insights and serves as a useful resource for your own data science endeavors.
