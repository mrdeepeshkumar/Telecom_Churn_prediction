# Telecom_Churn_prediction  
This repository contains the iPython notebook and training data to accompany the Telecom Churn Prediction with Logistic Regresssion and Principal Component Analysis in Python. 

# Problem Statement 
A leading telecom company was facing issues with why their customers churn and wants to increase customer retention.This is a big business problem because it is more expensive to aquire  a new customer than to keep an existing one from leaving.

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

# Steps 

 * Problem understanding 
 * Understanding the business objective 
 * Data cleaning and preparation
 * Preprocessing steps 
   * Reduced dimensionality for logistic regression using PCA
 * Test-train split
 * Feature scaling
 * Model Building using RFE, p-values and VIFs 
 * Evaluation 
 # Conclusion 
I have predicted whether a particular customer will switch to another telecom provider or not.The implementation was done using the Logistic Regression and Principal Component Analysis and got 82 % accuracy. Implemented the model  to predict whether a particular customer will switch to another telecom provider or not.In telecom terminology, this is referred to as churning and not churning, respectively.
