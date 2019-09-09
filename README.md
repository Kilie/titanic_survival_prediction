# Titanic Survival Prediction - Machine Learning from Disaster
On April 15, 1912, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. 

The data of this project was obtained from [Kaggle](https://www.kaggle.com/c/titanic/overview), which contains such demographic information of the passengers on Titanic as their ages, genders, ticket classes, number of siblings/spouses on board, number of parents/children on board, tickect numbers, port of embarkation etc. 

A detailed list of the variables is as follows, which is also available [here](https://www.kaggle.com/c/titanic/data) on Kaggle.

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
>> NumPy, pandas, matplotlib, seaborn, scikit-learn, LogisticRegression

# File Description
There are three files in this repository: 

1. README.md provides some important information about the project.

2. The titanic_survival_prediction.ipynb file includes the code for exploring the demographic features visualizing the relationships between these features and the survival rate in the train data.

3. The machine_learning.ipynb contains code for applying LogisticRegression modeling to predict the survival in the test data.

# Results

The data exploration of the demographics showed that passengers with the following features seemed to have higher likelihood to survive: 

1. Being in the 1st class (r=-0.34), 

2. Being female, 

3. Being 16 or younger.

4. Having embarked at port C(Cherbourg) 

![Survival rate with different demographic features](https://github.com/Kilie/titanic_survival_prediction/blob/master/demo_features.png)

Fig.1 Survival rate with different demographic features


![Survival rate with different age, sex, and ticket class](https://github.com/Kilie/titanic_survival_prediction/blob/master/titanic.png)

Fig. 2 Survival rate with different combinations of the demographic features

# Contribution
Any contribution to this project is very welcome!

