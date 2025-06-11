# 📊 Multiple Linear Regression: Predicting Advertising Sales

This project showcases how Multiple Linear Regression can be used to predict **Sales** based on advertising spending across **TV**, **Radio**, and **Newspaper** platforms.

---

## 🧠 Project Description

This notebook demonstrates a hands-on application of **Multiple Linear Regression** using the `advertising.csv` dataset. We predict sales using three independent variables: TV, Radio, and Newspaper advertisement budgets. We also evaluate the model manually and visually for performance comparison.

---

## 📁 Dataset Description

The dataset contains 200 rows and 4 columns:

| Feature     | Description                                   |
|-------------|-----------------------------------------------|
| `TV`        | Advertising budget spent on TV (in thousands) |
| `Radio`     | Advertising budget spent on Radio             |
| `Newspaper` | Advertising budget spent on Newspaper         |
| `Sales`     | Product sales (target variable)               |

---

## ✅ What This Notebook Covers

- 📌 Data Inspection & Cleaning
- 📊 Exploratory Data Analysis (EDA)
- 🔢 Multiple Linear Regression using `sklearn`
- ✍️ Manual prediction using learned coefficients
- 🧮 Evaluation Metrics: R² Score, MAE, MSE, RMSE
- 📉 Visualizations for model interpretation

---

## 📈 Visualizations

Below are the key visualizations added for clarity:

### 1. Actual vs Predicted Sales
Visualizes how closely predicted values align with actual values.

![Actual vs Predicted](images/actual_vs_pred.png)

---

### 2. Single Prediction Comparison
Shows predicted vs actual value for one test case.

![Single Prediction](images/single_pred_bar.png)

---

### 3. Residual Distribution
Displays the distribution of prediction errors.

![Residual Distribution](images/residual_hist.png)

---

## 📏 Model Evaluation

| Metric | Value | Description |
|--------|-------|-------------|
| **R² Score** | `≈ 0.89` | How much variance is explained by the model |
| **MAE**      | — | Average magnitude of error |
| **MSE**      | — | Squared average error |
| **RMSE**     | — | Root of MSE, more interpretable |

*(Replace with your actual metric values once calculated)*

---

## 🚀 What You'll Learn

- Practical application of Multiple Linear Regression
- Feature importance interpretation from coefficients
- Manual vs automated prediction comparison
- Visual debugging of model performance

---

## 📂 Recommended Directory Structure

```
/Multiple-Linear-Regression/
│
├── Multiple_LInear_Regression.ipynb
├── advertising.csv
├── README.md
├── images/
│   ├── actual_vs_pred.png
│   ├── single_pred_bar.png
│   └── residual_hist.png
```

---

## 🪜 Next Steps

- ✅ Upload **Simple Linear Regression** (with both sklearn and scratch implementation)
- 🔜 Add more algorithms: Polynomial, Ridge, Lasso, etc.
- 📱 Deploy using **Streamlit** or **Flask**
- 🧪 Add test cases and improve production-readiness

---

## 📌 Author

Prince Gaate – sharing DS/ML learning journey through code + explanation.  
Follow the repo to watch the learning series grow!

---