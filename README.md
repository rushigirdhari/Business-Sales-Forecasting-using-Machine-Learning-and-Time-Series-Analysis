# Business Sales Forecasting using Machine Learning

## 📌 Project Overview

This project analyzes historical business sales data and predicts future sales using Machine Learning and Time Series Analysis techniques.

### Workflow

- Data Cleaning
- Missing Value Imputation
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Time-Based Train-Test Split
- Model Training
- Sales Forecasting

## 📊 Dataset Features

- Order Date
- Sales
- Profit
- Quantity
- Discount
- Year
- Postal Code

## 🤖 Models Used

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

## ⚙️ Feature Engineering

- Year
- Month
- Day of Week
- Lag Features (1, 2, 3)
- Rolling Mean (3-period)

## 📈 Evaluation Metric

- Root Mean Squared Error (RMSE)

## 🏆 Results

| Model | RMSE | Predicted Next Sales |
|--------|--------|--------|
| Linear Regression | 2.04 × 10⁻¹⁴ | 19,385.91 |
| Random Forest | 0.1378 | 18,157.55 |
| XGBoost | 0.1433 | 18,808.16 |

### Best Performing Model

**Linear Regression** achieved the lowest RMSE on the processed dataset. However, Random Forest and XGBoost were also evaluated to compare forecasting performance and model robustness.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib
- Seaborn

## 🚀 Future Improvements

- ARIMA Forecasting
- SARIMA Forecasting
- Prophet Forecasting
- Hyperparameter Optimization
- Streamlit Deployment
- Interactive Forecast Dashboard

## 👨‍💻 Author

**Rushikesh Girdhari**

B.Tech Artificial Intelligence & Machine Learning  
Symbiosis Institute of Technology, Pune
