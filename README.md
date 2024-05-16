# 20-Credit-Risk-Classification
 Identify creditworthiness of borrowers

OVERVIEW:
This week's challenge had us use a logistic regression model to predict creditworthiness of borrowers from a peer-to-peer lending services company. The target value (y) was the column noted as 'loan_status' with a value of 0 being a healthy loan and a value of 1 having a high risk of defaulting.


RESULTS:

• Accuracy - the predicted accuracy is 99% which means the model correctly predicts the healthy loans versus the loans that may be at risk of defaulting.  A high accuracy means it correctly predicts both true positives and true negatives out of all the loans.

• Precision - the precision is 100% for the healthy loans and 87% for the risky loans.  A high precision is important in predicting creditworthiness because you want a model to correctly predict the loans that will be at risk of defaulting out of all the loans that actually will default. 

• Recall - the recall is 100% for the health loans and 89% for the risky loans.  This metric helps us identify all the loans that are truly at risk and reduces the number of false negatives. 


SUMMARY:
Overall, this model demonstrates high accuracy, precision, and recall for identifying creditworthiness for the lenders to minimize risk on lending money to borrowers who will default.  However, there is one aspect of the model that should be assessed further and that is the imbalance between the two classes. The support value for Class 0 is 18,719 as compared to Class 1 of 665.  The concern is the imbalance may create bias toward Class 0.  If the values are true, then I recommend the lender use the model for assessing creditworthiness.


I completed this week's homework by reviewing the class activities, zoom recordings, asking the teacher for assistance, and briefly using the Xpert Learning Assistant for more clarification of differences between accuracy, precision, and recall along with the class slides.
