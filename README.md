# Home_Sales

Please find attached my submission for the Module 22 Challenge.


Overview

In this challenge, SparkSQL has been used to determine key metrics about home sales data

Performance Analysis

To evaluate the impact of data partitioning and caching, the query run times were measured under different conditions. The performance improvements observed are as follows:

    Uncached Data: Initial query run time.
    Cached Data: Query run time after caching the table.
    Partitioned Data: Query run time after partitioning the data.

The results included in the jupyter notebook Home_Sales_colab clearly demonstrate the benefits of caching and partitioning, with significant reductions in query execution times.

