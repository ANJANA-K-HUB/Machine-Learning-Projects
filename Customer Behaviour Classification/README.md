# Customer Behavior Classification Using Machine Learning

##  Project Overview

Customer Behavior Classification is a machine learning project that predicts whether a customer is likely to purchase a product based on demographic and financial attributes such as **Age**, **Estimated Salary**, and **Gender**. The project demonstrates the complete machine learning workflow, from data preprocessing and model training to deployment using a graphical user interface (GUI).

The goal of this project is to assist businesses in understanding customer purchasing patterns and making data-driven marketing decisions.

---

## Objectives

* To analyze customer data and identify patterns in purchasing behavior
* To build a supervised machine learning classification model
* To preprocess and scale data for better model performance
* To integrate the trained model with a user-friendly GUI
* To provide real-time predictions based on user input

---

## Technologies Used

* **Programming Language:** Python
* **Libraries:** NumPy, Pandas, Scikit-learn
* **GUI Framework:** Tkinter
* **ML Algorithms:** Logistic Regression / SVM / Decision Tree
* **Tools:** Jupyter Notebook, Python IDE

---

## Dataset Description

The dataset contains customer-related information with the following features:

* **Age:** Age of the customer
* **Estimated Salary:** Approximate annual income
* **Gender:** Male / Female (encoded numerically)
* **Purchased:** Target variable indicating purchase decision (0 = Not Purchased, 1 = Purchased)

---

## Machine Learning Workflow

1. Data loading and exploration
2. Data preprocessing (encoding and feature scaling)
3. Train-test data splitting
4. Model training and evaluation
5. Saving the trained model and scaler
6. GUI integration for real-time prediction

---

## GUI Functionality

The Tkinter-based GUI allows users to:

* Enter customer age and estimated salary
* Select gender using radio buttons
* Click a button to get instant prediction results
* View the output as **Purchased** or **Not Purchased**

---

## Results and Performance

* The model achieves good accuracy on test data when proper preprocessing is applied
* Feature scaling improves convergence and prediction stability
* Predictions are consistent when training and inference pipelines match

*(Exact accuracy may vary depending on the algorithm and dataset split)*

---

## Observations

* Age and estimated salary significantly influence purchasing behavior
* Feature scaling is essential for models sensitive to numerical ranges
* Consistent feature encoding and ordering are critical for correct predictions
* Imbalanced datasets can cause biased predictions toward one class
* GUI integration emphasizes the importance of input validation
* The model generalizes well when trained with a proper train-test split
* Small preprocessing mismatches can lead to major prediction errors

---

## Learning Outcomes

* Understanding of supervised machine learning classification problems
* Practical experience with data preprocessing and feature scaling
* Knowledge of training and evaluating ML models using scikit-learn
* Ability to integrate ML models with real-world applications
* Improved debugging and problem-solving skills
* Experience in building end-to-end ML projects

---

## Applications

* Targeted marketing and advertising
* Customer segmentation
* Sales prediction and forecasting
* Business decision support systems

---

## Future Enhancements

* Add more customer features for improved prediction accuracy
* Use advanced models like Random Forest or XGBoost
* Display prediction probability along with the result
* Deploy the application as a web app using Flask or Streamlit
* Connect the system to a live database

---

## Conclusion

This project demonstrates how machine learning can be effectively used to classify customer behavior and support business decision-making. By combining data preprocessing, model training, and GUI integration, the project provides a practical example of deploying machine learning solutions in real-world scenarios.

---


