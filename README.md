# Titanic Survival Prediction using Logistic Regression

This project builds a machine learning model to predict passenger survival on the Titanic dataset using **Logistic Regression**.  
It also compares two different **missing value imputation techniques**:
- KNN Imputer
- Simple Imputer (Mean strategy)

---

## 📌 Project Overview

The goal of this project is to:
- Handle missing values effectively
- Train a classification model
- Compare model performance based on imputation methods

The model is evaluated using **accuracy score**.

---

## 📂 Dataset

- **Source**: Titanic Dataset
- **Features Used**:
  - `Age`
  - `Pclass`
  - `Fare`
- **Target Variable**:
  - `Survived` (0 = No, 1 = Yes)

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn

---

## 🔄 Workflow

1. Load and select required columns from dataset
2. Check percentage of missing values
3. Split data into training and testing sets
4. Apply data imputation
5. Train Logistic Regression model
6. Evaluate and compare accuracy

---

## ⚙️ Model Training

### 1️⃣ KNN Imputer
- `n_neighbors = 3`
- `weights = distance`

**Accuracy Achieved:**  
`≈ 70.39%`

### 2️⃣ Simple Imputer (Mean Strategy)

**Accuracy Achieved:**  
`≈ 69.27%`

---

## 📊 Results Comparison

| Imputation Method | Accuracy |
|------------------|----------|
| KNN Imputer      | 70.39%   |
| Simple Imputer   | 69.27%   |

✅ **KNN Imputer performed slightly better** than Simple Imputer.

---

## 🚀 How to Run the Project

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
