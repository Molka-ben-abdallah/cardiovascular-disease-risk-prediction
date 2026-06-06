# 🫀 Cardiovascular Disease Risk Prediction

A complete machine learning pipeline to predict cardiovascular disease (CVD) risk using a dataset of 308,000+ patients.

## 📌 Project Overview

This project covers the full ML workflow:
- Data cleaning and preprocessing
- Categorical encoding and outlier treatment
- Class imbalance handling with SMOTE
- Training and evaluation of 5 classification models
- Cross-validation and threshold tuning for medical use

## 📂 Dataset

- **Source**: https://www.kaggle.com/datasets/harshwardhanfartale/cardiovascular-disease-risk-prediction-dataset
- **Size**: 308,854 rows × 19 columns
- **Target variable**: `Heart_Disease` (binary: 0 = No, 1 = Yes)

## 🧪 Models Trained

| Model | Description |
|-------|-------------|
| Logistic Regression | Baseline linear model |
| Decision Tree | Non-linear, interpretable |
| Random Forest | Ensemble, robust |
| Naive Bayes | Probabilistic, fast |
| Gradient Boosting | Sequential ensemble |

## 📊 Evaluation Metrics

- Accuracy, Precision, Recall, F1-Score
- ROC Curve & AUC Score
- Confusion Matrix
- Cross-validation (K-Fold & Stratified K-Fold)
- Threshold tuning (optimized for medical recall)

## ⚙️ How to Run

1. Clone the repository:
```bash
   git clone https://github.com/YOUR_USERNAME/cardiovascular-disease-risk-prediction.git
   cd cardiovascular-disease-risk-prediction
```

2. Install dependencies:
```bash
   pip install -r requirements.txt
```

3. Place `CVD_cleaned.csv` in the project folder.

4. Open the notebook:
```bash
   jupyter notebook Cardiovascular_Disease_Risk_Prediction.ipynb
```

## 📦 Dependencies

pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
jupyter

## 👩‍💻 Author

**Molka** — Master's student in Data Science  
https://github.com/Molka-ben-abdallah

## 📜 License

This project is for educational purposes.
