# Bank-Marketing-Campaign-Analysis_Phase1
Phase 1: Data Preprocessing
This phase involves preparing the dataset for machine learning by performing the following steps:

## 1️ Load the Dataset
The dataset is loaded from an Excel file (bank-full.xlsx).

Ensure that the file path is correctly specified before running the script.

## 2️ Check for Missing Values
We analyze missing values using df.isnull().sum().

If missing values exist, they are handled by either removing the rows (dropna()) or filling them with appropriate values (fillna()).

## 3️ Encode Categorical Variables
Since machine learning models require numerical input, we use Label Encoding to convert categorical columns into numeric values.

Example: "yes" and "no" become 1 and 0.

## 4️ Scale Numerical Features
To ensure consistent data distribution, we apply Standard Scaling using StandardScaler().

This improves the model’s performance by bringing all numerical values into a similar range.

## 5️ Save the Processed Dataset
The cleaned dataset is saved as "bank-full-processed.csv" for use in the next phase (model training).

