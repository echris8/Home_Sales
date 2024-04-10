# Home_Sales
In this challenge, I used SparkSQL to determine key metrics about the home sales dataset. Then, I used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

I used Google Colab for the project since we had isses installing PySpark on our development python enviroments. 

Questions answered include: 
- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
- What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
- What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
- What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places
