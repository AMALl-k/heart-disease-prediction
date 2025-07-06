
# 🫀 Heart Disease Risk Prediction using Machine Learning

This project demonstrates how to build a machine learning model to predict the presence of heart disease using patient medical records. We compare multiple models and evaluate their performance to find the best one.

---

## 📁 Dataset

The dataset used in this project is derived from the UCI Heart Disease datasets. It includes patient features such as age, chest pain type, blood pressure, cholesterol, etc. The target variable indicates the presence (`1`) or absence (`0`) of heart disease.

---

## 🧪 Models Used

- **Logistic Regression** (Baseline)
- **Random Forest Classifier**

Each model was trained, evaluated, and compared using metrics like Accuracy, Precision, Recall, F1-score, and AUC (Area Under the Curve).

---

## 🔍 Workflow Summary

1. **Data Preprocessing**
   - Handling missing values
   - One-hot encoding categorical features
   - Feature scaling using `StandardScaler`

2. **Model Training**
   - Logistic Regression
   - Random Forest

3. **Model Evaluation**
   - Confusion Matrix
   - Classification Report
   - ROC Curve
   - Accuracy, Precision, Recall, F1-score comparison

---

## 📊 ROC Curve Comparison

### Logistic Regression
![ROC - Logistic Regression](roc_logistic.png)

### Random Forest
![ROC - Random Forest](roc_random_forest.png)

---

## 📈 Model Comparison Chart

![Model Comparison](model_comparison_bar.png)

---

## ✅ Results

| Model              | Accuracy | Precision | Recall | F1-score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 79.3%   | 78%      | 87%    | 82%     |
| Random Forest       | 83.7%   | 81%      | 93%    | 86%     |

---

## 📌 Conclusion

Random Forest outperformed Logistic Regression in all metrics, making it the better model for this task. However, Logistic Regression still provides a strong baseline with interpretable results.

---

## 📁 Files

- `Heart_Disease_Model.ipynb` – Complete code in Jupyter Notebook
- `README.md` – Project overview with results
- `roc_logistic.png`, `roc_random_forest.png`, `model_comparison_bar.png` – Visual evaluation artifacts

---

## 🧠 Future Work

- Hyperparameter tuning (GridSearchCV)
- Try more models like XGBoost, SVM, or Neural Networks
- Deploy the model with a Streamlit or Flask web app

---

## 👨‍💻 Author

Amal K – MSc Artificial Intelligence  
🔗 [LinkedIn](https://www.linkedin.com/in/amal-k-ml)
