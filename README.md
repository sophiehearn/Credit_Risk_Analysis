# Credit Risk Analysis 

We are using various machine learning models to attempt to predit the credit risk of credit applicants based on a variety of factors. 

For each of the strategies, the data set was separated into training and testing groups. The applicants in our data set had previously been identified as low or high risk by other methods. We are interested in how successfully these models predict the actual results -- both in accuracy and precision. 

## Naive Random Oversampling

This method had a balanced accuracy score of .60, meaning it correctly labeled candidates 60% of the time. It accurately predicts high risk candidates 56% of the time, but also labels 37% of low risk candidates as high risk. 

## SMOTE Oversampling

This method had a balanced accuracy score of .66, meaning it correctly labeled candidates 66% of the time. It accurately predicts high risk candidates 64% of the time, but also labels 32% of low risk candidates as high risk. 

## Undersampling 

This method had a balanced accuracy score of .53, meaning it correctly labeled candidates 53% of the time. It accurately predicts high risk candidates 62% of the time, but also labels 56% of low risk candidates as high risk. 

## Smoteen Over and Under Sampling

This method had a balanced accuracy score of .65, meaning it correctly labeled candidates 53% of the time. It accurately predicts high risk candidates 75% of the time, but also labels 31% of low risk candidates as high risk. 

## Random Forest Classifier

This method had a balanced accuracy score of .79, meaning it correctly labeled candidates 79% of the time. It accurately predicts high risk candidates 67% of the time, but also labels 9% of low risk candidates as high risk. 

## Easy Ensemble AdaBoost Classifier

This method had a balanced accuracy score of .91, meaning it correctly labeled candidates 91% of the time. It accurately predicts high risk candidates 88% of the time, but also labels 5% of low risk candidates as high risk. 

## Conclusions 

The Easy Ensemble AdaBoost Classifier was clearly the most compelling model in this toolkit foor this application. It was 91% accurate, and predicted 88% of high risk candidates. It was even more precise with low-risk candidates, meaning that low-risk applicants weren't automatically rejected without grounds. 