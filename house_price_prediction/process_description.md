# House Prices - Advanced Regression Techniques
Developed a **data-centric** solution for predicting house prices in the Kaggle competition, employing a comprehensive approach to data cleaning, feature engineering, and model selection. The resulting **Root Mean Square Error (RMSE) of 0.12174**, placing in the **top 6%**, demonstrates the effectiveness of the applied techniques
### 1. Data Cleaning
- **Handled missing values** in both categorical and numerical features using a combination of techniques.
- Utilized the **K-Nearest Neighbors (KNN)** Imputer for numerical features, training the model on non-null data and predicting missing values based on the nearest neighbors. 
### 2. Feature engineering
- Applied **feature engineering** techniques to enhance the predictive power of the model, by creating new features.
### 3. Feature Transformation:
- Utilized log transformations to address skewed data, promoting a more **normalized distribution**.
- Employed **one-hot encoding** for categorical variables and standardized features using **StandardScaler** for consistent scaling.
### 4. Model Selection and Training:
- Employed **PyCaret** for regression **model comparison**, identifying CatBoost as the optimal choice based on performance metrics.
- Trained a CatBoostRegressor model and achieved a final RMSE score of 0.12174.
### 5. Ensemble Modeling:
- Expanded the predictive power by creating an **ensemble** of various models, including GradientBoosting, ExtraTrees, RandomForest, LightGBM, and XGBoost.