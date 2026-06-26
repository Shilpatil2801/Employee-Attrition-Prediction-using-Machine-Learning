# Employee Attrition Prediction using Machine Learning

## 📌 Overview

Employee attrition is a major challenge for organizations, leading to increased recruitment costs, loss of experienced employees, and reduced productivity. This project develops a Machine Learning model to predict whether an employee is likely to leave the company based on various personal, professional, and workplace-related factors.

The project uses the **IBM HR Analytics Employee Attrition & Performance** dataset and compares multiple classification algorithms to identify the best-performing model while providing actionable HR insights.

---

## 🎯 Objectives

* Analyze employee attrition trends using Exploratory Data Analysis (EDA).
* Preprocess HR data for machine learning.
* Build and compare multiple classification models.
* Evaluate model performance using standard classification metrics.
* Identify the key factors influencing employee attrition.
* Provide business recommendations for improving employee retention.

---

## 📂 Dataset

* **Dataset:** IBM HR Analytics Employee Attrition & Performance
* **Source:** Kaggle
* **Records:** 1,470 employees
* **Features:** 35 employee attributes
* **Target Variable:** `Attrition` (Yes / No)

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

* Employee Attrition Rate
* Attrition by Department
* Attrition by Job Role
* Monthly Income vs Attrition
* Work-Life Balance vs Attrition
* Years at Company vs Attrition

---

## 🤖 Machine Learning Models

The following classification models were trained and evaluated:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

---

## 📈 Model Evaluation

Performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

The best-performing model was further analyzed using feature importance.

---

## 📉 Visualizations

This project includes:

* Attrition Rate by Department
* Attrition Rate by Job Role
* Monthly Income vs Attrition (Box Plot)
* Confusion Matrix Heatmap
* Top 10 Feature Importance
* ROC Curve Comparison (Bonus)

---

## 🔍 Key Business Insights

* The Sales department has the highest employee attrition rate.
* Sales Representatives experience the highest attrition among all job roles.
* Employees who left the company earned significantly lower monthly salaries than those who stayed.
* Poor work-life balance is associated with higher employee attrition.
* Employees are most likely to leave during their first few years with the organization.

---

## 📁 Project Structure

```
Employee-Attrition-Prediction/
│
├── HR_Attrition.csv
├── employee_attrition_prediction.ipynb
├── README.md
└── charts/
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Employee-Attrition-Prediction.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Launch Jupyter Notebook

```bash
jupyter notebook
```

4. Open the notebook and run all cells.

---

## 📌 Results

* Successfully predicted employee attrition using machine learning.
* Compared three classification algorithms.
* Identified the most important factors contributing to employee attrition.
* Generated meaningful HR insights to support employee retention strategies.

---

## 📚 Future Improvements

* Apply SMOTE to handle class imbalance.
* Perform hyperparameter tuning using GridSearchCV.
* Deploy the model using Streamlit or Flask.
* Build an interactive HR dashboard for real-time attrition prediction.

---

## 👩‍💻 Author

**Shilpa Patil**

Artificial Intelligence & Data Science Student

---

## ⭐ If you found this project useful, consider giving it a star!
