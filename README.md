Overview

Customer churn is a critical issue for telecom companies as it directly affects revenue. This project focuses on predicting which customers are likely to churn in the near future using machine learning models. By 

identifying potential churners early, companies can take timely actions to retain customers and reduce churn rates. This project employs machine learning algorithms like Random Forest and XGBoost to build a 

predictive model for customer churn.

Table of Contents

Objective

Data Source

Tools Used

Modeling Process

Key Findings

The objective of this project is to predict customer churn for a telecom company using machine learning techniques. The goal is to help the company take preventive measures by identifying customers at risk of 

leaving, improving retention, and reducing revenue loss.

Data Source

Dataset: The dataset consists of customer demographics, service usage data, contract information, and whether the customer has churned.

Data Attributes: Includes features such as customer ID, tenure, contract type, monthly charges, total charges, internet service, and churn status.

Tools Used

Python (Jupyter Notebook): For data preprocessing, model building, and evaluation.

Libraries used: Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Random Forest

MS PowerPoint: For summarizing the model outcomes and insights.

Modeling Process

Data Preprocessing:

Handled missing values and transformed categorical variables into numerical values using label encoding.

Scaled numerical features to ensure consistency across the dataset.

Exploratory Data Analysis (EDA):

Conducted univariate and bivariate analysis to identify patterns in the data and understand the factors influencing churn.

Visualized correlations between features like tenure, contract type, and internet service usage with churn status.

Modeling:

Random Forest: Built and trained a Random Forest model to predict customer churn.

XGBoost: Implemented an XGBoost model for higher predictive accuracy and feature importance analysis.

Model Evaluation:

Used metrics such as accuracy, precision, recall, F1-score, and ROC-AUC to evaluate the performance of the models.

Performed cross-validation to ensure robustness and generalizability of the models.

Key Findings

Important Features: Features such as contract type, tenure, and monthly charges were identified as significant predictors of churn.

Random Forest Model: Achieved an accuracy of 85% with strong precision and recall, indicating its effectiveness in predicting churners.

XGBoost Model: XGBoost outperformed Random Forest with an accuracy of 88% and provided more granular feature importance insights.

Churn Patterns: Customers on month-to-month contracts and those with higher monthly charges were more likely to churn.
