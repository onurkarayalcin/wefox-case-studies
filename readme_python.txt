====== README for Python =======

In order to achieve python challenge, the amount of codes mentioned in the file "Python-second_way" should be executed incrementally. For this challenge it would be possible to create more sophisticated scenario, if especially Airflow worked regularly on my PC. Due to that some negations with my PC, I could not achieve them exactly. 

As second way to load data into a table(based on a RDBMS), it is to deploy Airflow as data integration tool. As one of the best tools dedicated for performing ETL processes, Airflow provides services based on web platforms which means that user can upload data into a table created in a database on online platform of the tool. Also by creating CRON jobs, performing tasks like uploading data periodically is an easy way to satisfy requirements. 

As third alternative way, again with using Airflow, loading data into some of AWS services like S3, RedShift, RDS is also another possible way. However, when it comes to use AWS, at big rate the platform has its own widgets like AWS Glue to perform ETL/ELT tasks. However in this scenario, it is an advantage to develop a process with Boto3 library-developed to synchronize data transferring from S3 bucket to other computation services as Lambda/EC2. 

As another alternative way is to use pandas library in order to establish ETL pipelines and load data into relational databases. 

All in all, I could not recognize exactly what is expected from me to develop, especially for loading data into a table. If there was a target table/platform it would be easier to come up with an accurate result. 
