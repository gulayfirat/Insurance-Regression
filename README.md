#  Insurance Cost Prediction 🩺💰

This project is a machine learning regression model that predicts medical insurance charges based on demographic and health-related features.

## 📊 Dataset

- **Source:** [Kaggle] (https://www.kaggle.com/code/maverickss26/regression-modellng-using-insurance-dataset/notebook)
- **Features:**
  - `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`

## 🧹 Data Preprocessing

- Removed outliers based on `bmi` and `charges` using the IQR method
- Encoded categorical variables:
  - `sex` and `smoker`: label encoded
  - `region`: one-hot encoded

## 🤖 Models Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet Regression
- Polynomial Regression (Degree = 2)

## 📈 Model Performance

| Metric | Score |
|--------|-------|
| MAE    | 1382.86 |
| MSE    | 8,650,559.85 |
| RMSE   | 2941.18 |
| R²     | 0.66 |

> Polynomial Regression with degree 2 provided the best R² score.

## 🧠 Conclusion

A regression model was developed to predict medical insurance charges with a reasonable performance. Preprocessing and feature engineering improved the accuracy, and the final R² score reached **0.66** using polynomial regression.

