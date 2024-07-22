# Home Sales Analysis

This Assignment shows a workflow for analyzing home sales data using Apache Spark, including data loading, caching for performance optimization, 
and partitioning with Parquet for efficient data storage and querying.

## Steps

1. **Data Loading and Initial Analysis**
    - Load CSV data into a Spark DataFrame.
    - Calculate the average price per view rating.

2. **Performance Optimization with Caching**
    - Cache the DataFrame to speed up queries.
    - Validate caching effectiveness.

3. **Data Partitioning with Parquet**
    - Partition data by `date_built` and save as Parquet.
    - Create a temporary SQL view for efficient querying.

4. **Comparative Analysis**
    - Measure query performance on uncached, cached, and Parquet data.

5. **Resource Management**
    - Uncache the DataFrame when done.
    - Stop the Spark session to release resources.


## Insights

- **Caching**: Improves repeated query performance.
- **Partitioning**: Enhances scalability and efficiency.
- **Resource Management**: Essential for optimal performance.

## Acknowledgment
Use examples from the course activities and assignments  to assist in the coding portion
use Xlearning virtual assistance for problems with code.
