# DataLake
Creation of Data Lake using Spark and  Kafka in HDFS

Step 1 - Database and Table structure and required access for Maxwell to pull data from the tables

Step 2 - Maxwell configuration for pushing data from the RDS to Kafka topics

Step 3 - Spark streaming application to pull the data from Kafka in every 2 minutes and keeping it in HDFS

Step 4 - Processing the data to make sure only the updated copy for the each record is kept and keeping the raw and final version (lastest copy of each record) in HDFS which is available to within 4 - 5 minutes once updated or inserted into MySQL.
