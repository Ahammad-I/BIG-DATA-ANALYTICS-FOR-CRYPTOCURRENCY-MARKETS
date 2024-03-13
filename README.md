# Big Data Cryptocurrency Project
  The dataset used for this project is a CSV file of cryptocurrency data obtained from [ Kaggle G-Research Crypto Forecasting](https://www.kaggle.com/competitions/g-research-crypto-forecasting/data).This project's primary objective is to build a pipeline that will process the dataset utilizing streaming and batch processing layers to simulate a daily cryoptocurrency trading.

  
 


## Technologies Overview

This section provides a brief overview of the technologies used in this project and their role in big data processing.

 - **HDFS (Hadoop Conveyed FileSystem)**: HDFS is a dispersed record framework intended to store and oversee enormous volumes of information across different hubs. It gives high-throughput admittance to information and is shortcoming lenient, making it appropriate for enormous information projects. 
- **Hadoop**: Hadoop is an open-source system that empowers disseminated capacity and handling of enormous datasets utilizing the MapReduce programming model. It gives a versatile, savvy answer for handling large information.
 - **Flash Streaming**: Apache Flash Streaming is a hearty, versatile, and shortcoming open minded streaming handling framework that innately upholds both bunch and ongoing responsibilities. As an expansion of the center Flash Programming interface, Flash Streaming empowers information specialists and information researchers to handle live information from various sources, like Kafka, Flume, and Amazon Kinesis...
 - **Kafka**: Apache Kafka is a disseminated streaming stage that is intended to deal with high-throughput, shortcoming lenient, and versatile constant information streaming. It empowers the distributing and buying into surges of records and permits the handling of these streams as they happen. In this venture, Kafka is utilized as a message dealer to ingest and disseminate the streaming information to be subsequently handled by Flash Streaming.
   - **MongoDB**: MongoDB is a NoSQL data set that stores information in adaptable, JSON-like reports, which considers an additional dynamic and versatile information model contrasted with conventional social data sets. It is intended to deal with high-throughput, even scaling, and high accessibility, making it appropriate for large information projects. In this task, MongoDB is utilized as the essential information store for the result of both bunch handling and streaming information, giving a bound together stockpiling arrangement that works on information the board and recovery. 
## Cluster Handling Layer In the group handling layer, Hadoop MapReduce is utilized to deal with the day to day cluster of digital currency exchange information put away in HDFS for each cryptoasset ID. 
## Streaming Layer In the streaming layer, Apache Flash Streaming is utilized to deal with the streaming information. Flash Streaming consumes the information from the Kafka subject, mimicking true streamed information, and envisions the variety of the volume weighted normal value, the min, the maximum, and the count for each timestamp (minute). 
## Information Capacity and Representation The information is then put away in a MongoDB data set and sent through a Hub server to be imagined on a Respond dashboard.

## Demo
[demo.webm](https://github.com/SamerBenMim/BigData-Pipeline-Hadoop-Kafka-Spark/assets/79151541/5fb26869-e5dd-4378-9705-b82489e1e458)



