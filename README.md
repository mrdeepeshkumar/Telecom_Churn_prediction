# Machine Learning 
# Project: Telecom Churn Prediction 
## Objective: 
A leading telecom company was facing issues with why their customers churn and want to increase customer retention.

## Installation
### Install the requirements 
This project requires Python 3 and the following Python libraries installed:

* [NumPy](http://www.numpy.org/) 
* [Pandas](http://pandas.pydata.org/)
* [matplotlib](http://matplotlib.org/)
* [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have tool to run and execute a [Jupyter Notebook.](http://ipython.org/index.html)
Make sure you use Python 3.If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

### Intalling Anaconda Python
The easiest way to install Jupyter Notebook as well as NumPy, Pandas,matplotlib is to start with the Anaconda Python distribution.
Follow the installation instructions to download the [Anaconda](https://www.anaconda.com/distribution/) Python. We recommend using Python 3.7.

git clone https://github.com/mrdeepeshkumar/Telecom_Churn_prediction Use cd to navigate into the top directory of the repo on your machine

Launch Jupyter by entering

This will open the Jupyter Notebook software and project file in your browser. 
## Download the data 
Before running the notebook, you'll first need to download all data we'll be using. This data is located in the churn_data.csv , customer_data.csv and internet_data.csv . We will extract these into the same directory as Telecom_Churn_Prediction.

## Project overview:
A leading telecom company was facing issues with why their customers churn and want to increase customer retention.This is a big business problem because it is more expensive to aquire a new customer than to keep an existing one from leaving. This repository contains the iPython notebook and training data to accompany the Telecom Churn Prediction with Logistic Regresssion and Principal Component Analysis in Python.
A telecom firm which has collected data of all its customers. The main types of attributes are:

* Demographics (age, gender etc.)
* Services availed (internet packs purchased, special offers taken etc.)
* Expenses (amount of recharge done per month etc.)
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
10.	`OnlineSecurity:` Specifies if a customer has online security.
11.  `OnlineBackup:` if a customer has online backup.
12.  `DeviceProtection:` 	Specifies if a customer has opted for device protection.
13.	`TechSupport:` 	Whether a customer has opted for tech support of not.
14.	`StreamingTV:` Whether a customer has an option of TV streaming.
15.	`StreamingMovies:` Whether a customer has an option of Movie streaming.
16.	`Contract :` 	The type of contract a customer has chosen.
17.	`PaperlessBilling:`  	Whether a customer has opted for paperless billing.
18.	`PaymentMethod:` Specifies the method by which bills are paid.
19.	`MonthlyCharges:` Specifies the money paid by a customer each month.
20.	`TotalCharges:` 	The total money paid by the customer to the company.
##### Target Variable:
21	`Churn:`  This is the target variable which specifies if a customer has churned or not. 

### Starting the project:
`Telecom_Churn_prediction`repository contains the all necessary project files. To run this project , you may download the all files.The implimented code is provided in the `Telecom_Churn_Logistic_Regression_PCA.ipynb` jupyter notebook file.You will also be required to use the churn_data.csv , customer_data.csv and internet_data.csv dataset files to complete your work. 

This project contains three files:
* `Telecom_Churn_Logistic_Regression_PCA.ipynb`: This is the main iPython file which you must run this file to run this project.
* `churn_data.csv	`: This is the dataset. You'll load this into the main file.
* `customer_data.csv`: This is also dataset. You'll load this into the main file.
* `internet_data.csv`: This is also dataset. You'll load this into the main file.
You'll load the above three files after merge into the one file in the main iPython file. 

### Run
To successfully run the project In a terminal or command window, navigate to the top-level project directory Telecom_Churn_Prediction/ (that contains this README) and run one of the following commands:
     
    ipython notebook Telecom_Churn_Logistic_Regression_PCA.ipynb
  or
    
    jupyter notebook Telecom_Churn_Logistic_Regression_PCA.ipynb
    
### Methodology:
#### Understanding the business objective: 
The variable of interest, i.e. the target variable here is ‘Churn’ which will tell us whether or not a particular customer has churned. It is a binary variable - 1 means that the customer has churned and 0 means the customer has not churned.
#### Data Preprocessing and Cleaning:
#### Feature Selection:
Conducted feature selection for logistic regression using:
* Automated methods: RFE -Recursive Feature Elimination
* Manual methods: VIF and p-value check
#### Model Building:
In the this process built Multiple logistic Regresssion model.
#### Evaluation:
  Developed a model with an AUC score of 0.83.
### Conclusions
I have predicted whether a particular customer will switch to another telecom provider or not.The implementation was done using the Logistic Regression and Principal Component Analysis and got 82 % accuracy. Implemented the model to predict whether a particular customer will switch to another telecom provider or not.In telecom terminology, this is referred to as churning and not churning, respectively.
