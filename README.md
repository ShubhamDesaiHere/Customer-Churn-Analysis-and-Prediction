# Customer-Churn-Analysis-and-Prediction
internship project

🔹 Task 1: Data Preparation
📌 Objective

The objective of this task is to prepare the telecom customer churn dataset for further analysis and machine learning modeling by cleaning, preprocessing, and structuring the data.

📂 Dataset

Dataset Name: Telco Customer Churn Dataset

Target Variable: Churn

1 → Customer has churned

0 → Customer is retained

🛠️ Steps Performed

Loaded the dataset using Pandas and explored its structure, data types, and summary statistics

Identified and handled missing values in the dataset

Converted the TotalCharges column from object type to numeric format

Replaced invalid or missing values using median imputation

Removed non-informative features such as customer identifiers

Encoded categorical variables into numerical format for machine learning compatibility

Separated features and target variable (Churn)

Split the dataset into training and testing sets using an 80:20 ratio

Saved the processed datasets for reuse in subsequent tasks

📁 Output Files
data/
├── X_train.csv
├── X_test.csv
├── y_train.csv
└── y_test.csv

🧰 Tools & Technologies Used

Python

Pandas

NumPy

Scikit-learn

✅ Outcomes

A clean, structured, and machine-learning-ready dataset was created, forming a strong foundation for exploratory data analysis and churn prediction modeling in the next stages of the project.
