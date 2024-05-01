# ETL-pipeline-Spar-Nord-Bank
This project involves analyzing Danish ATM transaction data from Spar Nord Bank to optimize refill frequency and gain valuable insights from the data. The data includes over 2.5 million records of withdrawal data from 113 ATMs, spanning the year 2017, and includes weather information at the time of the transactions.

Broadly performed the following tasks:
•	Extracting the transactional data from a given MySQL RDS server to HDFS(EC2) instance using Sqoop.

•	Transforming the transactional data according to the given target schema using PySpark. 

•	This transformed data is to be loaded to an S3 bucket.

•	Creating the Redshift tables according to the given schema.

•	Loading the data from Amazon S3 to Redshift tables.

•	Performing the analysis queries.


