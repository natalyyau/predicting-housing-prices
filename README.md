# Housing Price Prediction

A machine learning project that predicts housing prices in Seattle, Washington using exploratory data analysis, feature engineering, and Gradient Boosting regression.

# **About**

This project analyzes 21,613 Seattle housing records to predict property prices. The workflow includes:

- Exploratory data analysis with visualizations
- Feature engineering (log transformations, age calculations, handling multicollinearity)
- Training and comparing three regression models (Linear Regression, Decision Tree, Gradient Boosting)
- Hyperparameter tuning on the best model

**Final Model**: Gradient Boosting <br>
**Performance**: R² = 0.711, MAE = 0.223, RMSE = 0.284

# **Dataset**

**Source**: Kaggle <br>
**Size**: 21,613 observations <br>
**Features**: 21 columns including bedrooms, bathrooms, sqft_living, grade, view, condition, zipcode, etc.

# **How to Run**

1. housing_eda.ipynb - Analyze the dataset
2. housing_preprocessing.ipynb - Clean and prepare data
3. housing_modeling.ipynb - Train models
4. housing_evaluation.ipynb - Evaluate final model

# Contributors

Nataly Yau, Rose Joseph, Khushi Nanda, Tahia Islam, and Sangit Gaire
