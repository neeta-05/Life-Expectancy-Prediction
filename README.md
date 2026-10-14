# 🌍 Life Expectancy Prediction using Machine Learning

An end-to-end Machine Learning project that predicts **life expectancy** using socioeconomic and health-related indicators from the **WHO Life Expectancy Dataset**.

The project demonstrates the complete machine learning workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, model training, evaluation, and feature importance analysis.

---

## 📌 Project Overview

Life expectancy is a key indicator of a country's overall health and development. It is influenced by factors such as healthcare, education, economic conditions, mortality rates, immunization, and lifestyle.

This project applies multiple regression algorithms to predict life expectancy and identify the factors that have the greatest impact on population health.

---

## 🎯 Objectives

- Predict life expectancy using machine learning techniques.
- Clean and preprocess real-world health data.
- Perform exploratory data analysis (EDA).
- Compare multiple regression models.
- Evaluate model performance using standard regression metrics.
- Identify the most influential features affecting life expectancy.

---

## 📂 Dataset Information

**Dataset:** WHO Life Expectancy Dataset

### Dataset Summary

| Attribute | Value |
|-----------|------:|
| Total Records | **2,938** |
| Records after Cleaning | **2,928** |
| Total Features | **22** |
| Target Variable | **Life Expectancy** |
| Problem Type | Regression |

The dataset contains health and socioeconomic indicators including:

- Country
- Year
- Adult Mortality
- Infant Deaths
- Alcohol Consumption
- BMI
- GDP
- Population
- Schooling
- HIV/AIDS
- Immunization Coverage
- Income Composition of Resources
- Status (Developed / Developing)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 🔄 Project Workflow

```
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Feature Importance Analysis
```

---

## 📊 Exploratory Data Analysis

The project includes:

- Data Quality Assessment
- Missing Value Analysis
- Distribution of Life Expectancy
- Developed vs Developing Country Comparison
- Feature Distribution Analysis
- Correlation Heatmap
- Scatter Plot Analysis

---

## 🤖 Machine Learning Models

The following regression models were trained and evaluated:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

---

## 📈 Model Performance

| Model | R² Score | MAE (Years) | RMSE (Years) |
|--------|---------:|------------:|-------------:|
| **XGBoost** | **0.967** | **1.101** | **1.678** |
| **Random Forest** | **0.965** | **1.076** | **1.743** |
| **Linear Regression** | **0.836** | **2.859** | **3.762** |

**Best Overall Model:** **XGBoost**

XGBoost achieved the highest R² score and the lowest RMSE, while Random Forest produced a slightly lower MAE. Overall, XGBoost provided the strongest predictive performance on the test dataset.

---

## 🔍 Feature Importance

The most influential features identified by the ensemble models include:

- HIV/AIDS
- Income Composition of Resources
- Adult Mortality
- Schooling
- Under-five Deaths
- BMI

---

## 💡 Key Insights

- Higher schooling levels are generally associated with increased life expectancy.
- Adult mortality has a strong negative relationship with life expectancy.
- HIV/AIDS is one of the most influential predictors in the trained models.
- Developed countries generally exhibit higher life expectancy than developing countries.
- Ensemble learning methods significantly outperform Linear Regression for this dataset.

---

## 📁 Repository Structure

```
Life-Expectancy-Prediction/
│
├── data/
│   └── Life Expectancy Data.csv
│
├── notebook/
│   └── life_expectancy_prediction.ipynb
│
├── images/
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## 🚀 Installation

```bash
git clone https://github.com/neeta-05/Life-Expectancy-Prediction.git

cd Life-Expectancy-Prediction

pip install -r requirements.txt

jupyter notebook
```

---

## 🔮 Future Improvements

- Hyperparameter tuning
- Cross-validation
- SHAP-based model explainability
- Streamlit deployment
- Interactive prediction dashboard

---

## 👩‍💻 Author

**Neeta Sharma**

B.Sc. Data Science & Big Data Analytics

MIT World Peace University 2025

GitHub: https://github.com/neeta-05
