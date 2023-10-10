# WILL WE BE HOMELESS?
## Predicting Renting Price at San Francisco

# Problem statement
Based on Bloomberg, San Francisco placed in 2nd of the most expensive US Cities for Renters. Therefore, we would like to analyze what wound be the factors which will affect ZORI and will the ZORI continuously increase overtime? 

## Terminology:
## Zillow Observed Rent Index (ZORI):
A smoothed measure of the typical observed market rate rent across a given region.

# Steps For Analysis
1. Merge data (ZORI ,Sale Inventory, New Listing, New Pending Listing, Median List Price, Median Sale Price, Sale to list ratio, Days to close, Sales count nowcast, Shares of Listing with a Price Cut  and Price Cut)
2. Clean data: pick only data in San Francisco, change date type , remove N/A  
3. Exploratory Data Analysis
4. Linear Regression 
5. Prediction 
6. Analyze Results
7. Model is good or not.

# Exploratory Data Analysis: Sale
![image](https://user-images.githubusercontent.com/121316449/218261837-a9a9befb-b3b6-4884-a778-3e9c08e286be.png)  ![image](https://user-images.githubusercontent.com/121316449/218261858-1d2c64d4-6cb3-4346-b16f-0def51139e1d.png)
![image](https://user-images.githubusercontent.com/121316449/218261882-26fb3961-bbac-49f6-a379-693a678d74d0.png)  ![image](https://user-images.githubusercontent.com/121316449/218261895-d9ec99a5-bee6-4475-8165-8f2772d89536.png)

# Exploratory Data Analysis: Listing
![image](https://user-images.githubusercontent.com/121316449/218261961-0d48b5f0-ce93-4836-a938-20d697fae98c.png)  ![image](https://user-images.githubusercontent.com/121316449/218261966-dd1c9d47-e1e5-45ce-98dd-00162765f859.png)
![image](https://user-images.githubusercontent.com/121316449/218261971-8166739e-9c17-4b25-8384-52fb2c0c0d14.png)  ![image](https://user-images.githubusercontent.com/121316449/218261976-956ac80f-4ea6-4f37-9838-f941c296368a.png)

# Exploratory Data Analysis
![image](https://user-images.githubusercontent.com/121316449/218262204-c40cafd6-0af2-4615-ad27-8ddbcad42900.png)

# Linear Regression
Based on Linear Regression shows that For Sale Inventory,New Listing, New Pending Listing, Median List Price, Median Sale Price, Shares of Listing with a Price Cute and Price Cute are statistically significant.

![image](https://user-images.githubusercontent.com/121316449/218262241-b8926f41-0489-455d-ac2c-099d38236fbc.png)


For Sale Inventory,New Pending Listing and Price Cute have negative coefficients which mean that the lower For sale Inventory, New Pending Listing and Price cute , the higher the odds that ZORI will be increase

![image](https://user-images.githubusercontent.com/121316449/218262286-12925430-20d4-402b-981c-0a474d047bd0.png)

New Listing, Median List Price, Median Sale Price,and Shares of Listing with a Price Cute have positive coefficients which mean that the higher For sale Inventory, New Pending Listing and Price cute , the higher the odds that ZORI will be increase

![image](https://user-images.githubusercontent.com/121316449/218262333-47e3692e-0688-4e2a-853f-b36e968e7272.png)


### We use Linear Regression analysis to predict the value of ZORI in the next 12 months based on the growth in the last 12 months of Sale Inventory, New Listing, New Pending Listing, Median List Price, Median Sale Price, Sale to list ratio, Days to close, Sales count nowcast, Shares of Listing with a Price Cut  and Price Cut. 

# Predicted ZORI in the next 12 months 

### In the next 12 months, the ZORI will continue to increase!
Will we be homeless ? Recommendation :  To compare the trends of household income of people in San Francisco with predicted ZORI

![image](https://user-images.githubusercontent.com/121316449/218262444-57731074-4ee2-4f77-ac40-e65ff067473f.png)  ![image](https://user-images.githubusercontent.com/121316449/218262453-f7d9328b-b536-4ffc-8891-cc881e6161ad.png)




