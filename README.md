# 📈 Predicting Investment Portfolio Performance using Artificial Neural Networks (ANN)

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)

![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00?style=for-the-badge&logo=tensorflow)

![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikitlearn)

![Keras](https://img.shields.io/badge/Keras-ANN-D00000?style=for-the-badge&logo=keras)

![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

---

# 📌 Project Overview

This project demonstrates how **the same investment dataset** can solve **three different Machine Learning problems** using **Artificial Neural Networks (ANN)**.

Instead of changing the input features, only the **target variable** changes according to the business objective.

This project covers:

- 📊 Regression
- ✅ Binary Classification
- 📈 Multi-Class Classification

---

# 🏢 Business Background

FinGrow Wealth Advisors manages thousands of investment portfolios across India.

The company wants to predict investment performance using historical investor data.

Artificial Intelligence helps financial advisors make better investment decisions while reducing manual analysis.

---

# 🎯 Objectives

- Predict Annual Return (%)
- Predict High or Low Return
- Predict Low, Moderate or High Return

---

# 📂 Dataset

Dataset provided by **YBI Foundation**

https://github.com/YBIFoundation/DeepLearning/raw/main/PredictingInvestmentPortfolioPerformance.csv

Total Investors : **5000**

---

# 📊 Features

| Feature | Description |
|----------|-------------|
| Age | Investor Age |
| Income | Annual Income |
| Investment | Total Investment |
| Risk Score | Risk Appetite |
| Experience | Investment Experience |
| Market Exposure | Equity Exposure |
| Diversification | Asset Classes |
| Previous Return | Last Year's Return |

---

# 🤖 Machine Learning Tasks

## 1️⃣ Regression

Predict the exact Annual Return (%)

Output Layer

```text
Dense(1, activation="linear")
```

Loss Function

```text
Mean Squared Error
```

Evaluation

- Mean Absolute Error (MAE)

---

## 2️⃣ Binary Classification

Predict

- High Return
- Low Return

Output Layer

```text
Dense(1, activation="sigmoid")
```

Loss Function

```text
Binary Crossentropy
```

Evaluation

- Accuracy
- Precision
- Recall
- F1 Score

---

## 3️⃣ Multi-Class Classification

Predict

- Low
- Moderate
- High

Output Layer

```text
Dense(3, activation="softmax")
```

Loss Function

```text
Categorical Crossentropy
```

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- TensorFlow
- Keras
- Scikit-Learn
- Jupyter Notebook

---

# 🔄 Project Workflow

```
Import Libraries
        │
        ▼
Load Dataset
        │
        ▼
Data Exploration
        │
        ▼
Feature Selection
        │
        ▼
Train-Test Split
        │
        ▼
Feature Scaling
        │
        ▼
Build ANN Model
        │
        ▼
Train Model
        │
        ▼
Prediction
        │
        ▼
Evaluation
```

---

# 🧠 ANN Architecture

```
Input Layer (8 Features)

↓

Dense Layer (8 neurons, ReLU)

↓

Dense Layer (16 neurons, ReLU)

↓

Output Layer
```

Regression → Linear

Binary → Sigmoid

Multi-Class → Softmax

---

# 📈 Results

| Model | Evaluation Metric |
|-------|-------------------|
| Regression | Mean Absolute Error |
| Binary Classification | Accuracy |
| Multi-Class Classification | Accuracy |

---

# 📁 Repository Structure

```
Predicting-Investment-Portfolio-Performance
│
├── Predicting_Investment_Portfolio_Performance.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
└── images/
```

---

# 🚀 Future Improvements

- Hyperparameter Tuning
- Dropout Layers
- Batch Normalization
- Early Stopping
- Streamlit Deployment
- Random Forest Comparison
- XGBoost Comparison

---

# 👨‍💻 Author

**Rahul Singh**

B.Tech Computer Science Engineering

Machine Learning | Deep Learning | Data Analytics

---

## ⭐ If you found this project useful, don't forget to Star this repository.
