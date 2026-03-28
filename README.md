# California Housing Price Prediction (ML Project)

# Objective
Build and evaluate a Linear Regression model using the California Housing dataset to understand the complete Machine Learning workflow.

# Workflow
- Data Loading
- Exploratory Data Analysis (EDA)
- Data Visualization
- Train-Test Split
- Linear Regression Model
- Model Evaluation (MSE, R2 Score)
- Random Forest Comparison
- Feature Importance Analysis
- Model Saving using Pickle

# Dataset
California Housing Dataset (scikit-learn)

# Models Used
- Linear Regression
- Random Forest Regressor

# Results
- Linear Regression R2 Score: ~0.60+
- Random Forest R2 Score: ~0.80+

Random Forest performed better than Linear Regression.

# Skills Used
Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Model Evaluation




## Task 2 – Model Optimization & Comparison

In this task multiple machine learning models were trained and compared
using the California Housing Dataset.

Models used:

- Linear Regression
- Ridge Regression
- Decision Tree Regressor
- Random Forest Regressor

Evaluation Metrics:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Best Model: Random Forest Regressor  
R² Score Achieved: **0.8047**

Additional Visualizations:

- Model Comparison Graph
- Actual vs Predicted Plot
- Feature Importance Graph

- ## Task-3: Model Validation and Hyperparameter Tuning

- Applied Cross Validation (K-Fold)
- Performed Hyperparameter Tuning using GridSearchCV
- Compared baseline and tuned model
- Performed Overfitting and Underfitting analysis
- Final model justification provided
- Achieved stable R² score (~0.80)
- 

#  Task 4: Classification Models, Evaluation Metrics & Imbalanced Data Handling

##  Overview

This project focuses on building and evaluating classification models using machine learning techniques. The objective is to understand how to properly evaluate models using different metrics and handle imbalanced datasets effectively.

---

##  Objectives

* Build classification models for binary prediction
* Evaluate models using multiple performance metrics
* Understand limitations of accuracy
* Analyze ROC Curve and AUC
* Handle imbalanced datasets
* Compare performance of different models

---

##  Models Used

* **Logistic Regression**
* **Decision Tree Classifier**

---

##  Dataset

* Breast Cancer Dataset (from `sklearn`)
* Binary classification problem:

  * `0` → Malignant
  * `1` → Benign

---

##  Evaluation Metrics

The following metrics were used for evaluation:

* **Confusion Matrix** → Shows TP, TN, FP, FN
* **Precision** → Accuracy of positive predictions
* **Recall** → Ability to detect all positive cases
* **F1 Score** → Balance between precision and recall
* **Accuracy** → Overall correctness
* **ROC Curve** → Performance visualization
* **AUC Score** → Model’s ability to distinguish classes

---

##  Why Accuracy is Not Enough

Accuracy alone can be misleading, especially in imbalanced datasets. A model may show high accuracy but still fail to correctly classify minority class instances. Hence, additional metrics like Precision, Recall, and F1 Score are essential.

---

##  Handling Imbalanced Data

To address class imbalance:

* Used **`class_weight='balanced'`** in Logistic Regression
* This improves the model’s ability to detect minority class samples

---

##  Model Comparison

| Model               | Observation                                           |
| ------------------- | ----------------------------------------------------- |
| Logistic Regression | Stable performance with balanced precision and recall |
| Decision Tree       | Higher variance, prone to overfitting                 |
| Logistic (Balanced) | Improved recall and better handling of imbalance      |

---

##  Final Model Selection

**Logistic Regression (with balanced class weights)** was selected as the final model because:

* It provides a good balance between precision and recall
* Performs consistently across evaluation metrics
* Achieves strong ROC-AUC performance

---

##  Key Learnings

* Importance of using multiple evaluation metrics
* Understanding confusion matrix deeply
* ROC-AUC as a strong performance indicator
* Handling imbalanced datasets effectively
* Model comparison and selection strategies

---

##  Files Included

*'AI_ML_TASK4_Classification_Evaluation.ipynb' → Complete implementation
* 'AI_ML_Task4_Report.pdf' → Detailed report

---

##  Conclusion

This task demonstrates how to build reliable classification models by focusing on proper evaluation techniques and handling real-world challenges like imbalanced data. Logistic Regression proved to be a robust and effective solution for this problem.

---


# Author
Kishan



Note: Random Forest model file is not uploaded due to GitHub file size limits.
