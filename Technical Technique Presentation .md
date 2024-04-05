# Technical Technique Presentation Proposal - Loan Status Prediction

## Introduction
- The dataset consists of relevant data submitted by applicants seeking housing loans from banks, including personal information, income, credit history, loan amount, etc., as well as the bank's approval status for the application.
- Our goal is to train and fine-tune a prediction model for approval results based on bank loan application data and compare the predicted results with sample data to measure the accuracy of the prediction model.

## Background
- Learned and practiced predictive analysis methods and models based on the low-code machine learning library Pycaret during the course.

## Sample Data Selection
- The dataset contains 614 records with 13 fields. Excluding the ID field, there are 12 usable fields, with the loan_status serving as the target for prediction.
- 20% of the dataset will be sampled as unseen data for validating the prediction model's results, while the remaining 80% will be used for training the prediction model.

## Technical Technique Demonstration
- Data processing steps include handling missing values and splitting the dataset.
- Building a prediction model pipeline using Pycaret.
- Comparing the predicted results with actual data.

## Implementation Plan
- Download the dataset.
- Install relevant libraries such as Pycaret, Scikit-learn, and Joblib.
- Load the dataset and perform data processing.
- Select and train the prediction model.
- Predict using unseen data and compare with actual data.

## Conclusion
- Predicted data always deviates from actual occurrences. The process of training and testing prediction models is aimed at narrowing this gap.
- Comprehensive and authentic data serve as crucial foundations for reliable prediction results.

## Appendices
Loan Dataset:
https://www.kaggle.com/datasets/burak3ergun/loan-data-set