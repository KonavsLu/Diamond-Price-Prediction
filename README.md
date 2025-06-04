# Diamond-Price-Prediction

This project focuses on predicting diamond prices based on their physical attributes using various machine learning models. Throughout the process, data preprocessing, feature engineering, and outlier removal techniques were applied to improve model accuracy. Multiple models—including linear regression, support vector regression, random forest, XGBoost, and a neural network—were trained and compared. The final results highlight the performance of each model, showing that ensemble and deep learning methods can provide highly accurate price estimations.


This project aims to predict diamond prices using various supervised learning algorithms. The dataset consists of over 53,940 diamond entries with features such as carat, cut, color, clarity, depth, table, and physical dimensions (x, y, z). The main objective was to build regression models that can accurately estimate the price of a diamond based on these features.

DATA : https://www.kaggle.com/datasets/shivam2503/diamonds/data

The workflow included:
- Exploratory Data Analysis (EDA) to understand data patterns and distributions.
- Outlier detection and removal using the IQR method to ensure model robustness.
- Label encoding for categorical features (cut, color, clarity).
- Training and evaluation of multiple regression models: Linear Regression, SVR, Random Forest, XGBoost, and Neural Network.
- Hyperparameter tuning using GridSearchCV where applicable.
- Performance comparison using R², RMSE, and MSE metrics.

Results showed that XGBoost outperformed other models, highlighting its strength in capturing non-linear relationships and delivering high accuracy.


📌 Conclusion
Among all the models tested, the XGBoost Regressor delivered the best performance in predicting diamond prices. It achieved an impressive R² score of 0.9830, significantly outperforming other models including Linear Regression, SVR, Random Forest, and Neural Network. This result demonstrates the strength of ensemble learning methods—especially XGBoost—in capturing complex relationships between features and target values in structured datasets.



