# Project Name: SALES AND PROFIT DASHBOARD

----
# Project Objective: 
Using key metrics to understand the Sales and Profit trend for Business X from 2014-2018.



----
# Data Sourcing
Data used for this analysis was sourced from a repository 30DaysOfLearning Data Analysis using Power BI, powered by @theoyinbooke. Link to repository is as follows:
https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students


![Sales Dashboard Data Sourcing](https://user-images.githubusercontent.com/107516898/175808468-716bd358-da31-4330-80ba-820ecba92c5c.png)



----
# Data Transformation
Data used for analysis was cleaned using basic data cleaning skills such as removal of unnecessary rows/columns, change of data type, removal of errors. This action was also repeated for the relevant dimension tables.


![Sales Dashboard Transformation](https://user-images.githubusercontent.com/107516898/175808592-51af0560-ec1d-41e7-a212-d0cfd1dc9129.png)



----
# Data Modelling
This was where i connected the fact table to the dimension tables in the data for seamless analysis. The sales table was the FACT TABLE wherein all the primary keys from each table were stored for analysis.
- The sales reps table was connected to the sales fact table with the "Sales Reps ID" key.
- The customers table was also connected to the sales fact table with the "Customer ID" key.
- The product table was connected to the sales fact table using the "Product ID" key. 
- The location table were connected to the sales fact table using the "Location ID" key.  


![Sales Dashboard Modelling](https://user-images.githubusercontent.com/107516898/175808707-4b1a3906-c853-43cc-9046-69014d1d2e30.png)



----
# Data Visualization
At this stage, we identified certain metrics as it relates to the analysis of the sales and profit of Business X. Some of the metrics identified include:
- Sales made by region - How much is the Business making from the regions where their services are present?
- Sales by Category -  How much sales is being made from the categories in Business X?
- Top five cities by sales - What are the five cities with the most sales?
- Profit made by each product sub-category by region - How well is Business X doing in terms of profit in the product subcategory present in each region?
- A line chart depicting the annual profit trend for Business X from the year 2014-2018.
- A line chart depicting the annual sales trend for Business X from the year 2014-2018. 


![Sales Dashboard](https://user-images.githubusercontent.com/107516898/175808768-456b3470-baa8-4785-91a5-f4b794bc3ce9.png)



----
# Results
After analysis, it was discovered that the "West" was the region with the most sales, with the figures totalling 0.73m between 2014-2018.
- The technology category recorded the most sales for the period under consideration, with a figure of 0.84m.
- The top five cities that recorded top sales between 2014-2018 include Philadelphia with a figure of 0.11m, San Francisco also with a figure of 0.11m, Seattle with a figure of 0.12m, Los Angeles with a figure of 0.18m, and New York city with a figure of 0.26m. New York City, however, ranked high as the city with the most sales, recording a figure of 0.26m between 2014-2018.
- The region that recorded the most profits by sub-products is the West. In the table that contains the profit figures of the subproducts by region, the figures coded in blue represent subproducts with high profits, while those coded in light red to red represent subproducts that recorded losses within the period of review. 
- From the line chart for profit, we can see that Business X generates most of their profit in 2017, while October is the month that recorded the most profits on Business X products. 
- From the line chart for sales, the year with the most sales is 2017, while Novemeber and December are the months where sales is most generated. 



----
# Observations and Recommendations
It was observed that the region where Business X made the most sales was the West and could be as a result of the the presence of urbanization as most schools, training centers, firms are located in the urban center. It could also be as a result of the unavailability of products peculiar to a particular region in the stock of Business X. It is recommended that Business X does a market survey of the affected regions through their sales reps to identify products that are akin to that particular region, and then juxtapose the quality of the products with that of ours. 
Given that the months when Business X generates the most sales tilts towards the festive period, it could be as a result of a unique product in the accessory of Business X, or close proximity to a recreation site. I recommend that the Business X improve the quality of other products so as to generate high sales in other months of the year. 
