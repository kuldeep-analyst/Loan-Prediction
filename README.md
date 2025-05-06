# 🏦 Loan Prediction Project

A Machine Learning project aimed at predicting loan approval status based on applicant financial history, credit score, and demographic data. This project showcases practical data cleaning, feature engineering, model evaluation, and visualization using Python.

## 📁 Dataset

The dataset used in this project contains information about applicants such as:
- Gender, Marital Status, Education
- Applicant and Coapplicant Income
- Loan Amount and Term
- Credit History
- Loan Status (Target variable)

**Source:** Internal file named `Copy of loan.csv`

---

## 📌 Project Objectives

- Handle missing values and preprocess the dataset
- Engineer new features like `LoanAmount_log` and `TotalIncome_log`
- Visualize categorical and numerical variables to understand patterns
- Train and evaluate multiple machine learning classifiers
- Predict the loan approval status with high accuracy

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis

The dataset was explored through:
- Histograms of skewed features (log-transformed)
- Countplots of categorical variables such as `Gender`, `Credit_History`, and `Married`
- Feature correlation analysis to identify key influencers

---

## 🔧 Data Preprocessing

- Filled missing values using appropriate strategies (mean/mode)
- Encoded categorical features using `LabelEncoder`
- Applied feature scaling with `StandardScaler`
- Created new features to improve model interpretability

---

## 🤖 Machine Learning Models Used

| Model                    | Accuracy   |
|--------------------------|------------|
| Random Forest Classifier | **81%**    |
| Gaussian Naive Bayes     | 77%        |
| Decision Tree            | 74%        |
| K-Nearest Neighbors      | 69%        |

---

## 📈 Results

The **Random Forest Classifier** performed best with **81% accuracy**, proving robust in handling diverse features and imbalanced classes. Key features impacting predictions included `Credit_History`, `TotalIncome`, and `LoanAmount`.

---

## 📁 File Structure

```bash
Loan-Prediction-Project/
│
├── Copy of loan.csv           # Dataset file
├── loan_prediction.ipynb      # Jupyter Notebook (analysis + modeling)
├── README.md                  # Project documentation
