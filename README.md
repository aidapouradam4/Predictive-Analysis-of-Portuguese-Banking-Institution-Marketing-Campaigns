# Predictive-Analysis-of-Portuguese-Banking-Institution-Marketing-Campaigns

## Overview
This repository contains the code and documentation for a project focused on predictive analysis of marketing campaigns conducted by a Portuguese banking institution. The project aims to explore whether clients are likely to subscribe to the institution's marketing campaigns based on phone calls. The analysis involves examining various attributes such as demographic information, financial status, past campaign outcomes, and communication preferences of clients.

## Dataset
The dataset used in this project was obtained from the UC Irvine Machine Learning Repository. It consists of 4521 rows and 17 columns, containing information about clients contacted during marketing campaigns. To ensure the dataset meets project requirements, irrelevant columns were removed, and missing values were checked and handled appropriately.

## Project Tasks
### 1. Data Collection and Preparation
Obtained the Bank Marketing dataset from the UC Irvine Machine Learning Repository.
Preprocessed the dataset by removing irrelevant columns and handling missing values.
Performed initial data exploration using both manual methods and the sweetviz library to gain insights into the dataset.
### 2. Data Exploration
Explored each attribute in the dataset, including age, job, marital status, education, default status, loan status, contact type, etc.
Investigated relationships between pairs of columns and posed meaningful questions about the data.
Explored the influence of age and account balance on client subscription behavior.
![image](https://github.com/aidapouradam4/Predictive-Analysis-of-Portuguese-Banking-Institution-Marketing-Campaigns/assets/103252922/aa9a9cec-45be-4102-ba97-c9ba813658fc)
![image](https://github.com/aidapouradam4/Predictive-Analysis-of-Portuguese-Banking-Institution-Marketing-Campaigns/assets/103252922/2fa1a6c9-31ea-4f96-b387-6f9150d6b745)
![image](https://github.com/aidapouradam4/Predictive-Analysis-of-Portuguese-Banking-Institution-Marketing-Campaigns/assets/103252922/8c74fc1b-fbf6-42ba-9a08-6e6f7cc86241)

### 3. Data Modeling
Split the data into training and test sets.
Applied feature transformation techniques such as Z-score normalization and Principal Component Analysis (PCA).
Implemented and evaluated three machine learning models: K-Nearest Neighbors (KNN), Decision Trees (DT), and Artificial Neural Networks (ANN).
Tuned hyperparameters for each model to optimize performance.
Compared model performances using accuracy metrics and confusion matrices.
### 4. Performance Assessment
Applied the trained models to the test dataset and calculated accuracy metrics.
Analyzed confusion matrices to assess model performance.
Recommended the KNN model as the most suitable approach based on validation results.
![image](https://github.com/aidapouradam4/Predictive-Analysis-of-Portuguese-Banking-Institution-Marketing-Campaigns/assets/103252922/f35c56f2-daba-4628-b129-27b2f1ae91b8)

## Key Achievements
Successfully analyzed the Bank Marketing dataset to predict client subscription behavior.
Conducted thorough data exploration and implemented various machine learning models.
Achieved high accuracy in predicting subscription behavior using the KNN model.
