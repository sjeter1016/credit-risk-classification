# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

For this analysis, I used machine learning to predict the creditworthiness of a potential borrower by determining if they are healthy(low-risk) or high-risk. The dataset for this analysis is from lending activity from a peer-to-peer lending service company. I wanted to see how many loans were predicted to be low-risk and high-risk vs. how were actually low-risk and high-risk. I did this by using a confusion matrix, logistic regression model, accuracy scores, and recall. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 95% accuracy. The confusion matrix is [[18663   102]
 [   56   563]]

 The precision score for low-risk is 1.00 and for high-risk is .85. 
 The recall for the low-risk is .99 and the high-risk is .91. 
  


* Machine Learning Model 2:
  * Description of Model 2 99% accuracy. The confusion matrix is 
[[18649   116]
 [    4   615]]

 The precision score for low risk is 1.00 and for high-risk is .84. 
 THe recall for low-risk is .99 and for the high-risk is .99. 
## Summary

The balance accuracy score and recall for the second model demonstrates that it is the best model to use for predicting high-risk loans. Both models are able to predict the low-risk loans at the same precision and recall. Based on the Confusion Matrix, the second one generally performs slightly better than Confusion Matrix 1. It has a higher accuracy and recall rate, indicating that the model's predictions align better with the actual positive instances. Therefore, I would recommend using model 2. 
