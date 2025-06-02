# Parkinson's Disease Prediction Using Machine Learning 🧠

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![XAI](https://img.shields.io/badge/Explainability-SHAP-purple)

---

## 📝 Project Overview

This repository contains a **Machine Learning pipeline** for predicting **Parkinson's Disease** based on biomedical voice measurements.  
It demonstrates:
- Data preprocessing & feature engineering.
- Model training & evaluation.
- Hyperparameter tuning using Grid Search.
- Model explainability using **SHAP**.

Inspired by the real-world challenge of early disease detection, this project aims to build **interpretable AI solutions for healthcare**.

---

## 📊 Dataset

- **Source**: [Parkinson's Disease Dataset](https://archive.ics.uci.edu/ml/datasets/parkinsons)
- **Features**: 22 biomedical voice measurements (e.g., `MDVP:Fo(Hz)`, `Jitter`, `Shimmer`, `HNR`).
- **Target**: `status` (1 = Parkinson's, 0 = Healthy).

---

## 🔥 Pipeline Overview

1. **Data Preprocessing**
   - Handling missing values (none found).
   - Outlier handling (Winsorization).
   - Skewness correction (Yeo-Johnson).
   - Feature scaling (MinMaxScaler).

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmap.
   - Distribution plots.
   - Outlier detection via boxplots.

3. **Model Building & Evaluation**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)
   - K-Nearest Neighbors (KNN)

4. **Hyperparameter Tuning**
   - GridSearchCV for SVM, Random Forest, KNN.

5. **Explainable AI (XAI)**
   - SHAP analysis to understand feature contributions.

---

## 📈 Results

| Model                   | Performance Highlights      |
|-------------------------|----------------------------|
| Logistic Regression     | Baseline Model             |
| Decision Tree           | Good interpretability       |
| Random Forest           | High accuracy, robust      |
| SVM                     | Tuned for better accuracy  |
| KNN                     | Tuned via GridSearchCV      |

---

## 🧠 Explainability (XAI)

This project integrates **SHAP** for model interpretation:
- Feature importance analysis.
- Visual explanations of predictions.
- Insights into model behavior.

---

## 🚀 Getting Started

### Clone the Repo

```bash
git clone https://github.com/your-username/Parkinsons-Disease-Prediction.git
cd Parkinsons-Disease-Prediction
