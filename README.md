# Project Name - Automatic Ticket Classification Case Study
For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers. The goal is to build a model that is able to classify customer complaints based on the products/services.These tickets can be segregated automatically into their relevant categories and, therefore, help in the quick resolution of the issue.

## Table of Contents
* [General Information](#general-information)
* [Steps Performed](#steps-performed)
* [Observations](#Observations)
* [Libraries Used](#libraries-used)


## General Information
These customer complaints are unstructured text data. So, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base. The goal is to work for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans. 

Since the provided data is not labelled, non-negative matrix factorization (NMF) should be used to analyse patterns and classify tickets into the following five clusters based on their products/services:

1. Credit card / Prepaid card
2. Bank account services
3. Theft/Dispute reporting
4. Mortgages/loans
5. Others 

With the help of topic modelling, each ticket can be mapped to its respective department/category.This data can be used to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, any new customer complaint support ticket can be classified into its relevant department.


## Steps Performed
1. Data loading

2. Text preprocessing

3. Exploratory data analysis (EDA)

4. Feature extraction

5. Topic modelling 

6. Model building using supervised learning

7. Model training and evaluation

8. Model inference

## Observations
Logistic Regression - The accuracy, weighted average precision and weighted average recall is around 92%

Decision Tree - The accuracy, weighted average precision and weighted average recall is around 77%

Random Forest - The accuracy obtained is 69%, weighted average precision and weighted average recall is around 76% and 73% respectively

Naive Bayes - The accuracy obtained is 69%, weighted average precision and weighted average recall is around 74% and 73% respectively

## Libraries Used
- pandas
- plotly 
- matplotlib 
- seaborn
- sklearn
- natural language toolkit

## Contact
Created by AparnaBindage - feel free to contact me!