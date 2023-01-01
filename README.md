# Credit_Risk_Analysis
## Overview of the loan prediction risk analysis:
The purpose of Credit Risk Analysis is to mitigate the risks involved in lending money to individuals by establishing and utilizing a metric by which risk of loaning can be assessed. This can be determined by analysis of variables such as home ownership, last payment and much more through machine learning. 

## Results:
Oversampling
- Balanced accuracy score: 0.6403
- Precision 
  - High risk: 0.01
  - Low risk: 1.00
- Recall scores:
  - High risk: 0.61
  - Low risk: 0.69

SMOTE Oversampling
- Balanced accuracy score: 0.6514
- Precision:
  - High risk: 0.01
  - Low risk: 1.00
- Recall scores:
  - High risk: 0.61
  - Low risk: 0.69

Undersampling
- Balanced accuracy score: 0.5439
- Precision:
  - High risk: 0.01
  - Low risk: 1.00 
- Recall scores:
  - High risk: 0.69 
  - Low risk: 0.39

Combination
- Balanced accuracy score: 0.6551
- Precision:
  - High risk: 0.01
  - Low risk: 1.00
- Recall scores:
  - High risk: 0.75
  - Low risk: 0.56

Balanced Random Forest Classifier
- Balanced accuracy score: 0.7885
- Precision:
  - High risk: 0.03
  - Low risk: 1.00 
- Recall scores:
  - High risk: 0.70
  - Low risk: 0.87

Easy Ensemble AdaBoost Classifier
- Balanced accuracy score: 0.9316
- Precision:
  - High risk: 0.09
  - Low risk: 1.00
- Recall scores:
  - High risk: 0.92
  - Low risk: 0.94

## Summary:
In all six models, the balanced accuracy score is above 60% with the highest accuracy score being 93.16% for the Easy Ensemble AdaBoost Classifier. Overall, there is poor precision for high risk cases in all 6 models with the Easy Ensemble AdaBoost Classifier being the best with precision at 9%. This creates senarios with models that would result in a lot of false positives for high risk cases. The best recall scores is the Easy AdaBoost Classifier with 92% and 94% for high risk and low risk cases respectively. 

I recommend using the Easy Ensemble AdaBoost Classifier because of the high balanced accuracy score and recall scores. The precision is comparatively higher than the other 5 models but would still have a lot of false positives. That is why it is important to have human intervention to review all the high risk results. 
