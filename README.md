# 🏥 WHO-Life-Expectancy 🏥 

## 🩺 Project Overview 🩺 
This project examines life expectancy data from the **World Health Organisation (WHO)** to identify key factors influencing longevity and to develop predictive linear regression models.

As part of the **Digital Futures training program**, this work combines exploratory data analysis, feature engineering, and model evaluation to build a reliable, interpretable machine learning pipeline.

## 📁 Contents 📁
| File | Description |
|------|-------------|
| `WHO_EDA.ipynb` | **Exploratory Data Analysis**: Includes data inspection, cleaning insights, correlation checks, and initial hypothesis generation. |
| `WHO_Non_Sensitive_Linear_Model.ipynb` | **Linear Model with All Features**: Builds a regression model using both sensitive and non-sensitive features to understand the full impact on life expectancy. |
| `WHO_Sensitive_Linear_Model.ipynb` | **Ethical Linear Model (Non-sensitive only)**: Constructs a model excluding sensitive columns (e.g., immunisation coverage, HIV incidents, economic status) to maintain ethical integrity and fairness in predictions. |

## ✅ Key Highlights ✅

- ✅ **Robust EDA**: Addressed missing values, data types, and outliers - visualised trends by region and year.
- ✅ **Ethical Feature Selection**: Isolated models using sensitive and non-sensitive predictors to explore model fairness.
- ✅ **Data Engineering**: One-hot encoding, feature scaling with `RobustScaler`, and transformations like log scaling for skewed features.
- ✅ **Multicollinearity Check**: Used **Variance Inflation Factor (VIF)** to identify and mitigate multicollinearity.
- ✅ **Model Performance**: Achieved an **R² of ~0.96** and balanced **RMSE** across train and test sets (~2.15), indicating strong predictive performance without overfitting.
- ✅ **Interpretable Results**: Model built using **Statsmodels** OLS for full statistical transparency (coefficients, p-values, AIC/BIC, etc.).

## 💡 Learnings 💡 
This project demonstrates how ethical considerations (e.g., removing potentially biased or sensitive variables) can be integrated into machine learning workflows without significantly compromising performance. It also reinforces the importance of proper feature engineering and model diagnostics.
