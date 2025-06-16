# Root Cause Analysis of Medical Claims Rejections

This project explores a synthetic healthcare claims dataset to identify the root causes behind medical claim rejections and predict future claim outcomes using a decision tree classifier.

---

## Objective

To:
- Analyze patterns in claim rejections vs. approvals
- Identify top rejection reasons (e.g., missing codes, billing issues)
- Build a predictive model to classify claims as Approved or Rejected
- Highlight key features influencing rejections

---

## 🛠 Tools & Technologies

- **Python** (pandas, matplotlib, scikit-learn)
- **Google Colab** (for running notebooks online)
- **Jupyter Notebook** (initial dataset creation in JupyterLite)
- **Machine Learning**: Decision Tree Classifier

---

##  Dataset

A simulated dataset of 1,000 healthcare insurance claims was created with:
- Claim status: APPROVED or REJECTED
- Insurance type: Medicare, Medicaid, Private
- Diagnosis & Procedure codes
- Billing amounts
- Rejection reasons (only if claim was rejected)

*No real patient data was used. This dataset is fully synthetic.*

---

##  Exploratory Data Analysis

- Count of approved vs. rejected claims
- Distribution of rejection reasons
- Missing values check
- Visualizations of claim outcomes and common rejection patterns

---

##  Predictive Modeling

- Trained a **Decision Tree Classifier** to predict claim rejection
- Input features: insurance type, procedure/diagnosis code, billing amount
- Achieved strong interpretability with a **feature importance plot**

### Key Finding:
> `Billing_Amount` was the most influential factor in predicting rejection.

---

##  How to Run

1. Open [Google Colab](https://colab.research.google.com)
2. Upload the notebook and `claims_data.csv`
3. Run all cells in order
4. View model outputs and feature importance

---

