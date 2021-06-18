# Online-Retail-Customer-Segmentation

# Problem Description 
In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

# Data Description 

## Attribute Information: 
InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
UnitPrice: Unit price. Numeric, Product price per unit in sterling.
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides.

# Patterns/Trends in the Data

## Top 5 and Bottom 5 products
![image](https://user-images.githubusercontent.com/47490381/121404128-445b6c00-c979-11eb-8a7b-7f1b6fb88847.png)
![image](https://user-images.githubusercontent.com/47490381/121404162-4d4c3d80-c979-11eb-870d-38a0e42baf94.png)

## Top 5 countries based on number of customers
![image](https://user-images.githubusercontent.com/47490381/121404285-710f8380-c979-11eb-92e5-9853861f3aa6.png)

## Number of orders in different days of the week
![image](https://user-images.githubusercontent.com/47490381/121404556-b2079800-c979-11eb-9771-f3d108f94630.png)

## Number of orders as per month
![image](https://user-images.githubusercontent.com/47490381/121404781-e8ddae00-c979-11eb-93de-0a1670f410ea.png)

## Number of orders as per hour of the day
![image](https://user-images.githubusercontent.com/47490381/121404891-09a60380-c97a-11eb-8fab-b812e510ddd6.png)
![image](https://user-images.githubusercontent.com/47490381/121404953-19254c80-c97a-11eb-8e7e-3d36cdeff094.png)

# Model Evaluation

## Elbow method to identify optimum number of clusters
![image](https://user-images.githubusercontent.com/47490381/121405136-4c67db80-c97a-11eb-856d-451a04beaf22.png)

## Dendogram to identify the number of clusters
![image](https://user-images.githubusercontent.com/47490381/121405289-7d481080-c97a-11eb-8c63-686315f8f5c9.png)

# Number of clusters from different models
![image](https://user-images.githubusercontent.com/47490381/121405352-905ae080-c97a-11eb-98e5-fafc767ff007.png)

# Conclusion
Observing from different models, we can say that optimum number of clusters is 2.



