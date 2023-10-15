# Loan Risk Assessment using Machine Learning
## Overview
This repository contains a machine learning project focused on assessing the creditworthiness of borrowers in the context of a peer-to-peer lending service. The goal is to build a model that can predict whether a loan is likely to be repaid (healthy loan) or if it carries a high risk of not being repaid (high-risk loan).

## Project Highlights
* Data-Driven Risk Assessment: This project leverages a dataset to make data-driven decisions regarding loan risk. By using machine learning, we enhance the lending company's ability to make informed lending decisions.
* High Accuracy: The logistic regression model implemented in this project achieves an impressive accuracy of 99%, ensuring reliable loan assessments.
Balanced Precision and Recall: The model offers a good balance between precision and recall, which is crucial for identifying both healthy loans and high-risk loans accurately.
* Model Recommendation: Based on the strong performance, the logistic regression model is recommended for use by the lending company. However, the model choice can be adjusted based on specific business goals and requirements.

## Dataset
The dataset used in this analysis consists of historical lending activity data, including information about borrowers, loan features, and the final outcome of loans. The analysis follows these key steps:

* Data Preprocessing: Encoding categorical variables, and splitting the data into training and testing sets.
* Model Selection: Using a logistic regression model for credit risk assessment.
* Model Evaluation: Assessing the model's performance using metrics such as accuracy, precision, recall, and F1-score.

## Results
The logistic regression model achieved the following results:

* Overall accuracy of 99%
* High precision, recall, and F1-score for healthy loans ('0').
* A good balance between precision and recall for high-risk loans ('1').
