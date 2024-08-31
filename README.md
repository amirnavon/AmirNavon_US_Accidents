# Project Overview
 BIU DS17 - AmirNavon_US_Accidents
 
#### Objective
This project aims to develop a machine learning model to predict the severity of car accidents in the USA for 2019. The target is to classify accidents into two categories: severe (1) or not severe (0). The project aims to identify key factors influencing accident severity and improve traffic safety measures.
#### Existing Knowledge
The dataset from Kaggle initially categorized accidents into four severity levels (1 to 4). For this project, these levels are consolidated into binary classes: severe (1) and not severe (0). Key features include traffic signals, weather conditions, time of accident, and geographical details. Understanding these factors is crucial for effective prediction.
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
•	Class Distribution: The target variable is balanced with 28% severe and 72% non-severe accidents.
•	External Influences: Variations in traffic conditions and reporting practices in 2019 can impact results.
#### Innovations
Innovative aspects of the project:
•	Algorithm: XGBoost is used for its performance and efficiency.
•	Feature Engineering: Creation of features like Season and Region to enhance model accuracy.
•	Feature Selection: Lasso regression and ANOVA applied to select significant features.
#### Data Preparation and Analysis
1.	Transform Data Types and Manipulation: Convert data types and preprocess for analysis.
2.	Exploratory Data Analysis (EDA): Use automated tools and visualizations to understand data distributions and patterns.
3.	Data Cleansing: Address outliers with IQR and z-score methods; handle missing values using MICE and manual imputation.
#### Feature Engineering and Selection
1.	Feature Engineering: Develop features such as Season and Region to improve model performance.
2.	Feature Selection: Utilize Lasso regression and ANOVA to identify important features.
#### Model Selection and Testing
1.	Model: XGBoost is chosen for its effectiveness in large datasets and complex patterns.
2.	Confusion Matrix: Analyzed to understand the distribution of true positives, true negatives, false positives, and false negatives.
3.	Performance Metrics: The model achieved:
o	Accuracy: 78%
o	Precision: 76%
o	Recall: 78%
o	F1 Score: 77%
o	ROC-AUC: 83%
#### Deployment and Beneficiaries
Deployment
The XGBoost model will be integrated into traffic management systems or used as a standalone tool for predicting accident severity. It can be applied in real-time monitoring or offline analysis.
Beneficiaries
•	Traffic Management Authorities: For optimizing resource allocation and improving risk management.
•	Insurance Companies: For enhanced risk assessment and claim processing.
•	City Planners: To guide infrastructure improvements and safety measures.
•	Public Safety Agencies: For targeted safety interventions and overall traffic safety enhancement.
#### Dataset
Available on Kaggle: US Accidents Dataset


