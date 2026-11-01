# Telecom Customer Churn Prediction and Retention Analysis

## Project Overview
Customer churn poses a big problem for telecommunication companies since the loss of current customers could lead to a reduction in revenue and an increase in costs incurred when acquiring new customers. Recognizing the customers who are likely to churn helps the telecommunication firms to come up with a strategy for retaining them.
The goal of the project is to study data related to customers, recognize patterns of churn, and use this information to come up with machine learning models that would be used to predict the likelihood of a customer churning.

## Objectives

- Analyze customer attributes and churn.
- Classify customers using clustering.
- Create machine learning models for predicting customer churn.
- Assess model results and find churn predictors.
- Create customer retention strategy.

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- XGBoost
- Google Colab
- Joblib

## Project Workflow

The project includes data collection and validation, exploratory data analysis, customer segmentation, feature engineering, modeling, model evaluation, explainability, retention prioritization, and exporting artifacts.

The following models were compared:

- Logistic Regression
- Decision Tree
- Random Forest                                                                                            
- Extra Trees
- XGBoost
- Dummy Classifier (baseline)

**Selected model:** Logistic Regression, based on validation PR-AUC.

## Results

The final Logistic Regression model was evaluated on a separate test dataset of 1,409 customers using a probability threshold of 0.60.

| Metric | Test Result |
|---|---:|
| Accuracy | 77.4% |
| Precision | 55.9% |
| Recall | 71.1% |
| F1-score | 62.6% |
| ROC-AUC | 84.6% |
| PR-AUC | 65.6% |

The model identified approximately 71% of customers who actually churned in the test dataset.
                  
## Customer Segmentation

The K-Means cluster analysis has determined four unique customer clusters that have distinct tenure, usage of service, monthly charges, and patterns of churn. The distinct churn levels among these clusters point to customers who require retention programs.
## Business Recommendations

Potential retention strategies include:

- Offering suitable longer-term contracts to high-risk month-to-month customers.
- Improving onboarding for customers with short tenure.
- Providing proactive technical support.
- Reviewing plan suitability for customers with high monthly charges.

These recommendations require further testing to establish their actual impact.

## Limitations

- The dataset represents a sample from a fictional telecommunications provider.
- The data does not support temporal analysis.
- Predictive relationships do not establish causation.
- The model requires validation on real-world company data.
- A/B testing is needed to measure the effectiveness of retention campaigns.

## Repository Contents

- `Telecom_Customer_Churn.ipynb` 
- `README.md` 
- `requirements.txt` 

## Future Improvements

- Develop an interactive Streamlit application.
- Validate the model using updated customer data.
- Conduct experiments to evaluate retention strategies.



**Memory Mhembere**

[GitHub Profile](https://github.com/Memory-Mhembere)
