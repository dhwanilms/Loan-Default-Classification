# Loan Default Prediction
Classifying each borrower as a defaulter or a defrayer using machine learning and deep learning models

## Lending Club
LendingClub is the world's largest peer-to-peer lending company, headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. It operates as an online lending platform that enables borrowers to obtain a loan, and investors to purchase notes backed by payments on loans. 
LendingClub enables borrowers credit unsecured personal loans starting from as low as $1,000 to as large as $40,000. Investors can browse the loan listings from the website and invest based on the information provided by the borrower. Investors earn money through the interest on the loans and LendingClub earns by charging a service fee to the investors and an origination fee to the borrowers. 

## Motivation
LendingClub is transforming the banking system by making loans more affordable and investing much more rewarding. However one major issue is especially in peer-to-peer lending is loan defaulting i.e. the borrowers not being able to payback the loans. Hence there is a necessity to classify each borrower as a defaulter or a defrayer based on the data collected while issuing the loans.

## Goal
Given historical data on loans given out with information on whether or not the borrower defaulted (charge-off), we would build a model that can predict wether or nor a borrower will pay back their loan? This way in the future when a new potential customer arrives, we can assess whether or not they are likely to pay back the loan.

## Requirements

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [tensorflow](https://www.tensorflow.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python  which already has the above packages and more included. However if you wish to run it online rather than your local machine you can use [Google Colab](https://colab.research.google.com/) which also has the necessary packages installed.

## Data

I have used a subset of the LendingClub dataset provided by [Kaggle](https://www.kaggle.com/wordsforthewise/lending-club) with the data starting from 2008 to 2016. The dataset contains about 396030 observations with each having 27 features such as loan_amount, interest_rate, installment etc. The target feature is the loan_status column which contains either of the two values fully-paid or charged-off.
