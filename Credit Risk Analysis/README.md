# 🏦 German Credit Risk Analysis


A machine learning project that predicts whether a loan applicant is a **Good** or **Bad** credit risk using the German Credit dataset. The project also applies **Principal Component Analysis (PCA)** to reduce dimensionality and improve model efficiency.

---

## 🎯 Objective

To build a classification model that evaluates credit risk, identifies key influencing factors, and explores the impact of dimensionality reduction using PCA.

---

## 📊 Dataset Overview

The dataset contains information about loan applicants, including:

- Demographic features: Age, Sex, Job
- Financial features: Checking account status, Savings account balance, Credit amount
- Loan features: Loan duration, Purpose of credit
- Asset-related features: Housing status

**Target variable:**

- Risk (Good / Bad credit)

---

## 🛠 Data Preprocessing

- Removed non-informative columns (e.g., Id)
- Applied Label Encoding to categorical features:
  - Sex
  - Housing
  - Savings account
  - Checking account
  - Risk
- Applied One-Hot Encoding to the Purpose feature
- Scaled numerical features using StandardScaler
- Maintained consistent feature ordering

---

## 📉 Dimensionality Reduction (PCA)

- Applied **Principal Component Analysis (PCA)** after feature scaling
- Reduced feature dimensionality while preserving maximum variance
- Helped minimize multicollinearity and improve computational efficiency
- Compared model performance before and after applying PCA

---

## 🤖 Model Training

A supervised machine learning classifier was trained on both:
- Original feature space
- PCA-transformed feature space

This allowed evaluation of PCA’s impact on prediction performance.

---

## 🔍 Key Features Affecting Credit Risk

The most influential factors include:

1. Checking account status
2. Credit amount
3. Loan duration
4. Savings account balance
5. Purpose of credit
6. Employment type and housing status
7. Age and gender (lower impact)

---

## 📈 Results

- Achieves moderate to strong predictive performance
- PCA reduces dimensionality with minimal loss in accuracy
- Performs better at identifying good credit applicants
- Financial behavior variables dominate credit risk prediction

---

## 🖥 Application Interface

A Tkinter-based GUI allows users to input applicant details and receive real-time credit risk predictions.

---

## ⚠ Limitations

- Label encoding introduces artificial ordering
- Dataset is slightly imbalanced
- PCA reduces interpretability of individual features
- Sensitive attributes may introduce bias

---

## 🚀 Future Improvements

- Use OneHotEncoder for categorical variables
- Implement Pipeline and ColumnTransformer
- Display prediction probabilities
- Perform fairness analysis

---

## 🏁 Conclusion

This project demonstrates how **financial behavior features** strongly influence credit risk prediction and shows that **PCA can effectively reduce dimensionality** while maintaining model performance. It highlights the importance of consistent preprocessing for reliable deployment.

