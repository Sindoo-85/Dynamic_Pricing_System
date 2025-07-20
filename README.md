# Dynamic_Pricing_System
This Project Explores about Dynamic Pricing Strategies for a Ride-sharing services by analyzing 
it's historical data,calculating demand and supply multipliers, and forecasting the ride costs using timeseries and regression modeling. The traditional pricing model used by the business is based on fixed rates per kilometre, which does not account for fluctuations in supply and demand.
Dynamic Pricing is an application of Data Science that involves adjusting product or service prices based on various factors in real time. It is employed by businesses to optimize their revenue and profitability by setting flexible prices that respond to market demand, customer behaviour, and competitor pricing.Using data-driven insights and algorithms, businesses can dynamically modify prices to achieve the most favourable outcomes.
# Overview
In Dynamic Pricing Strategy,The aim is to maximize revenue and profitability by pricing the items at the right level that balances supply and demand dynamics.It allows business to adjust Prices Dynamically based on factors like day of the week,customer segemnets,seasonal fluctutations and market conditions
# Data
To implement a Data-Driven dynamic pricing strategy, Dataset dynamic_pricing.csv is used.It includes information such as :
1. number of riders
2. number of drivers
3. vehicle type
4. expected ride duration
5. historical cost of rides
6. location category
7. coustomer loyalty
8. number of past riders
9. average ratings
10. time of booking
# Pre-Processing
A Data Preprocessing pipeline should be able to handle missing values, standardize numerical features, remove outliers, and ensure easy replication of preprocessing steps on new datasets.
The pipeline begins by identifying the numeric and categorical features in the dataset.The pipeline then identifies and handles outliers within the numeric features using the Interquartile Range (IQR) method. Calculating the quartiles and the IQR determines upper and lower boundaries for outliers. Any values outside these boundaries are replaced with the mean value of the respective numeric feature. This step helps prevent the influence of extreme values on subsequent analyses and model building.

# Model Training and Evaluation
A model is used to forecast future subscription trends ,while a random Forest regression model predicts dynamic pricing costs based on features like rider count,driver availability and ride duration.Model performance is evaluated through actual vs predicted value comparisions

# Summary
In a dynamic pricing strategy, the aim is to maximize revenue and profitability by pricing items at the right level that balances supply and demand dynamics. It allows businesses to adjust prices dynamically based on factors like time of day, day of the week, customer segments, inventory levels, seasonal fluctuations, competitor pricing, and market conditions.


