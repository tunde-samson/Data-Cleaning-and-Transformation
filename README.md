# Data-Cleaning-and-Transformation

First, I imported the pandas, numpy, matplotlib, seaborn, and plotly libraries.

I downloaded the flipkart.com, an ecommerce dataset from kaggle.com and load it into pandas dataframe in jupyter notebook. The dataset contain many missing and duplicated values, which I removed. 
converted the date and time dtype and extracted the year, month, weekday, and hour for furtheer analysis. 

I checked in the retail_price columns for negative value to removed it, because product prices should not be negavtive values

I created another dataframe by applying group by method to find top 10 products that are performing very well.
