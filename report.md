# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge.

    The objective of this analysis is to evaluate the effectiveness of a machine learning model in predicting credit risk for loan applicants. By leveraging data from loan applications and their corresponding outcomes, the model seeks to accurately assess the creditworthiness of prospective borrowers. The data pulls financal information regarding loan applicants including details such as demographics, income, credit history, loan amount, and loan terms. the goal is to predict if a barrower is likely to be a high risk or low risk when it comes to defualting on their loan. This tool and prediction model is an essential tool to help make an infomred decision for the bank when making loan approvals. 
    
Machine learning stages: read teh CSV, create labels, set y and x, split data into training and testing, fit the logistic regression model by using the training data, evaluate the models preformance by generating a confusion matrix, print the classification report

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.
model accuracy: 99%
0: precision: 1, recall: .99, f1-score: 1 
1: precision:.85, recall:.91, f1-score: .88

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

The model seems to have a high accuracy at 99% which is greaat, however there are signifcantly more 0's then 1's, and it is more important to predict the 1's than 0's because it is worse for a riskier application to be accidentally approved for a loan because they are more likely to defualt on their loan. the model is 91% accurate at predicting ones which is lower than its ability to predict 0's so this might not be the best model to use for such a task, even a few wrong predictions could cost the bank a lot of money. therefore more data on 1's would help train the model to be more accurate at predicting risker credit applicants.  
