# Predicting-impact-of-marketing-on-sales-in-R
Finding how different marketing channels and price of product impact sales of the product

Objective is to build a prediction model which will determine the sales of number of units of a particular product given some predictor variables like price and amount of advertisement spent on different media.
In other words a model that will predict the effectiveness of different marketing channels on sales of a product i.e. I want to find out whether radio campaign is good or not, Or I want to know whether TV brings better revenue than radio advertisement and so on?

Every record in the data set belongs to a particular week. I have the sales of the product labelled as (NewVolSales), the base price of the product is given by Base Price column, the money spent on Radio advertisement, TV advertisement, Instore promotion are shown in Radio, TV and Instore columns respectively. There are also Facebook, Twitter, Webcampaign, Online Campaign and newspaper Inserts columns- and value of 0 in those columns indicates there was no such particular campaign for that specific week while indicates the presence of campaigns.
So with all this data we have got, our objective is  to create a predictive model, where we will predict how many units of product is going to be sold for a particular week and what are the effects of price and different media channels on the sales?

Since our dependent/target variable here sales (NewVolSales) is continuous; we will use a linear regression equation.
The steps written in high level here that needs to be done to build our predictive model are:

1. Read in the data into R.
2. Perform exploratory analysis of the data- see the structure of the data, check the summary statistics, find the missing values, perform univariate and bivariate analysis, identify the outliers and treat it, create additional variables (grouping of some variables, transform some variables, creation of lag and interaction variables, dummy variables, and so on).
3. Build linear regression model using stepwise regression. Perform iterations, flush out the insignificant variables and choose a final model.
4. Validate the model.
5.  Test the model on test data set

In addition, a pdf file with the following link https://drive.google.com/file/d/0B7PO2UZh7eKmT2xjUElYMTdYbHc/view?usp=sharingtitled contains the data exploration and data preprartion codes performed in R. 

Copyright www.datasciencemojo.com


