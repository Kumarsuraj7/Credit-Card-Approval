# Cedit Card Approval

__Summary__

For any Credit card provider, scrutny of the application is the most import task. A wrongly classified record will be a financial loss to the Bank. 
In this project we are using the application and credit data available on the KAGGLE to create a model for the prediction Bad and Good Applicant based on available data. 
For the identification of bad and good customer Vintage Analysis is perfomed on available credit data. Various model such as Logistic Regression, Random Forest, XGBoost,
CatBoost and KNN model are fitte. 

## Vintage Analysis 
The term 'Vintage' refers to the month or quarter in which account was opened (loan was granted). In simple words, the vintage analysis measures the performance of a portfolio
in different periods of time after the loan (or credit card) was granted. Performance can be measured in the form of cumulative charge-off rate, proportion of customers 
30/60/90 days past due (DPD), utilization ratio, average balance etc.


Data Distribution post Vintage Analysis

![image](https://user-images.githubusercontent.com/23438020/151836656-06fae8b7-a4ad-4f38-a82e-a192eb52dbd7.png)

Application approval(target) distribution in for important features

![image](https://user-images.githubusercontent.com/23438020/151836796-d1ab88d9-10aa-411d-bcfe-f539a9fa0d17.png)

ROC Curve 

![image](https://user-images.githubusercontent.com/23438020/151837109-b244d10f-9479-4036-81cd-839a14d32002.png)

Confusion Matrics

![image](https://user-images.githubusercontent.com/23438020/151837169-077c5919-83c4-445e-b6ac-38ecd44c7409.png)


__Summary__

- Every wrongly classified customer is a finacial loss to the Bank 
- Recall score of Random forest: 0.45 & CatBoost: 0.44 which slightly different
- From execution perspective CatBoost is faster, Hence we are selecting it as the final model.

Reference:
- https://www.kaggle.com/esmaascioglu/predicting-good-bad-customers-for-credit-cards/data
- https://sundarstyles89.medium.com/weight-of-evidence-and-information-value-using-python-6f05072e83eb
- https://www.listendata.com/2019/09/credit-risk-vintage-analysis.html
