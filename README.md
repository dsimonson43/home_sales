# home_salesHome Sales Analysis with PySpark###
Overview
This project analyzes home sales data using Apache Spark. The goal is to explore trends in home prices based on various attributes such as the number of bedrooms, bathrooms, floors, square footage, and view ratings.

Tools & Technologies
PySpark (Apache Spark)

AWS S3 (for data storage)

Jupyter Notebook

Tasks Performed
Data Ingestion: Read home sales data from an AWS S3 bucket into a PySpark DataFrame.

SQL Queries: Analyze trends using SparkSQL, including:

Average home prices based on bedrooms, bathrooms, and year built.

Price comparisons for homes with specific attributes (e.g., 3 bed, 3 bath, 2 floors).

View rating impact on average home price.

Performance Optimization:

Cached data for faster queries.

Partitioned the dataset for efficient storage and retrieval.

Compared query runtimes for uncached vs. cached data.

Data Storage: Converted data into Parquet format for optimized querying.

Running the Notebook
Clone this repository:

sh
Copy
Edit
git clone https://github.com/yourusername/Home_Sales.git
cd Home_Sales
Launch Jupyter Notebook and open Home_Sales.ipynb.

Ensure PySpark is properly installed and configured.

Run each cell sequentially to complete the analysis.
