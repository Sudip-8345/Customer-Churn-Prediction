# Teleom-Customer-Churn-Analysis

Customers are the most important resources for any companies or businessed. What if these customers leave the company due to high charges, better compititor offers, poor customer services or something unknown, which indirectyly shows company's performance. Hence, Customer churn is one of the important metrics for companies to evaluate their performance.

Customer churn rate is the KPI to understand leaving customers. Churn rate represents the percentage of customer that company lost over all the customers at the beginning of the interval.

For example, If company had 400 customers at the beginning of the month and end with 360, means company's churn rate is 10%, because company lost 10% of the the customer from the base. Companies try to decrease churn rate as 0%.

So I have built an app for predicting whether a customer is going to churn or not.
![image alt](https://github.com/Sudip-8345/Customer-Churn-Prediction/blob/c0326f88d34899fdf4197bf285d525b861ac64cd/Images/IMG_20250707_133732.jpg)

1. Introduction
   Dataset : Telco customer churn
Source : https://www.kaggle.com/blastchar/telco-customer-churn ( IBM Sample dataset)
Here, IBM provided customer data for Telco industry to predict behaviour of the customers. Main objective is that to analyze customer behavious and develop strategies for customer retention.

Dataset has information related,

- Demographic: gender, age range and if they have any partner or dependent.
- Usage: User has phone or internet service. Also information related to multiline phone, streaming services and many more.
- Account type: How long they have been a customer, contract type, payment method, paperless billing, monthly charges.

2. Problem Description
Why customers leaving the company?
The reasons behind the customer leaving company could be

- High charges
- Better offer from competitor
- Poor customer service
- Some unknown reasons
How to detect the churn customer?
- Monitoring usage
- Analysing complains
- Analyzing competitors offers
How to prevent customers from leaving a company?
Once you detect high risk customers, apply

- Retention plans
- Improve customer service

3. Descriptive EDA
   ![image alt](https://github.com/Sudip-8345/Customer-Churn-Prediction/blob/c0326f88d34899fdf4197bf285d525b861ac64cd/Images/download%20(5).png)

   There mainly three types of customer (resulting from our clustering)
   ![image alt](https://github.com/Sudip-8345/Customer-Churn-Prediction/blob/c0326f88d34899fdf4197bf285d525b861ac64cd/Images/download%20(2).png)

   ![image alt](https://github.com/Sudip-8345/Customer-Churn-Prediction/blob/c0326f88d34899fdf4197bf285d525b861ac64cd/Images/download%20(3).png)

   
   The correlation map between feature are given below :
   ![image alt](https://github.com/Sudip-8345/Customer-Churn-Prediction/blob/c0326f88d34899fdf4197bf285d525b861ac64cd/Images/download%20(4).png)

   The ROC-AUC score of the best model is here :
   ![image alt](https://github.com/Sudip-8345/Customer-Churn-Prediction/blob/c0326f88d34899fdf4197bf285d525b861ac64cd/Images/download%20(7).png)

   Feature Imporatances are also shown below:
   ![image alt](https://github.com/Sudip-8345/Customer-Churn-Prediction/blob/c0326f88d34899fdf4197bf285d525b861ac64cd/Images/download%20(6).png)
