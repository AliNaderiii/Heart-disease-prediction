# Heart Disease Prediction | Clinical ML Portfolio

<img width="796" height="400" alt="dataset-cover" src="https://github.com/user-attachments/assets/5736bd06-f9d7-4957-985e-b25ad1e4f388" />

**Advanced Machine Learning pipeline for early detection of cardiovascular disease using the UCI Cleveland Heart Disease Dataset.**

---

## 🌟 Highlights

- **High-Recall Focus**: Optimized for minimizing false negatives (critical in clinical settings)
- **Rigorous Statistical EDA**: Mann-Whitney U, Chi-Square, Q-Q plots, VIF analysis
- **Zero Data Leakage**: Strict `ColumnTransformer` + Pipeline architecture
- **Advanced Ensembling**: Stacking Classifier + Voting + Hyperparameter tuning with GridSearchCV
- **Interactive Diagnostic Simulator** in the portfolio dashboard
- **Clinical-grade Documentation**

---

## 📊 Project Overview

This project builds a robust Clinical Decision Support System (CDSS) prototype capable of predicting the presence of heart disease based on 13 clinical features. Special emphasis was placed on statistical validity, interpretability, and prevention of common ML pitfalls in healthcare.

**Key Performance Goals Achieved:**
- High **Recall** to avoid missing at-risk patients
- Strong AUC-ROC and Precision-Recall curves
- Interpretable feature importance analysis

---

## 🛠️ Tech Stack

- **Core**: Python, scikit-learn, pandas, numpy
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Modeling**: XGBoost, Random Forest, SVM, Stacking Ensemble
- **Evaluation**: Stratified K-Fold, GridSearchCV
- **Frontend**: Interactive HTML Dashboard

---

## 📁 Project Structure

- `notebooks/` → Main Jupyter Notebooks (EDA + Modeling)
- `assets/` → Screenshots and visualizations
- `Heart_Disease_Portfolio.html` → Main interactive portfolio

---

## 🚀 Demo

**[View Live Portfolio Dashboard →](Heart_Disease_Portfolio.html)**

Try the **Interactive Risk Simulator** directly in the HTML file.

---

## 📈 Results Summary

- Dataset: 303 patients, 13 clinical features
- Best Model: Stacking Ensemble / Logistic Regression Meta-Learner
- Strong performance on key clinical metrics (Resting ECG, ST Depression, Max HR, etc.)

---

## 🧪 How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction

# Open the main dashboard
open Heart_Disease_Portfolio.html
