# Titanic-Data-Analysis

The data is from the Titanic ML competition on Kaggle. The goal is to predict which passengers survived the Titanic shipwreck.

`titanic-eda.ipynb` contains visualisations of the data, this is the exploratory analysis before fitting the model. It gives a general ideas about the relationship between the variables.

`titanic-analysis.ipynb` contains the models used to make predictions, after filling missing values and some feature engineering, the following models were used:

* SVC
* KNN
* Logistic Regression
* Random Forest
* Decision Tree

**Logistic Regression** appeared to give the best performance. Ranked 2832 out of 26158 participants, with a score of 0.79904, as of 23 June 2020.
