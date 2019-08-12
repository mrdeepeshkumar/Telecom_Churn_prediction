# Machine Learning
# Project: Telecom Churn Prediction   
## Objective: 

A leading telecom company was facing issues with why their customers churn and wants to increase customer retention.
## Downloading Data 
Before running the notebook, you'll first need to download all data we'll be using. This data is located in the churn_data.csv , customer_data.csv and internet_data.csv . We will extract these into the same directory as Telecom_Churn_Logistic_Regression_PCA.ipynb .

## Requirements and Installation 
In order to run iPython Notebook.You'll need the following libraries. 
* Numpy 
* Pandas 
* Seaborn
* Scikit Learn

## Installing Anaconda Python 
The easiest way to install Jupyter as well as NumPy, Pandas, and matplotlib is to start with the Anaconda Python distribution.

Follow the installation instructions for Anaconda Python. We recommend using Python 3.7.

git clone https://github.com/mrdeepeshkumar/Telecom_Churn_prediction
Use cd to navigate into the top directory of the repo on your machine

Launch Jupyter by entering 
## Project Overview:
A leading telecom company was facing issues with why their customers churn and wants to increase customer retention.This is a big business problem because it is more expensive to aquire  a new customer than to keep an existing one from leaving.
This repository contains the iPython notebook and training data to accompany the Telecom Churn Prediction with Logistic Regresssion and Principal Component Analysis in Python.

### Features 
1.  `CustomerID:` The unique ID of each customer
2.	`Gender:` 	The gender of a person
3.	`SeniorCitizen:`	Whether a customer can be classified as a senior citizen.
4.	`Partner:` 	If a customer is married/ in a live-in relationship.
5.	`Dependents:`	If a customer has dependents (children/ retired parents)
6.	`Tenure:`	The time for which a customer has been using the service.
7.	`PhoneService:`  	Whether a customer has a landline phone service along with the internet service.
8.	`MultipleLines:`	Whether a customer has multiple lines of internet connectivity.
9.	`InternetService:` 	The type of internet services chosen by the customer.
10.	`OnlineSecurity:` 	Specifies if a customer has online security.
11. 	`OnlineBackup:` 	Specifies if a customer has online backup.
12. 	`DeviceProtection:` 	Specifies if a customer has opted for device protection.
13.	`TechSupport:` 	Whether a customer has opted for tech support of not.
14	`StreamingTV:`	Whether a customer has an option of TV streaming.
15	`StreamingMovies:` 	Whether a customer has an option of Movie streaming.
16	`Contract :` 	The type of contract a customer has chosen.
17	`PaperlessBilling:`  	Whether a customer has opted for paperless billing.
18	`PaymentMethod:` 	Specifies the method by which bills are paid.
19	`MonthlyCharges:` 	Specifies the money paid by a customer each month.
20	`TotalCharges:` 	The total money paid by the customer to the company.
##### Target Variable:
21	`Churn:`  This is the target variable which specifies if a customer has churned or not.

## Methodology:
 
 #### Problem understanding:  
 
 #### Understanding the business objective:
 #### Data cleaning and preparation:
 #### Preprocessing steps:
      Reduced dimensionality for logistic regression using PCA
 #### Test-train split:
 #### Feature scaling
 #### Model Building:
      Used RFE, p-values and VIFs 
 #### Evaluation: 
      Developed a model with an AUC score of 0.83
 # Conclusion 
I have predicted whether a particular customer will switch to another telecom provider or not.The implementation was done using the Logistic Regression and Principal Component Analysis and got 82 % accuracy. Implemented the model  to predict whether a particular customer will switch to another telecom provider or not.In telecom terminology, this is referred to as churning and not churning, respectively.
