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

![Screen Shot 2023-01-01 at 5 06 09 PM](https://user-images.githubusercontent.com/110945895/210185943-7dba1aaa-9ada-4e8e-be0f-5dd787de1b0f.png)

Figure 1. Displaying the code for Oversampling model for balanced accuracy score, precision, and recall score. 

SMOTE Oversampling
- Balanced accuracy score: 0.6514
- Precision:
  - High risk: 0.01
  - Low risk: 1.00
- Recall scores:
  - High risk: 0.61
  - Low risk: 0.69

![Screen Shot 2023-01-01 at 5 07 49 PM](https://user-images.githubusercontent.com/110945895/210185981-55a41b46-4a9b-49ef-a4cd-f6f2ff63ad4b.png)

Figure 2. Displaying the code for SMOTE Oversampling for balanced accuracy score, precision, and recall score.

Undersampling
- Balanced accuracy score: 0.5439
- Precision:
  - High risk: 0.01
  - Low risk: 1.00 
- Recall scores:
  - High risk: 0.69 
  - Low risk: 0.39

![Screen Shot 2023-01-01 at 5 10 26 PM](https://user-images.githubusercontent.com/110945895/210186034-b2102596-4e1f-4ef6-bcec-80cc5d2e1b8a.png)

Figure 3. Displaying the code for Undersampling for balanced accuracy score, precision, and recall score.

Combination
- Balanced accuracy score: 0.6551
- Precision:
  - High risk: 0.01
  - Low risk: 1.00
- Recall scores:
  - High risk: 0.75
  - Low risk: 0.56

![Screen Shot 2023-01-01 at 5 12 17 PM](https://user-images.githubusercontent.com/110945895/210186061-8368c8f2-37c0-4bfc-9360-a354dc026d94.png)

Figure 4. Displaying the code for Combination for balanced accuracy score, precision, and recall score.

Balanced Random Forest Classifier
- Balanced accuracy score: 0.7885
- Precision:
  - High risk: 0.03
  - Low risk: 1.00 
- Recall scores:
  - High risk: 0.70
  - Low risk: 0.87

![Screen Shot 2023-01-01 at 5 13 21 PM](https://user-images.githubusercontent.com/110945895/210186081-759aafc3-43dd-46f4-8502-5443c0dff898.png)

Figure 5. Displaying the code for Balanced Random Forest Classifier for balanced accuracy score, precision, and recall score.

Easy Ensemble AdaBoost Classifier
- Balanced accuracy score: 0.9316
- Precision:
  - High risk: 0.09
  - Low risk: 1.00
- Recall scores:
  - High risk: 0.92
  - Low risk: 0.94

![Screen Shot 2023-01-01 at 5 14 32 PM](https://user-images.githubusercontent.com/110945895/210186100-4ae7ef2f-47e8-4547-bdc4-0ced118fba83.png)

Figure 6. Displaying the code for Easy Ensemble AdaBoost Classifier for balanced accuracy score, precision, and recall score.

## Summary:
In all six models, the balanced accuracy score is above 60% with the highest accuracy score being 93.16% for the Easy Ensemble AdaBoost Classifier. Overall, there is poor precision for high risk cases in all 6 models with the Easy Ensemble AdaBoost Classifier being the best with precision at 9%. This creates senarios with models that would result in a lot of false positives for high risk cases. The best recall scores is the Easy AdaBoost Classifier with 92% and 94% for high risk and low risk cases respectively. 

I recommend using the Easy Ensemble AdaBoost Classifier because of the high balanced accuracy score and recall scores. The precision is comparatively higher than the other 5 models but would still have a lot of false positives. That is why it is important to have human intervention to review all the high risk results. 
