# Health-Insurance-Cost-Prediction
This project develops a regression model to predict individual health insurance costs based on demographic and health factors like age, BMI, smoking status, and region. It includes exploratory data analysis, data cleaning, and feature encoding, ultimately achieving an $R^2$ score of approximately 0.804.

# 📌 Project Overview: 

This project aims to predict individual health insurance costs based on demographic and health-related factors. Using a dataset of over 1,300 beneficiaries, the project involves Exploratory Data Analysis (EDA), data preprocessing, and training a regression model to estimate the medical "charges" incurred by customers.

📊 Dataset Description: 

The model is trained on the insurance.csv dataset, which includes the following features:

Age: Age of primary beneficiary.
Sex: Insurance contractor gender (female, male).
BMI: Body mass index, providing an understanding of body weights that are relatively high or low relative to height.
Children: Number of children covered by health insurance / Number of dependents.
Smoker: Smoking status (yes, no).
Region: The beneficiary's residential area in the US (northeast, southeast, southwest, northwest).
Charges (Target): Individual medical costs billed by health insurance.

🛠️ Tech Stack: 

Language: Python
Libraries: pandas & numpy for data manipulation.
seaborn & matplotlib for data visualization.
scikit-learn for machine learning and evaluation.

🚀 Key Workflow: 

Exploratory Data Analysis (EDA): Visualizing distributions of age, BMI, and charges using histograms and KDE plots to understand data variance.
Data Preprocessing: Handling categorical variables (Sex, Smoker, Region).
Checking for null values (the dataset was found to be clean with 0 missing values).
Model Training: Implementing regression algorithms to predict medical charges.
Evaluation: The model's performance is measured using the R² Score (Coefficient of Determination).
