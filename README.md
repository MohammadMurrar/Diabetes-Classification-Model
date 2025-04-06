# 🩺 Diabetes Classification Model

This project builds a machine learning model to predict whether a patient has diabetes based on diagnostic health measurements. The goal is to create the best-performing model by thoroughly cleaning and preparing the dataset, building robust pipelines, and using appropriate evaluation metrics.

---

## 📁 Dataset

The dataset includes diagnostic measurements for patients and a binary outcome indicating whether the patient has diabetes. It includes numerical and categorical features that require cleaning, imputation, and transformation.

---

## ✅ Project Objectives

1. **Clean the data**
   - Validate data types and remove duplicates.
   - Address inconsistencies and extreme values.

2. **Prepare the data for modeling**
   - Implement a preprocessing pipeline to avoid data leakage.
   - Check and handle missing values using imputation (not by dropping rows).
   - Justify imputation strategies (e.g., median for numerical, constant for categorical).
   - Apply appropriate feature scaling.
   - Encode variables using suitable encoding methods.

3. **Training and evaluation**
   - Build and train ML models inside pipelines.
   - Use proper metrics (e.g., Accuracy, ROC AUC, Precision, Recall).
   - Perform model tuning to optimize performance.
   - Select and justify the final model.

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🔄 Workflow Summary

1. **Data Cleaning**
   - Checked for nulls, inconsistencies, and outliers.
   - Applied median imputation for skewed numerical columns.
   - Used constant placeholder `'NA'` for categorical values.

2. **Preprocessing**
   - Used `SimpleImputer`, `StandardScaler`, and encoding via pipeline.
   - Prevented data leakage by fitting transformations only on training data.

3. **Modeling**
   - Trained several models including Logistic Regression and Random Forest.
   - Chose the final model based on evaluation scores.

---

## 📊 Evaluation

The model was evaluated using:

- **Accuracy**
- **Classification Report**
- **ROC AUC Score**

---

## 🧠 Final Model Choice & Justification

The final model was chosen based on:
- Best balance between bias and variance.
- Strong generalization to unseen data.
- High ROC AUC and F1-Score on the test set.

---
