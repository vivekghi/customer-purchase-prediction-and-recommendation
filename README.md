# customer-purchase-prediction-and-recommendation
this is repository for content for machine learning @aws. 

## this is the solution for [kaggle problem](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations).

### Given the transaction, customers and products data we need to recoomend products to customer who are likely to buy in next 7 days
## Data
- **transactions_train.csv - Data about purchases made by customers. Contains customer id, article id and transaction timestamp**
- **customers.csv - Basic details about customer. Like Age, Club status, Fashion news subscription etc.**
- **articles.csv - Contains basic details about product like Product Group, Description , Name etc**

## Approach
The Problem is broken down in 2 parts
- Identify Customers who are likely to purchase in next 7 days
- Recommendation model to recommend products to customers identified from the previous step

## Files
- 1-customer-purchase-prediction.ipynb (This contains the code for predicting customers who are likely to purchase in next 7 days)
- 2-Customer-Product-sparse-data-prep-with-attributes.ipynb (This contains the code for preparing data for recommender system)
- 3-Customer-recommender-FM-with-attributes.ipynb (This contains the code to build recommendation system using Sagemaker built in Algorithm - Factorization machine.)

