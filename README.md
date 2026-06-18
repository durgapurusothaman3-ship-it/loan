                                 # Loan Default Prediction System using Lending Club Dataset

## Project Title

**Loan Default Prediction System using Exploratory Data Analysis (EDA), Linear Regression, and Interactive Dashboard Visualization**

---

# Introduction

Financial institutions such as banks and lending companies provide loans to customers based on their financial profiles. However, some borrowers fail to repay their loans, resulting in loan defaults and financial losses. Identifying potential defaulters before approving loans is an important task for effective credit risk management.

This project analyzes loan data from the Lending Club dataset to understand borrower behavior and the factors influencing loan repayment. It includes data preprocessing, exploratory data analysis (EDA), predictive modeling using Linear Regression, and interactive dashboard visualization using Plotly.

---

# Problem Statement

Banks process thousands of loan applications every day. Manually evaluating each applicant is time-consuming and may lead to incorrect decisions.

Poor loan approval decisions can result in:

* Increased Non-Performing Assets (NPAs)
* Financial losses
* Poor credit risk management
* Reduced profitability

An automated analytical system is needed to identify patterns in borrower data and support better loan approval decisions.

---

# Objectives

The main objectives of this project are:

* Load and analyze the Lending Club loan dataset
* Perform data cleaning and preprocessing
* Conduct Exploratory Data Analysis (EDA)
* Analyze borrower default behavior
* Study relationships among financial variables
* Classify borrowers into risk categories
* Build a Linear Regression model
* Evaluate model performance
* Develop an interactive dashboard using Plotly
* Generate insights for loan approval strategies

---

# Dataset Information

* **Dataset Name:** Lending Club Loan Data
* **Source:** Kaggle

### Selected Features

| Feature        | Description           |
| -------------- | --------------------- |
| loan_amnt      | Loan amount           |
| term           | Loan duration         |
| int_rate       | Interest rate         |
| annual_inc     | Annual income         |
| emp_length     | Employment length     |
| home_ownership | Home ownership status |
| purpose        | Loan purpose          |
| grade          | Loan grade            |
| credit_score   | Derived credit score  |
| loan_status    | Loan repayment status |

### Removed Features

* Address
* ZIP Code
* Customer IDs
* Long text descriptions
* Highly sparse columns

---

# Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Plotly

---

# Project Workflow

## Step 1: Data Collection

* Load dataset from Kaggle
* Explore dataset structure
* Identify required columns

---

## Step 2: Data Cleaning

* Handle missing values
* Remove unnecessary columns
* Convert data types
* Clean interest rate values
* Convert loan term into numeric format

---

## Step 3: Data Preprocessing

* Encode categorical variables
* Generate estimated credit score
* Convert loan status into binary values
* Prepare data for analysis

---

## Step 4: Exploratory Data Analysis (EDA)

Performed analysis on:

* Loan amount distribution
* Annual income distribution
* Interest rate distribution
* Loan status distribution
* Income vs default
* Employment length vs default
* Loan purpose vs default
* Home ownership vs default
* Loan amount vs default
* Correlation between variables

---

## Step 5: Risk Analysis

Borrowers are classified into:

* Low Risk
* Medium Risk
* High Risk

based on the derived credit score.

---

## Step 6: Predictive Modeling

A Linear Regression model is built using:

### Independent Variables

* Annual Income
* Interest Rate
* Loan Term

### Dependent Variable

* Loan Amount

The dataset is divided into training and testing sets before model training.

---

## Step 7: Model Evaluation

The model is evaluated using:

* R² Score
* Mean Squared Error (MSE)
* Residual Analysis

---

## Step 8: Interactive Dashboard

An interactive dashboard is created using Plotly, including:

* Income vs Loan Amount
* Loan Distribution
* Default Comparison
* Interest Rate Trends
* Dynamic charts
* Interactive filtering by loan term and purpose

---

# Visualizations

The project includes:

* Bar Charts
* Histograms
* Scatter Plots
* Box Plots
* Correlation Heatmaps
* Interactive Plotly Charts

---


# Conclusion

This project demonstrates how data analytics and machine learning can support loan risk assessment by identifying borrower patterns and financial trends. Through data preprocessing, exploratory analysis, predictive modeling, and interactive visualization, it provides valuable insights that can help financial institutions make informed lending decisions and improve credit risk management.

---


