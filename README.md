Problem statement:
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store.
Using the model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.


Hypothesis:
1) City type: Stores located in urban or Tier 1 cities should have higher sales because of the higher income levels of people there.
2) Population Density: Stores located in densely populated areas should have higher sales because of more demand
3) Customer Behavior: Stores keeping the right set of products to meet the local needs of customers will have higher sales.Healthy foods have more sales
4)Competitors: Stores having similar establishments nearby should have less sales because of more competition.
5)Store size: Supermarkets have more sales
6)Advertising: Better advertising of products in the store will higher sales in most cases.
7) Promotional Offer: Discounts/Promotional offers attract more customers and increase sales
8) Online shopping portal: If a store has online shopping portal with home delivery services sales will increase
9) Store with Pharmacy: More sales

Goals:
Based on the dataset create a model to how the products and stores influence sales and determine the factors that impact increased sales.


Limitations:

Initial analysis of the data indicate few key data points that are missing which may not help with testing all the hypothesis provided above.

Strong identifiers in the dataset:
*Food product types- Healthy vs Regular
*Store size
* Store type
*Store establishment year
*Prices


Step 1: 

I want to find what drives the sales amount for a certain product in different stores and try to predict where and how I can maximize the sales for this particular product. 
The task is to predict the sales of a certain product at a particular store, part of a chain of stores and find out what influences that sale. We will evaluate the model for the predictive accuracy using Root Mean Square Error.
Assumptions:
-	we are using only grocery type products, with few features; this is a small model
-	the category of the product might have an impact on sales (like dairy sells more than canned food beacause is used more often) 
-	the type of store and it’s location is important for sales
-	the size of the store might be important (people go to big stores to shop all they need at once)

Step 2: 
I’m building this model to provide a good insight in what drives the sales for a grocery product.
This is an easily scalable model to provide detailed info and accurate predictions for sales volume for different type of products as there is a lot of data out there.
This solution can be used for projects, start-ups and sales forecast.

Step 3: 

I would find the sales data for a product as detailed as possible (with as many features as possible). Select all the features with no NaN or missing data. Select the obviously important features for the model. All the other put them aside as we will be experimenting with them. Visualize the data (read through it and build some scatter, history plots for linearity and dimensionality and box plots for outliers).


Data clean up:
1. Replaced the Nans, identified outliers, feature selection and normalization - for both train and test data.


