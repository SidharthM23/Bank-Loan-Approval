# 🏦 Bank Loan Approval – Predictive Modeling Project

This project focuses on building a machine learning pipeline to predict personal loan approval based on customer demographic and financial data.

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)
![scikit-learn](https://img.shields.io/badge/ML-Scikit--Learn-yellow?logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/Model-XGBoost-brightgreen?logo=data)

---

## 🔍 Key Highlights
- Comprehensive **EDA** and outlier detection with reusable helper functions
- Addressed **multicollinearity** using Variance Inflation Factor (VIF)
- Evaluated multiple ML models using **Repeated K-Fold Cross-Validation**
- Hyperparameter tuning with **GridSearchCV** (recall-focused)
- Compared model performance **before vs after** feature reduction
- Final model: **XGBoost Classifier** with strong recall and precision

📈 **Business takeaway:** Income, education, and credit card usage were top predictors of loan approval.

---

## 📁 Project Structure
```bash
├── bank_loan_approval.ipynb     # Jupyter notebook with full analysis & modeling
├── README.md                    # Project overview (this file)
└── data/                        # (optional) folder for dataset or links
```

---

## 🚀 How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/bank-loan-approval.git
cd bank-loan-approval
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook bank_loan_approval.ipynb
```

---

## 📊 Models Evaluated
- Logistic Regression
- Decision Tree
- Random Forest
- Naive Bayes
- K-Nearest Neighbors
- AdaBoost
- XGBoost ✅ (Final model)
- LightGBM

---

## 📚 Future Improvements
- Add ROC-AUC and SHAP visualizations for interpretability
- Deploy as a simple Flask or Streamlit app
- Include SMOTE for class imbalance handling

---

## 👤 Author
**Sidharth Monga**  
[LinkedIn](https://www.linkedin.com/in/your-linkedin) • [GitHub](https://github.com/SidharthM23)

> Feel free to fork or contribute. Star ⭐ the repo if you found it helpful!
