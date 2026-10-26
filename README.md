# Customer Churn Prediction & Retention Analysis

## Project Overview

Customer Churn Prediction & Retention Analysis is a machine learning project that predicts whether a customer is likely to discontinue a subscription-based service. It analyzes customer demographics, account details, and service usage patterns to identify churn risks and recommend suitable customer retention strategies.

The project combines data preprocessing, exploratory data analysis, feature engineering, machine learning classification, model evaluation, and business interpretation.

## Objectives

- Predict customer churn using machine learning.
- Analyze customer demographics and service usage.
- Clean missing and inconsistent data.
- Encode categorical features and prepare model-ready data.
- Compare Logistic Regression, Decision Tree, and Random Forest models.
- Evaluate performance using accuracy, precision, recall, F1-score, confusion matrices, and ROC-AUC.
- Identify important churn-related factors.
- Generate practical retention recommendations.

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook
- Optional: Streamlit for an interactive prediction interface

## Dataset

The project uses the IBM Telco Customer Churn dataset, which contains customer demographics, subscribed services, account information, payment details, and a churn indicator.

The target variable is `Churn`, which indicates whether a customer left the service.

Dataset source: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Download `WA_Fn-UseC_-Telco-Customer-Churn.csv` from the dataset source and upload it when prompted by the notebook, or place it in the notebook's working directory.

## Project Workflow

1. Load the customer churn dataset.
2. Inspect the dataset structure and data quality.
3. Handle missing values and inconsistent data types.
4. Perform exploratory data analysis.
5. Visualize churn distribution and customer characteristics.
6. Encode categorical variables and prepare features.
7. Split the data into training and testing sets.
8. Train Logistic Regression, Decision Tree, and Random Forest models.
9. Compare model performance.
10. Generate confusion matrices and ROC-AUC evaluations.
11. Analyze feature importance.
12. Predict churn risk for individual customers.
13. Generate retention recommendations based on customer characteristics and model predictions.

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC

Accuracy alone is insufficient when churn classes are imbalanced, so the project also considers precision, recall, F1-score, and ROC-AUC.

## Expected Deliverables

- Cleaned customer churn dataset
- Exploratory data analysis and visualizations
- Feature engineering and categorical encoding
- Three trained classification models
- Model comparison table
- Confusion matrices and classification reports
- ROC curves and ROC-AUC scores
- Feature importance analysis
- Customer churn risk prediction function
- Retention recommendations

## Business Applications

The project can help subscription-based businesses identify customers at risk of leaving, understand potential churn drivers, prioritize customer outreach, and design targeted retention campaigns.

## How to Run

1. Open Google Colab or Jupyter Notebook.
2. Upload or download the IBM Telco Customer Churn CSV dataset.
3. Run the notebook code.
4. Review the analysis, model comparison, evaluation plots, and feature importance.
5. Use the prediction function to evaluate a customer record.

## Limitations

Predictions depend on the quality and representativeness of the available dataset. Feature importance indicates associations learned by the model and does not establish causation. Retention recommendations are general suggestions and should be validated against real business outcomes.

## Author

**Gayatri Gangane**

Machine Learning | Data Analytics | Python
