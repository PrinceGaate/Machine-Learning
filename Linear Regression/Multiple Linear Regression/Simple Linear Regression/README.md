# 📉 Simple Linear Regression – CGPA vs Placement Package

This project demonstrates how to implement **Simple Linear Regression** using Python and scikit-learn. The goal is to predict the placement package (in LPA) based on a student's CGPA using a simple and interpretable linear model.

---

## 🎯 Objective

To create a predictive model using **Simple Linear Regression** that estimates a student's placement package based on their academic performance (CGPA).

---

## 📂 Dataset

- **Filename**: `placement.csv`
- **Features**:
  - `cgpa`: Independent variable (Cumulative Grade Point Average)
  - `package`: Dependent variable (Placement Package in LPA)

---

## 🛠 Tools & Libraries

- `pandas` for data loading and handling
- `numpy` for numerical operations
- `matplotlib` & `seaborn` for data visualization
- `scikit-learn` for model building and evaluation

---

## 🧪 Workflow

1. Import necessary libraries
2. Load and explore the dataset
3. Visualize the relationship between CGPA and Package
4. Split the data into training and testing sets
5. Train the model using `LinearRegression`
6. Predict on test data
7. Evaluate model performance using:
   - MAE
   - MSE
   - RMSE
   - R² Score
8. Plot the regression line over the scatter plot

---

## 📈 Sample Code Snippet

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)

y_pred = model.predict(X_test)
```

---

## 📊 Visualization

- Scatter plot (CGPA vs Package)
- Regression line (Best-fit line)
- Optionally: residual plot, prediction plot

---

## ✅ Outcome

- A trained regression model that demonstrates a positive linear relationship between CGPA and placement package.
- Ability to make basic predictions using simple input values (e.g., CGPA = 8.5).

---

## 📌 Note

This is an educational project focused on building and visualizing a basic regression model. It is ideal for learning concepts in supervised learning and regression analysis.
