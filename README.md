# Home_Sales

## Overview

This project analyzes home sales data using PySpark. Key steps include reading data, executing SparkSQL queries, caching temporary tables, partitioning data, and comparing query runtimes.

- In this project, I start by setting up the file by renaming Home_Sales_starter_code.ipynb to Home_Sales.ipynb. I then handle the data by reading CSV data into a Spark DataFrame and creating a temporary table for data analysis. Utilizing SparkSQL queries, I execute various analyses on home sales data. To optimize performance, I cache temporary tables for faster access. Additionally, I partition the data for efficient storage and retrieval. I process Parquet data and execute queries accordingly. Through performance comparison, I evaluate query runtimes with and without caching. Finally, as part of cleanup, I uncache temporary tables as needed.


## References
- **PySpark Documentation**: The PySpark documentation provided guidance on using the uncacheTable method in the Catalog class. Accessed from: PySpark API Reference
- **Class Activities**: Information and examples from class activities were used to implement various tasks in the project.
- **ChatGPT Debugging**: Debugging assistance and guidance provided by ChatGPT helped troubleshoot issues encountered during the project development.
