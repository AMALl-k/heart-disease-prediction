
# 🫀 AI-Powered Heart Disease Prediction Tool

This project uses machine learning to predict the likelihood of heart disease based on clinical and physiological patient data. It demonstrates the power of interpretable and high-performance models to assist in early medical diagnosis.

---

## 📁 Dataset

The dataset is from the [UCI Heart Disease Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease), containing 920 patient records and attributes like age, chest pain type, cholesterol, and ECG results.

---

## 💻 Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🔍 ML Models Trained

| Model               | Accuracy | Precision | Recall | F1 Score | AUC  |
|--------------------|----------|-----------|--------|----------|------|
| Logistic Regression| 79.3%    | 78%       | 87%    | 82%      | 0.90 |
| Random Forest       | 83.7% ✅ | 81%       | 93% ✅ | 86% ✅   | 0.90 |

✅ **Random Forest** performed the best in most metrics.

---

## 📊 Key Features

- Cleaned and preprocessed medical dataset
- One-hot encoding and feature scaling
- Two ML models trained and evaluated
- ROC Curve comparison
- Fully documented notebook for reproducibility

---

## 🚀 How to Run

1. Clone the repository  
2. Open the notebook `Heart_Disease_Model.ipynb` in Jupyter  
3. Run all cells to train models and view evaluations

---

## 📁 Files Included

- `Heart_Disease_Model.ipynb`: Main notebook
- `heart_disease_uci.csv`: Cleaned dataset
- `README.md`: This file

---

## 📌 Author

This project was built by an AI enthusiast aiming to apply machine learning to real-world medical challenges. Perfect for academic or portfolio use.

---
