# Lead-score-case-study
Lead score case study is about an education company which sells online courses to industry professionals but having very poor lead conversion rate. 
The expectation of the case study is to build a model where in a lead score can be generated to each of the leads such that the customers with a higher lead score have a higher conversion chance and the customers with a lower lead score have a lower conversion chance.
The input data set has leads from the past with 9240 data points. This dataset consists of 37 attributes. The target variable, in this case, is the column ‘Converted’ which tells whether a past lead was converted or not where in 1 means it was converted and 0 means it wasn’t converted.
The data set is not clean, so before starting model building the data need to clean.
The data cleaning steps in the project involves missing value treatment, dummy variable creation for categorical variables, scaling of numerical variables. 
Once the data is cleaned, data set is split in train and test set and then RFE is used to identify most suitable variables for model creation. 
Logistic regression model is created from the cleaned data in such a way that P-values of the model is less than 0.05 and VIF is less than 5.
Final model is evaluated using Sensitivity-Specificity view and Precision-Recall view.
I, (Abhigyan) am the sole contributor of the project 
