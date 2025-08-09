# Titanic Survival Prediction 🚢

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange.svg)
![Status](https://img.shields.io/badge/Status-Portfolio%20Project-success.svg)

A **machine learning classification** project based on the [Kaggle Titanic dataset](https://www.kaggle.com/c/titanic).  
The goal: **Predict passenger survival** using demographic and travel information through data preprocessing, exploratory analysis, and model training.

---

## 📌 Project Overview
The Titanic dataset is a well-known **binary classification** problem.  
I approached it as a portfolio project to strengthen my skills in:
- **Data cleaning & preprocessing**
- **Exploratory data analysis (EDA)**
- **Feature engineering**
- **Model selection & evaluation**

---

## 🔍 Workflow

### 1️⃣ Exploratory Data Analysis (EDA)
- Visualized survival rates by **gender**, **class**, **age**, and **embarkation port**.
- Checked for missing data and feature correlations.

### 2️⃣ Data Preprocessing
- Filled missing values for `Age` and `Embarked`.
- Encoded categorical variables (`Sex`, `Embarked`).
- Engineered new features:
  - `FamilySize` = `SibSp` + `Parch` + 1
  - `IsAlone` = Binary indicator
  - `Title` extracted from passenger names

### 3️⃣ Model Training
| Model                | Accuracy |
|----------------------|--------------------|
| Logistic Regression  |  **80.5%** |
| Random Forest        |  **79.3%** |
| Gradient Boosting    |  **79.3%** |

- Tuned hyperparameters for the best performing model.

### 4️⃣ Results
- **Best Model**: Logistic Regression (So far) 
- **Kaggle Public Leaderboard Score**: **0.76315**

---

## 🛠 Skills & Tools
**Languages & Libraries:**  
`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Scikit-learn`

**Core Skills:**  
Data wrangling · Visualization · Feature engineering · Model selection · Hyperparameter tuning

---

## 🎯 Outcome
This project improved my ability to:
- Handle **messy, real-world data**
- Create **meaningful features** from raw data
- Select and evaluate **ML models** effectively

---

> 💡 **Note:** This repository is part of my **Data Science Portfolio** and is not intended for production use.
