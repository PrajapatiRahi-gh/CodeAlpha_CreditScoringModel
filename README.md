# CodeAlpha_CreditScoringModel
Machine Learning Credit Scoring Model using Logistic Regression, Decision Tree and Random Forest.


# CodeAlpha Credit Scoring Model

## Project Overview

This project was developed as **Task 1 of my CodeAlpha Machine Learning Internship**.

The objective of this project is to build a machine learning classification model using financial and personal information to predict loan status.

The project follows a complete machine learning workflow including data understanding, data cleaning, exploratory data analysis, preprocessing, model training, evaluation, and prediction.

---

## Dataset

The dataset contains **32,581 records and 12 columns**.

Important features include:

- Person Age
- Person Income
- Home Ownership
- Employment Length
- Loan Intent
- Loan Grade
- Loan Amount
- Loan Interest Rate
- Loan Status
- Loan Percent Income
- Previous Default Information
- Credit History Length

### Target Variable

`loan_status`

---

## Data Cleaning

The following steps were performed:

- Checked the dataset structure and information.
- Checked missing values.
- Handled missing numerical values.
- Handled missing categorical values.
- Checked duplicate records.
- Performed basic data validation.

Missing values were found in:

- `person_emp_length`
- `loan_int_rate`

Duplicate records were also checked during the cleaning process.

---

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to understand the dataset and identify patterns.

The project includes visualizations such as:

- Credit Risk Distribution
- Income Distribution
- Other exploratory graphs

These visualizations helped understand the distribution of the data.

---

## ⚙️ Data Preprocessing

The features were divided into numerical and categorical features.

### Numerical Features

The following preprocessing techniques were used:

- Missing value imputation
- `StandardScaler` for feature scaling

### Categorical Features

Categorical variables were processed using:

- Missing value imputation
- `OneHotEncoder`

The dataset was divided into:

- **80% Training Data**
- **20% Testing Data**

The train-test split used `random_state=42` and stratification.

---

## Machine Learning Models

Three classification algorithms were implemented:

1. Logistic Regression
2. Decision Tree
3. Random Forest

---

## Model Results

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 86.7% | 76.7% | 56.2% | 64.9% |
| Decision Tree | 88.7% | 72.8% | 77.1% | 74.9% |
| Random Forest | 93.4% | 97.2% | 71.7% | 82.6% |

These results were obtained from the test dataset used in the project.

---

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix
- ROC Curve
- ROC-AUC

These metrics were used to evaluate and compare the classification models.

---

##  Final Model

The **Random Forest** model was used for the final sample prediction.

The sample prediction from the notebook produced:

**Credit Risk: Low**

---

##  Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Machine Learning

---

## Project Structure

```text
CodeAlpha_CreditScoringModel/
│
├── credit_risk_dataset_intership.ipynb
├── README.md


## Project Outcome

This project provided practical experience with the complete machine learning workflow, including:

- Data preprocessing
- Exploratory Data Analysis
- Feature transformation
- Classification algorithms
- Model evaluation
- Model comparison
- Final prediction

The project demonstrates the application of machine learning techniques to a credit-risk-related classification problem.

---

## Author

**Rahi**

BSc IT Student  
CodeAlpha Machine Learning Intern
