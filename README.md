# Loan Prediction Project

## 📌 Overview

This repository contains an **end-to-end Machine Learning project** to predict whether a loan will be approved or not, based on applicant details such as income, employment status, credit history, and more. The project demonstrates the complete ML workflow including **data preprocessing, visualization, model training, evaluation, and prediction**.

## 📊 Dataset

The dataset used is `Loan_Prediction_Dataset.csv` containing applicant details and loan status. Key features include:

* **Gender, Married, Dependents, Education, Self\_Employed** (categorical)
* **ApplicantIncome, CoapplicantIncome, LoanAmount, Loan\_Amount\_Term, Credit\_History** (numerical)
* **Loan\_Status** (target variable: Y = Approved, N = Not Approved)

## ⚙️ Project Workflow

1. **Importing Libraries** → Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.
2. **Data Loading** → Reading the dataset into a Pandas DataFrame.
3. **Exploratory Data Analysis (EDA)** → Summary statistics, null value checks, and feature distributions.
4. **Data Preprocessing** → Handling missing values, encoding categorical variables, and preparing the dataset.
5. **Data Visualization** → Loan status distribution, income vs loan amount, education vs loan amount.
6. **Model Building** → Training a **Random Forest Classifier**.
7. **Model Evaluation** → Accuracy score & classification report.
8. **User Prediction** → Interactive input function to predict loan approval based on user-provided details.

## 🧠 Model Used

* **Random Forest Classifier** (Scikit-learn)
* Chosen for its robustness with categorical + numerical data and ability to handle imbalances.

## 📈 Results

* Evaluated using **Accuracy** and **Classification Report**.
* Achieved a strong baseline performance suitable for loan prediction.

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/Loan_Prediction_Project.git
   cd Loan_Prediction_Project
   ```
2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Loan_Prediction_Project.ipynb
   ```

## 📂 Repository Structure

```
Loan_Prediction_Project/
│-- Loan_Prediction_Project.ipynb   # Jupyter notebook with full workflow
│-- Loan_Prediction_Dataset.csv     # Dataset file (not included here if large)
│-- README.md                       # Project documentation
│-- requirements.txt                # Python dependencies
```

## 🔮 Future Improvements

* Try different models (Logistic Regression, XGBoost, Neural Networks).
* Hyperparameter tuning for Random Forest.
* Deploy as a **Flask/Django web app** for real-time predictions.
* Add cross-validation for better performance insights.

✨ Developed as a part of a **Machine Learning learning project**.
