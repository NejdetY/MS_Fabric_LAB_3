# MS_Fabric_LAB_3
# Using Delta Tables in Apache Spark with Microsoft Fabric

This project is based on the "Use Delta Tables in Apache Spark" lab exercise provided by Microsoft.  
The goal is to explore Delta Lake capabilities within Microsoft Fabric, working with batch and streaming data using Delta tables.

## Lab Summary

- **Environment Setup**:
  - Created a Microsoft Fabric workspace with Lakehouse.
  - Uploaded a `products.csv` file into the Lakehouse.

- **Data Exploration**:
  - Used PySpark to define a schema and load the CSV file into a DataFrame.
  - Displayed and explored the data using Spark DataFrames.

- **Delta Table Operations**:
  - Created **Managed** and **External** Delta Tables.
  - Compared table properties using SQL commands.
  - Deleted tables to observe differences between managed and external storage behaviors.

- **Data Versioning**:
  - Updated table entries and retrieved different table versions by accessing the Delta Lake transaction log.

- **SQL Queries**:
  - Created a temporary SQL view.
  - Queried and visualized the dataset using SQL and PySpark.

- **Streaming Data with Delta Lake**:
  - Simulated IoT streaming data using Spark Structured Streaming.
  - Wrote streaming data into a Delta table and observed live updates.

## Key Technologies

- Microsoft Fabric (Lakehouse)
- Apache Spark
- Delta Lake
- PySpark
- Structured Streaming
- SQL

## Resources

- [Microsoft Fabric](https://app.fabric.microsoft.com/home?experience=fabric)
- [products.csv Dataset](https://github.com/MicrosoftLearning/dp-data/raw/main/products.csv)

## Notes

- A Microsoft Fabric trial account was used for this lab.
- This project demonstrates both batch and real-time data processing with Delta Lake tables in a Fabric Lakehouse environment.

---


