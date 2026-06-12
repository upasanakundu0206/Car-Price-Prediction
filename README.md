# 🚗 Car Price Prediction

A machine learning project that predicts used car prices using **Random Forest Regression** and performs digit clustering using **K-Means** on the MNIST Digits dataset.

---

## 📌 Project Overview

This project is divided into two parts:

### Part 1 — Supervised Learning: Used Car Price Prediction
- Dataset: `used_cars.csv`
- Preprocessing: missing value handling, feature engineering, outlier removal, label encoding
- Model: Random Forest Regressor (100 estimators)
- Evaluation: R² Score, MSE, MAE

### Part 2 — Unsupervised Learning: MNIST Digit Clustering
- Dataset: sklearn's built-in `load_digits()`
- Model: K-Means Clustering (10 clusters)
- Evaluation: Macro-averaged F1 Score

---

## 🛠️ Libraries Used

- `pandas`, `numpy`
- `scikit-learn`
- `scipy`

---

## 📊 Results

| Metric | Value |
|---|---|
| R² Score | ~0.90+ |
| Macro F1 Score (K-Means) | ~0.86 |

---

## 👩‍💻 Author

**Upasana Kundu**  
