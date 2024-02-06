# Lending Club Case Study for Exploratory Data Analysis

This project is for a consumer finance company that provides different types of loans (personal loans, business loans, and loans for medical procedures) to urban customers. The aim of the project is to identify patterns that would highlight the tendency of loan default. We will perform an EDA (Exploratory Data Analysis) to understand how the various attributes (consumer and loan-based ones) influence the tendency of default. 
The company would like to understand the important variables and how they contribute to default. This understanding would help the company in its portfolio and risk management. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
•	The conclusions have been highlighted in the below section and also in our presentation
* [Acknowledgements](#acknowledgements)


## General Information
- Provide general information about your project here.
- What is the background of your project?
•	To perform a risk analytics project for a consumer finance company 
- What is the business probem that your project is trying to solve?
•	To help a consumer finance company, to identify the factors that influence the chances of loan default
•	The company can utilise this knowledge for portfolio and risk assessment
- What is the dataset that is being used?
•	The dataset and the data dictionary have been provided by the company 
•	The dataset has all the details pertaining to the loans provided from 2007 to 2011


## Conclusions

For the entire data (that includes Fully Paid, Charged Off and Current customers)
•	83% of the loans have been fully paid and about 14% of the them have been charged off
•	Most of the loans have been taken for the purpose of debt consolidation (47%) and credit card (13%)
For the entire data (that includes only Charged Off customers)
•	Customers having a lower tenure of loan (36 months) have a high rate of default (57%) as compared to those opting for a higher tenure (60 months) of loan
•	Customers who have been employed for more than 10 years have accounted for about one-fourth (25%) of the defaults
•	Customers who are in either a rented house or a house (that is still in mortgage) have accounted for about 90% of the defaults
•	Customers who have taken loan for debt consolidation have the highest default rate (~50%) among the charged off customers
•	It is important to keep a close watch once the customer has missed installments for the first time, to avoid further slippages/avoid the loan being charged off. 30% of the charged off loans have had a delinquency of 2 or more times in the last 6 months.

•	About 70% of the loans that are charged off are the ones that are less than or equal to 15000
•	About 55% of the loans that are charged off are the ones that are less than or equal to 10000
•	About 50% of the charged off customers where paying an interest rate in the range of (>=)10 to (<=15)¶

•	Observation: Both Verified (36%) and Not Verified (38%) customers account for a high percentage of charged off customers
•	California accounts for the highest number of charged off customers (~20%), followed by Florida (9%) and NY (9%)
•	Majority of loan taker have annual income in range of 40000-81000¶

Considering the overall data (that includes Fully Paid, Charged Off and Current customers):
•	Proprtion of charged-off customers is more in the loan tenure of 60 months (23%) as compared to 36 months (11%)
•	Most of the loan defaults are by applicants who are at the lower income brackets
•	Loans taken for small business have a high of being charged-off
•	Grades F (30%) and G (32%) have more chances of being charged off
•	With increase in interest rates, the chance of the loan becoming charged-off increases
•	The loans provided to customers who have high record of bankruptcies (“pub_rec_bankruptcies”) are more likely to be charged off

## Technologies Used
- Excel
- Python
- Jupyter Notebook
- numpy
- pandas
- matplotlib
- seaborn.pydata

## Acknowledgements

Contributors:
* [Chaitanya Vanapamala](https://github.com/chaitanya-vanapamala/)
* [B Balaji](https://github.com/BalajiB197)
