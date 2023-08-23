# Kafka-real-time-data-analysis
In this project, we read data from CSV using Python Kafka producer and send it to Kafka consumer that upload it to AWS S3 bucket in real time. Once data saved in S3, AWS Crawler will read the data into database table and query it using AWS Athena.


# Requirments: 
1. AWS EC2 instance (Ubuntu or AWS Linux)
2. Kafka package on EC2
3. Java JDK 1.8 on EC2
4. Creation of Kafka topic
5. Initiate Producer and Consumer

# Project Description:
After we setup EC2 and download Kafka and Java packages, we create a Kafka topic then we start our Producer and Consumer.
We have our Python Producer script reading the data and passing it to the Consumer, which in turn upload it to S3. Once the data in S3, the Crawler will read it in real time and update our database table that we can query in Athena.

# Project Architecture:
![Project Architecture](https://github.com/ahmad-beshr/Kafka-real-time-data-analysis/blob/main/diagram2.png)

# Project Enhancements:
There are few enhancements that required for the project to be perfromed soon.

# Project Source:
This is a replication of darshilparmar project [here](https://www.youtube.com/watch?v=KerNf0NANMo&list=WL&index=30&t=4s)

