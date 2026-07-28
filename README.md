# Loan-Eligibility-Prediction-System
**This project is build in my initial phase of learning of Data analysis and Machine Learning**
# ![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange) ![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Pandas%20%7C%20Matplotlib-green)
## 📌 Project Overview
The **Loan Eligibility Prediction System** is a data analytics and machine learning project designed to automate the loan approval process. Financial institutions receive thousands of loan applications daily, and manually evaluating each one is time-consuming and prone to human bias. 

This project leverages historical customer data to predict whether a loan should be approved or rejected based on applicant demographics, financial standing, and credit history.

## 🎯 Objectives
* **Exploratory Data Analysis (EDA):** Uncover patterns and relationships between applicant features and loan approval rates.
* **Data Preprocessing:** Handle missing values, outliers, and encode categorical variables for modeling.
* **Predictive Modeling:** Build and evaluate robust machine learning classification models to predict loan eligibility.
* **Risk Mitigation:** Help financial institutions minimize default risks by identifying key drivers of loan rejection.

---

## 📊 Dataset Description
The model is trained on a dataset containing customer details and their loan status. 

**Key Features Include:**
* `ApplicantIncome`: The applicant's monthly income.
* `CoapplicantIncome`: The co-applicant's monthly income.
* `LoanAmount`: The total loan amount requested.
* `Loan_Amount_Term`: The duration of the loan in months.
* `Credit_History`: Record of previous credit behavior (1 = Good, 0 = Bad).
* `Property_Area`: Urban, Semi-Urban, or Rural.
* `Dependents`: Number of dependents relying on the applicant.
* `Education`: Graduate or Not Graduate.
* `Loan_Status`: **(Target Variable)** Y (Approved) or N (Rejected).

---

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Logistic Regression, Decision Trees, Random Forest, XGBoost)
* **Environment:** Jupyter Notebook / VS Code

---

## 🚀 Workflow & Methodology

1. **Data Cleaning:** Imputed missing numerical values using median/mean and categorical values using mode. Handled extreme outliers in income and loan amounts using log transformations.
2. **Feature Engineering:** Created new aggregate features (e.g., `TotalIncome` = `ApplicantIncome` + `CoapplicantIncome`).
3. **Encoding:** Converted categorical text data into numerical formats using Label Encoding and One-Hot Encoding.
4. **Model Selection:** Trained multiple classification algorithms to establish a baseline.
5. **Evaluation:** Assessed models using Accuracy, Precision, Recall, and the F1-Score to ensure a balance between false positives and false negatives.

---

## 📈 Results (Example)
* **Best Performing Model:** Random Forest Classifier
* **Accuracy:** 83.5%
* **Key Insight:** `Credit_History` was identified as the single most critical feature determining loan approval, followed by `TotalIncome` and `LoanAmount`.

---

## 💻 Installation & Usage

### Prerequisites
Ensure you have Python 3.8+ installed on your machine.

### Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/loan-eligibility-prediction.git](https://github.com/yourusername/loan-eligibility-prediction.git)
   cd loan-eligibility-prediction
