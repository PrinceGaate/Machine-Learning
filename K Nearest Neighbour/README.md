# 🧠 K-Nearest Neighbors (KNN) Classifier

This project demonstrates how to implement a **K-Nearest Neighbors (KNN)** classifier to predict whether a user purchases a product based on social network advertisement data.

---

## 📂 Dataset Used

- **Filename:** `Social_Network_Ads.csv`
- **Features Used:**
  - `Age`
  - `EstimatedSalary`
- **Target Variable:** `Purchased`

---

## ⚙️ Project Workflow

1. **Data Preprocessing**
   - Handled missing values (if any)
   - Label encoding (if needed)
   - Feature Scaling using `StandardScaler`

2. **Model Training**
   - Implemented KNN using `sklearn.neighbors.KNeighborsClassifier`
   - Splitting data into train/test sets

3. **Prediction & Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

4. **📉 Visualizations**
   - Decision boundary plots
   - Scatter plot of predictions
   - Model performance metrics

---

## 🔍 Key Results

- **Best accuracy achieved**: _~XX%_ *(Replace with actual value from output)*
- **Optimal K value**: _K = X_

---

## 📎 Requirements

- Python ≥ 3.7  
- Libraries:
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn

---

## 📊 Graphical Outputs Included

- Decision boundary (Train & Test sets)
- Confusion Matrix Heatmap
- Accuracy Comparison (if applicable)

---

## ✅ Conclusion

The KNN model provides a simple yet effective classification approach when the right value of `K` and scaling is applied.
