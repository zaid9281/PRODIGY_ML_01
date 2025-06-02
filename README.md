# PRODIGY_ML_01
# 🏠 House Price Prediction

This project uses a **Linear Regression** model to predict house prices based on features like square footage, number of bedrooms, and bathrooms. The goal is to build a simple yet effective model using a clean dataset and standard machine learning techniques.

## 📁 Files in this Repository

- `task_1_code.ipynb` – Jupyter notebook with data preprocessing, EDA, model training, and evaluation.
- `task_1_data.xlsx` – Dataset containing house features and prices.

## 🧾 Problem Statement

Predict the sale price of a house using the following features:
- **GrLivArea**: Living area (in square feet)
- **BedroomAbvGr**: Number of bedrooms above ground
- **FullBath**, **HalfBath**: Number of full and half bathrooms


---

## 📊 Workflow

1. **Data Cleaning**: Remove missing values
2. **Feature Engineering**: Combine bathroom fields
3. **EDA**: Visualize trends using scatter plots and a heatmap
4. **Modeling**: Train a linear regression model using `scikit-learn`
5. **Evaluation**: Use RMSE and R² Score to assess performance
6. **Prediction**: Generate predictions for sample inputs

---

## 📈 Example Model Output

```text
Model Performance:
RMSE: $42,345.67
R-squared: 0.82

Coefficients:
 - GrLivArea: $120.50 per sqft
 - BedroomAbvGr: $3,250.00 per bedroom
 - TotalBath: $15,800.00 per bathroom
Intercept: $32,000.00

Predicted price for 2000 sqft, 3 bed, 2.5 bath: $318,500.00

