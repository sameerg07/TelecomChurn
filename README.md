# TelecomChurn

# Problem Statment
You have a telecom firm which has collected data of all its customers. The main types of attributes are:

* Demographics (age, gender etc.)
* Services availed (internet packs purchased, special offers taken etc.)
* Expenses (amount of recharge done per month etc.)
 

Based on all this past information, you want to build a model which will predict whether a particular customer will churn or not, i.e. whether they will switch to a different service provider or not. So the variable of interest, i.e. the target variable here is ‘Churn’ which will tell us whether or not a particular customer has churned. It is a binary variable - 1 means that the customer has churned and 0 means the customer has not churned.


## Methodology Followed

### Data cleaning and preparation

* Combining three dataframes
* Handling categorical variables
    * Mapping categorical variables to integers
    * Dummy variable creation
* Handling missing values

### Test-train split and scaling

### Model Building Using Logisitc Regression

* Feature elimination based on correlations
* Feature selection using RFE (Coarse Tuning)
* Manual feature elimination (using p-values and VIFs)

### Model Evaluation

* Accuracy
* Sensitivity and Specificity
* Optimal cut-off using ROC curve
* Precision and Recall

### Predictions on the test set
Achieved a test accuracy of 74.4% with 72.16% sensitivity

### This was done as part of the coursework of PostGraduate programme by IIIT-B
