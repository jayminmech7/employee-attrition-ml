# Employee Attrition Prediction using Machine Learning

This project applies machine learning techniques to predict whether an employee is likely to leave the company (attrition) based on various HR-related features. The goal is to support human resource departments with data-driven employee retention strategies.

---

## 📊 Objective

To build and evaluate classification models that can accurately predict employee attrition using demographic, performance, and workplace features.

---

## 📁 Dataset

- **Source:** HR Analytics (assumed standard attrition dataset)
- **Rows:** ~1,470 employees
- **Features:** Job Role, Monthly Income, OverTime, etc.
- **Target:** `Attrition` (Yes/No)

---

## 🛠️ Tools & Libraries

- Python
- pandas, numpy
- seaborn, matplotlib
- scikit-learn (Logistic Regression, Random Forest)
- accuracy_score, f1_score, roc_auc_score, confusion_matrix

---

## 🧪 Workflow

1. Load and clean the dataset
2. Perform Exploratory Data Analysis (EDA)
3. Encode categorical variables and scale features
4. Split data into training/testing sets
5. Train multiple ML models
6. Evaluate using Accuracy, F1, and ROC AUC

---

## 🧠 Model Results

| Metric         | Value    |
|----------------|----------|
| Accuracy       | 87%      |
| F1 Score       | 0.88     |
| ROC AUC Score  | 0.89     |

---

## ✅ Conclusion

- The Random Forest model performed best, achieving an **accuracy of 87%**, **F1 Score of 0.88**, and **ROC AUC of 0.89**.
- Key predictors of attrition include **OverTime**, **Monthly Income**, and **Job Role**.
- This analysis enables HR departments to proactively identify employees at risk of leaving and take preventive actions.

---

## 📎 Author

**Jaymin Patel**  
[GitHub Portfolio](https://jayminmech7.github.io)
