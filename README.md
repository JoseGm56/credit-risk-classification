# credit-risk-classification

## Overview of Analysis:

The purpose of the analysis was to train amodel to accurelty predict the creditworthiness of borrowers. The data contained infromation such as number of accounts, loan size, interest rate and the model need to takew this data to know if this creditor was likely to pay back anyfuture loans, labeling as healthy or if theres was a greater chance that they couldnt pay labeling them a high-risk creditor. More specifically the variables that we are using to predict are loan status. We separeated the data into two sets one to train the models on and  and the other to test said models and see their accfuracy. We used a linear regression model and for then resampled the data with the RandonOverSample then reapplied them to the linear regression model and compared the results of these two models.

## Results:

Machine Learning Model 1:

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
    macro avg      0.92      0.95      0.94     19384
    weighted avg   0.99      0.99      0.99     19384

Machine Learning Model 2: 

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
    macro avg      0.92      0.99      0.95     19384
    weighted avg   0.99      0.99      0.99     19384

## Summary:

The resampled model tended to perform better with better recall and f1 scores. In my opionion both models seems to behave well and could be used interchangilby but the second one has a slight edge. Predicting the high-risk creditors seems more important as they represetn more potential lossed which reinforces my idea to go for the second model. 
