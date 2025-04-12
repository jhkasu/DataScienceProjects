# Breast Cancer Diagnosis - DS Project

This project uses logistic regression, random forest, and XGBoost to predict breast cancer diagnosis using the UCI Breast Cancer Wisconsin dataset.

## Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))  
- **Accessed via**: Kaggle (`uciml/breast-cancer-wisconsin-data`)
- **Shape**: 569 samples × 30 numeric features  
- **Target**: `diagnosis` (M = malignant, B = benign)

> **Note**:  
> This dataset has been preprocessed and cleaned by Kaggle.  
> The absence of missing values and well-scaled features makes it easy to achieve high model performance.  
> It's an excellent starting point for beginners looking to practice classification and model explainability techniques.

## Models Used

- **Logistic Regression** (AUC: 0.9912)
- **Support Vector Classifier (SVC)** (AUC: 0.9421)
- **XGBoost** (AUC: 0.9860)
- **Random Forest** (Tuned) (AUC: 0.995)

## Techniques Applied

- Exploratory Data Analysis (EDA) with correlation heatmaps
- Feature selection using Random Forest and SHAP values
- GridSearchCV for hyperparameter tuning
- SHAP explainability plots (beeswarm) for model transparency

## File

- `Breast_Cancer_Wisconsin.ipynb`: Full notebook with EDA → Preprocessing → Modeling → Evaluation

---

### Author

Jooho Kim – Data Science @ ASU  
This project is part of my data science portfolio, and is used for interview demonstration purposes.

