# Preprocessing---NumPy---A-Loan-Data-Example
* The goal of the project is to obtain a clean and preprocessed dataset. In this notebook, we'll note down all the changes we're making to the original dataset.

### Background: 
* The task is for a data science team of a central bank in Europe

### Team Task: 
Create a credit risk model, which estimates the probability of default for every personal account
* Recovery rate
* Probability of default
* Credit risk modelling

#### Data Analyst Task:
Take the raw dataset and prepare it for the models data scientists plan to run
* What data is stored
* How to clean and preprocess the values

#### Data Source: the loan data we've been given is a sample from a larger data set that belongs to an affiliate bank based in the United States. 
* Therefore, all the values are in dollars, so we need to provide their euro equivalents
* Then every categorical variable must be quantified, so we need to change any text columns into numbers based on the information they contain.
* Furthermore, when we're measuring creditworthiness, we need to be extremely risk-averse and distrustful of any unavailable data
* Missing information suggests foul play
* If the information isn't available, we'll just assume the worst

### Steps
1. Importing the Data Set
* The raw data set contains both text and numeric data, as well as a header clarifying the contents of each culumn

