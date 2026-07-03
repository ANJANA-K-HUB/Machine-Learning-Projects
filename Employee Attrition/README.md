# 📊 Employee Attrition Prediction Using Machine Learning

## 🔍 Project Overview
Employee attrition is a critical challenge for organizations, leading to increased hiring costs, loss of skilled talent, and reduced productivity. This project focuses on predicting employee attrition using machine learning techniques and dimensionality reduction to help HR teams proactively identify employees who are at risk of leaving.

---

## 🎯 Objectives
- Analyze factors contributing to employee attrition  
- Perform data preprocessing and exploratory data analysis (EDA)  
- Apply dimensionality reduction using Principal Component Analysis (PCA)  
- Build and compare multiple machine learning models  
- Identify the best-performing model for attrition prediction  

---

## 📂 Dataset Description
The dataset contains employee-related information such as:
- Demographic details (Age, Gender, Marital Status)
- Job-related attributes (Department, Job Role, Overtime)
- Compensation details (Monthly Income, Salary Hike)
- Performance and satisfaction metrics (Job Satisfaction, Work-Life Balance)

**Target Variable:**  
- `Attrition` (Yes / No)

---

## 🛠️ Technologies & Tools
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Techniques Used:**  
  - Feature Scaling  
  - Principal Component Analysis (PCA)  
- **Models Implemented:**  
  - Logistic Regression  
  - Decision Tree  
  - Support Vector Machine (LinearSVC)  
  - Random Forest (with PCA)  

---

## ⚙️ Methodology

### 1️⃣ Data Preprocessing
- Checked and handled missing values
- Encoded categorical variables
- Scaled numerical features to ensure uniform contribution

**Observation:**  
Proper encoding and scaling significantly improved model stability and performance.

---

### 2️⃣ Exploratory Data Analysis (EDA)
EDA helped uncover key patterns in the data.

**Key Observations:**
- Employees working overtime had higher attrition rates
- Low job satisfaction and poor work-life balance strongly influenced attrition
- Employees with lower monthly income were more likely to leave
- Younger employees and those with fewer years at the company showed higher attrition

---

### 3️⃣ Dimensionality Reduction using PCA
- PCA was applied after feature scaling
- Reduced the number of features while retaining most of the variance (~90–95%)
- Helped eliminate multicollinearity and noise

**Observation:**  
PCA improved computational efficiency and reduced overfitting without significant loss of information.

---

### 4️⃣ Model Building
Multiple machine learning models were trained and evaluated:
- Logistic Regression
- Decision Tree
- Support Vector Machine (LinearSVC)
- **Random Forest with PCA**

Random Forest was chosen due to its ability to capture complex, non-linear relationships.

---

## 📈 Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

**Key Results:**
- Ensemble and linear models performed better than simple classifiers
- Random Forest with PCA achieved strong predictive performance
- The model maintained a good balance between precision and recall

**Business Insight:**  
High recall is important in attrition prediction, as failing to identify an at-risk employee can be costly.

---

## 🔑 Key Observations & Insights
- Employee attrition is driven more by job-related factors than demographics
- Overtime, income level, job satisfaction, and work-life balance are major contributors
- PCA helped reduce model complexity while maintaining performance
- Random Forest with PCA showed better generalization and reduced overfitting

---

## 📌 Conclusion
This project demonstrates the effective use of machine learning and dimensionality reduction techniques to predict employee attrition. The combination of PCA and Random Forest provided efficient and reliable predictions, making the solution suitable for real-world HR analytics and decision-making.

---

## 🚀 Future Enhancements
- Deploy the model using Flask or Streamlit
- Add explainability using SHAP or LIME
- Integrate real-time HR data
- Perform advanced hyperparameter tuning




