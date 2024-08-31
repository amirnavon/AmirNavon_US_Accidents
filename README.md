# Project Overview
BIU DS17 - AmirNavon_US_Accidents

#### Objective 
This project aims to develop a machine learning model to predict the impact of car accidents on traffic in the USA for 2019. The goal is to classify the impact into two categories: significant impact (1) or minimal impact (0). The project seeks to identify key factors influencing traffic impact and enhance traffic management strategies.
#### Existing Knowledge 
The dataset from Kaggle initially categorized accidents into four impact levels (1 to 4). For this project, these levels are consolidated into binary classes: significant impact (1) and minimal impact (0). Key features include traffic signals, weather conditions, time of accident, and geographical details. Understanding these factors is crucial for effective prediction of traffic impact.
#### Goals 
The primary objective is to build a robust binary classification model with strong performance metrics:
•	Accuracy: 78%
•	Precision: 76%
•	Recall: 78%
•	F1 Score: 77%
•	ROC-AUC: 83%
#### Influencing Factors 
Factors affecting results include:
•	Data Quality: The dataset has 61,852 observations. Accuracy and completeness are essential.
•	Feature Relevance: Features such as traffic signals, weather conditions, and geographical details significantly impact performance.
•	Class Distribution: The target variable is balanced with 28% significant impact and 72% minimal impact.
•	External Influences: Variations in traffic conditions and reporting practices in 2019 can impact results.
#### Innovations 
Innovative aspects of the project:
•	Algorithm: XGBoost is used for its performance and efficiency.
•	Feature Engineering: Creation of features like Season and Region to enhance model accuracy.
•	Feature Selection: Lasso regression and ANOVA applied to select significant features.
#### Data Preparation and Analysis
•	Transform Data Types and Manipulation: Convert data types and preprocess for analysis.
•	Exploratory Data Analysis (EDA): Use automated tools and visualizations to understand data distributions and patterns.
•	Data Cleansing: Address outliers with IQR and z-score methods; handle missing values using MICE and manual imputation.
#### Feature Engineering and Selection
•	Feature Engineering: Develop features such as Season and Region to improve model performance.
•	Feature Selection: Utilize Lasso regression and ANOVA to identify important features.
#### Model Selection and Testing
•	Model: XGBoost is chosen for its effectiveness in large datasets and complex patterns.
•	Confusion Matrix: Analyzed to understand the distribution of true positives, true negatives, false positives, and false negatives.
•	Performance Metrics: The model achieved:
o	Accuracy: 78%
o	Precision: 76%
o	Recall: 78%
o	F1 Score: 77%
o	ROC-AUC: 83%
#### Deployment and Beneficiaries
•	Deployment: The XGBoost model will be integrated into traffic management systems or used as a standalone tool for predicting the impact of accidents on traffic. It can be applied in real-time monitoring or offline analysis.
•	Beneficiaries:
o	Traffic Management Authorities: For optimizing resource allocation and improving traffic management.
o	Insurance Companies: For enhanced risk assessment and claim processing.
o	City Planners: To guide infrastructure improvements and traffic flow management.
o	Public Safety Agencies: For targeted safety interventions and overall traffic impact mitigation.
#### Dataset 
Available on Kaggle: https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

