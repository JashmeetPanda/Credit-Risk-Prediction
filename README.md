# Credit Risk Prediction - German Credit Dataset

This repository contains the full machine learning pipeline to predict the creditworthiness of loan applicants using the **German Credit dataset**. The project focuses on classification of applicants into **Good** or **Bad** credit risks based on various features and provides an interactive **Streamlit** application for real-time predictions.

## 📌 Project Overview

Financial institutions rely heavily on credit risk assessments to decide whether to approve or deny loan applications. This project aims to:

- **Classify** loan applicants as **Good** or **Bad** credit risks based on historical data.
- Identify the most influential features for determining an applicant's creditworthiness.
- Provide recommendations on how to improve credit evaluation processes.

## 🧠 Features Used

The model is built using the following features:

- **Age** of the applicant
- **Sex** (Male/Female)
- **Job** (Job type: 0, 1, 2, 3)
- **Housing** (Own, Free, Rent)
- **Saving accounts** (0-4 scale)
- **Checking account** (0-3 scale)
- **Credit amount** 
- **Duration** (Duration of the credit in months)
- **Purpose** (Purpose of the credit: 0-10 scale)

### Engineered Feature:
- **Debt-to-Income Ratio**: Created by dividing `Credit amount` by `Duration` to capture the applicant's debt level relative to their credit term.

## ⚡ Project Highlights

- **Data Exploration**: Statistical analysis, visualizations, and correlation matrix for a deeper understanding of the dataset.
- **Preprocessing**: Handling missing values, encoding categorical features, and feature scaling.
- **Feature Engineering**: Introduction of the Debt-to-Income ratio as a new feature.
- **Model Building**: **Random Forest Classifier** tuned with **GridSearchCV** to find the optimal hyperparameters.
- **Model Evaluation**: Performance metrics like **Accuracy**, **Precision**, **Recall**, **F1-Score**, and confusion matrix.
- **Streamlit Interface**: An interactive app for users to input their data and get real-time credit risk predictions.

