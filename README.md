# Credit-Card-Spent-Prediction
BANKING-CREDIT-CARD-SPEND-PREDICTION-IDENTIFY-DRIVERS-FOR-SPEND.

# Business Problem:
One of the global banks would like to understand what factors driving credit card spend are. The bank want use these insights to calculate credit limit. In order to solve the problem, the bank conducted survey of 5000 customers and collected data. The objective of this case study is to understand what's driving the total spend (Primary Card + Secondary card). Given the factors, predict credit limit for the new applicants

# Data Availability:
Data for the case are available in xlsx format. The data have been provided for 5000 customers. Detailed data dictionary has been provided for understanding the data in the data. Data is encoded in the numerical format to reduce the size of the data however some of the variables are categorical. You can find the details in the data dictionary

# Idea and Concept:  

Credit scores are designed to make decisions easier for lenders. The bank would like to understand what factors are driving credit card spend. The bank wants to use these insights to calculate credit limit. Credit scores help lenders decide whether or not to approve loan applications and determine what loan terms to offer. The scores are generated by algorithms using information from the credit reports, which summarize the borrowing history of a customer.  

# Objective and approach:  

The objective of our project is to understand what’s driving the total spend (Primary Card + Secondary card). Given the factors, predict credit limit for the new applicants. Dataset available was in xlsx format. The data have been provided for 5000 customers. Detailed data dictionary has been provided for understanding the data in the data. Data is encoded in the numerical format to reduce the size of the data however some of the variables are categorical. You can find the details in the data dictionary.  

# Project walk-through:  

In general, the collected data was for 5000 customers and we wished to understand what is driving the total spends of credit card and prioritize the drivers based on the importance. Comeout with different insights from the project. Feature selection was also tough task to perform to select right features for the model prediction. Random forest important features and vif really helped me in feature selection. Prepare different models to check the accuracy and the prediction from model. Model used are Random Forest, KNN, SVM.

# Conclusions:  

Following are a few conclusions corresponding to the columns.  

lncreddebt : log of credit card debt in thousands. If user has more debt on credit card, then his credit card limit is more and the user is likely to have more income. If user has more debt on credit card, then she/he spends more with credit card and haven’t repaid.  

carcatvalue: Primary vehicle price category. Person owning economic car likely to have less credit card spend as she/he would prefer more on saving and likely to defer from buying expensive items.  
debtinc : If debt to income ratio is high, person is likely to spend less. 
