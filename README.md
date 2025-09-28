Project Overview

This project analyzes loan approval probabilities using a machine learning model. It examines how changes in applicant features—such as employment status or income—affect the likelihood of loan approval. The goal is to provide insights that help financial institutions understand factors influencing approvals.

Dataset

The dataset contains information on loan applicants, including:

Gender

Marital Status

Dependents

Education

Self_Employed

ApplicantIncome

CoapplicantIncome

LoanAmount

Loan_Amount_Term

Credit_History

Property_Area

Loan_Status (target variable)

Features Analyzed

Baseline approval probability

Impact of all applicants being self-employed

Impact of 20% increase in annual income

Methodology

Data Preprocessing: Encoded categorical variables using LabelEncoder.

Model Training: Used a Random Forest Classifier to predict loan approval.

Scenario Analysis: Simulated changes in applicant features and measured their effect on approval probability.

Visualization: Displayed results using bar charts, horizontal bar charts, and doughnut charts with customized color palettes.

Usage

Load the dataset into a Pandas DataFrame.

Preprocess categorical features using LabelEncoder.

Train the Random Forest model using training data.

Use the trained model to predict approval probabilities under different scenarios.

Visualize results with Matplotlib or Seaborn charts.

Requirements

Python 3.x

Pandas

Scikit-learn

Matplotlib

Seaborn
