# Data-Streaming-Project-using-Apache
This project acts as a thorough guide for creating a data engineering pipeline. The project makes use of a robust tech stack that includes Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, and Cassandra to cover every step of the process, from data ingestion to processing to storage. Docker is used to containerise everything for scalability and deployment.
The project is designed with the following components:

-Data Source: We use randomuser.me API to generate random user data for our pipeline.
\-Apache Airflow: Responsible for orchestrating the pipeline and storing fetched data in a PostgreSQL database.
-\Apache Kafka and Zookeeper: Used for streaming data from PostgreSQL to the processing engine.
-Control Center and Schema Registry: Helps in monitoring and schema management of our Kafka streams.
-Apache Spark: For data processing with its master and worker nodes.
-Cassandra: Where the processed data will be stored.
