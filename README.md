# Home_Sales

Through the use of SparkSQL key metrics about home sales data were determined. Spark was used to create temporary views, partition the data, cache and uncached the temporary table. 

The key metrics assessed were:
  1) Average price for a four-bedroom house sold for each year
  2) Average price of a home for each year it was built that has three bedrooms and three bathrooms
  3) Average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet
  4) What is the "view" rating for homes costing more than or equal to $350,000

A comparison of the runtimes for the final query was done under differing conditions. The conditions were as follows with the associated run times:
  - Uncached (Regular initial query)
  
  <img width="271" alt="Screenshot 2024-04-13 at 8 07 57 PM" src="https://github.com/Nalchamp/Home_Sales/assets/145158606/b694369b-c058-4524-911c-20516e8e80a2">
  
  - Cached

  <img width="269" alt="Screenshot 2024-04-13 at 8 09 24 PM" src="https://github.com/Nalchamp/Home_Sales/assets/145158606/0c62f9d9-c38a-4ba2-aa99-f700e23f5da7">

    
  - Partitioned and Parquet

  <img width="283" alt="Screenshot 2024-04-13 at 8 10 11 PM" src="https://github.com/Nalchamp/Home_Sales/assets/145158606/2417ab90-7161-4a80-9b55-91d3c2bcea48">

    

