# Home-Sales-Big-Data-with-PySpark-SQL

![image](https://github.com/NTHub23/Home_Sales/assets/138403390/68e96f51-ad21-4f2e-93a8-947ed6125ac5)

Through utilizing PySpark and Spark SQL on Google Colab, this project serves to determine key metrics about home sales data. Then, Spark is utilized to create temporary views, partition the data, cache and uncache a temporary table. 

As an example, I generated a table with two columns, one of which contained the average price, rounded to 2 decimal places, of only the 4-bedrooms in the database and the other one which contained the grouped years when each property was sold. I also compared the runtimes between running queries on an uncached temporary table, a cached temporary table, and a cached and partitioned with Parquet temporary table.
<br>

### Findings
1. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

![image](https://github.com/NTHub23/Home_Sales/assets/138403390/1fd79a7f-ba8e-42d6-be9e-3240bf6eaf2f)

2. What is the average price of a home for each year it was built that has 3 bedrooms and 3 bathrooms? Round off your answer to two decimal places.

![image](https://github.com/NTHub23/Home_Sales/assets/138403390/ecedb799-c6f5-4147-8171-2f91dc4b6244)

3. What is the average price of a home for each year that has 3 bedrooms, 3 bathrooms, 2 floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

![image](https://github.com/NTHub23/Home_Sales/assets/138403390/4dbe73a9-5c70-4947-aff6-d7586b5d1efc)

4. What is the "view" rating for the average price of a home, rounded to two decimal places, where the homes are greater than or equal to $350,000? Although this is a small dataset, determine the run time for this query.
 
![image](https://github.com/NTHub23/Home_Sales/assets/138403390/053db0fa-25e9-4b1c-b541-1c4a3f57e8c8)


5. Using the cached data, run the query that filters out the view ratings with average price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

![image](https://github.com/NTHub23/Home_Sales/assets/138403390/e3d0e585-8af1-4006-9522-378609f545bd)

6. Run the query that filters out the view ratings with average price of greater than or equal to $350,000 with the parquet DataFrame. Round your average to two decimal places. Determine the runtime and compare it to the cached version.
 
![image](https://github.com/NTHub23/Home_Sales/assets/138403390/ef00b450-36fb-45ae-8aee-4b75fb615652)


