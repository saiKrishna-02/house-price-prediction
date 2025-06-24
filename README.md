# house-price-prediction
Machine learning model to predict house prices using Python.
# 🏠 House Price Prediction using Machine Learning

This project predicts house prices using various regression algorithms and optimizes their performance using **GridSearchCV**. The model is trained and tested on a dataset with various features influencing house prices.

---

## 🔍 Project Overview

The goal of this project is to explore multiple regression models and determine the best-performing one using **GridSearchCV** for hyperparameter tuning. The models evaluated include:

- **Linear Regression**
- **Lasso Regression**
- **Decision Tree Regressor**

The performance of each model is compared based on cross-validation scores.

---

## 📊 Best Model Comparison

| Model              | Best Score (R²) | Best Parameters |
|--------------------|-----------------|------------------|
| Linear Regression  | 0.8478          | `{}`             |
| Lasso Regression   | 0.7269          | `{'alpha': 2, 'selection': 'random'}` |
| Decision Tree      | 0.7131          | `{'criterion': 'friedman_mse', 'splitter': 'best'}` |

✅ **Linear Regression** performed the best with an R² score of **0.8478**.

---

## 🧠 Algorithms Used

### 1. **Linear Regression**
- Baseline model for comparison
- No hyperparameters were tuned

### 2. **Lasso Regression**
- Adds L1 regularization
- Tuned parameters: `alpha`, `selection`

### 3. **Decision Tree Regressor**
- Captures non-linear relationships
- Tuned parameters: `criterion`, `splitter`

---

## 🧪 Tools & Libraries

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn (sklearn)**
- **Matplotlib / Seaborn** (if used for visualization)
- **Google Colab** (development environment)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/saiKrishna-02/house-price-prediction
   cd house-price-prediction
