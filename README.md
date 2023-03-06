# sales_forecast
Sales forecasting 


This project is for a sales demand forecasting. This will help supply chain figure out demand needed at a horizon of 52 weeks out 

FILES:
- 00 = this will be used as the connection to Snowflake using a specific developed Snowflake connection file and we will load our data from this file 
- 01 = this will be used for data preparation, identifying and handling false positive orders 
- 02a through 02c = are using as EDA for grouping for the modeling aspect of the project. Once the best grouping is identified for the timeseries we will only select one of the scripts within the 02 series
- 03 = this is used for the modeling aspect. We would like to have multiple algorithms in this and then we choose the best one based on performances. More on this will be added as the modeling is developed
