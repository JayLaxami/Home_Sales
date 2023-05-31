# Home_Sales

In this,Knowledge of SparkSQL is used to determine key metrics about home sales data. Then, Spark is used to create temporary views, partition the data, cache and uncache a temporary table, and then verify that the table has been uncached.

Temp view named "home_sales" is created and SQL queries are made. Table date is partitioned and using it temporary table for the parquet data is created with name "p_home_sales_p". 

Cached table is uncached at the end and checked if home_sales temporary view table is uncached.
