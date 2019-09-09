# Titanic Survival Prediction - Machine Learning from Disaster
On April 15, 1912, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. 

The data of this project was obtained from [Kaggle](https://www.kaggle.com/c/titanic/overview), which contains such demographic information of the passengers on Titanic as their ages, genders, ticket classes, number of siblings/spouses on board, number of parents/children on board, tickect numbers, port of embarkation etc. A detailed list of the variables is as follows, which is also available [here](https://www.kaggle.com/c/titanic/data) on Kaggle.

|Variable |Definition         |Key
|:--------|:------------------|:-------------------------------------------------------|
|survival |Survival	          |0 = No, 1 = Yes                   
|pclass	  |Ticket class       |1 = 1st, 2 = 2nd, 3 = 3rd
|sex	    |Sex	
Age	      |Age in years	
sibsp	    |# of siblings / spouses aboard the Titanic	
parch	    |# of parents / children aboard the Titanic	
ticket	  |Ticket number	
fare	    |Passenger fare	
cabin	    |Cabin number	
embarked  |Port of Embarkation |C = Cherbourg, Q = Queenstown, S = Southampton

*(Variable Notes:  pclass is a proxy for socio-economic status (SES). 1st = Upper, 2nd = Middle, 3rd =Lower)*

This project is to analyze which of these demographic features made some passengers more likely to survive than others, and apply machine learning (logistic regression) to predict the survival likelihood of Titanic passengers.

# Installation
> Anaconda 3

> Jupyter Notebook 6.0.0

> Python 3.7:
>> NumPy, pandas, matplotlib, seaborn

# File Description
There are two files in this repository: one README file to provide some important information about the project and one titanic_survival_prediction.ipynb file which includes the code for analyzing the demographic features.  

# Contribution
Any contribution to this project is very welcome!

