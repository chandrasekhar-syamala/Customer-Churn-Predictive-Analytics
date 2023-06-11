# Customer-Churn-Predictive-Analytics

Churn Prediction is a problem where we need to predict the probable customers that are likely to leave a service or to cancel a subscription to a service. 
It is very critical to the streaming businesses like Netflix, Amazon Prime, Spotify, Telecom Providers etc.

It also imposes the high significance because the cost of customer acquisition is more costly than retaining the customers.

So, the problem here to identify those customer who are risk of leaving so that a targeted marketing can be carried out

The dataset that I have taken is a Telco Dataset that is offered by IBM dataset and also available on openML.org

https://www.ibm.com/docs/en/cognos-analytics/11.1.0?topic=samples-telco-customer-churn

https://www.openml.org/search?type=data&status=active&id=42178


# Customer Churn Prediction

Churn prediction is one of the most popular Big Data use cases in business. It consists of detecting customers who are likely to cancel a subscription to a service.Although originally a telcom giant thing, this concerns businesses of all sizes, including startups.

Churn Prediction Model is a predictive model that calculates, on an individual customer basis, the likelihood (or susceptibility) that a customer will stop doing business with the company.It’s a binary classifier, which means that it divides customers into two distinct groups (classes) based on whether or not they leave the company.

The data is sourced from IBM/openML portal which represents the customer information of a telecom company. The data is composed of both numerical and categorical features. 


### Insights from the Dataset
The EDA on the dataset showed that the features like Monthly Charges, Tenure, Contract Type, InternetService has more effect on the customer to churn.
 
- The possibility of customer churning out decreases as the tenure period of the cusomer increases
- The numbef of customers having monthly charges greater than 60 are possible to churn
- Majority of churners are leaving in the first two months
- Fiber Optic Internet Customers churn at significantly proportions than DSL or No Internet customers
- Significantly more customers churn on monthly plans. The longer the plan, the lower the churn rate



### Modelling

As defined, the churn prediction is a classification model where we need to label a customer either Churn or Non-Churner.
Various classification algorithms are applied on the dataset. The Random Forest Classifier and Logistic Regression Classifiers are relatively better algorithms giving aroung 80% of accuracy in the predictions.
The importance of the features in both the models is presented below.





