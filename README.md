# Apache Spark
 Taming Big Data with Apache Spark and Python

# Why Learn Spark?
Spark is currently one of the most popular tools for big data analytics. You might have heard of other tools such as Hadoop. Hadoop is a slightly older technology although still in use by some companies. Spark is generally faster than Hadoop, which is why Spark has become more popular over the last few years.

There are many other big data tools and systems, each with its own use case. For example, there are database system like Apache Cassandra and SQL query engines like Presto. But Spark is still one of the most popular tools for analyzing large data sets.

# Outline of the topics
* What is big data?
* Review of the hardware behind big data
* Introduction to distributed systems
* Brief history of Spark and big data
* Common Spark use cases
* Other technologies in the big data ecosystem

# Hadoop Vocabulary
Here is a list of some terms associated with Hadoop. Terms and how they relate to Spark.

* <b>Hadoop</b> - an ecosystem of tools for big data storage and data analysis. Hadoop is an older system than Spark but is still used by many companies. The major difference between Spark and Hadoop is how they use memory. Hadoop writes intermediate results to disk whereas Spark tries to keep data in memory whenever possible. This makes Spark faster for many use cases.

* <b>Hadoop MapReduce</b> - a system for processing and analyzing large data sets in parallel.

* <b>Hadoop YARN</b> - a resource manager that schedules jobs across a cluster. The manager keeps track of what computer resources are available and then assigns those resources to specific tasks.

* <b>Hadoop Distributed File System (HDFS)</b> - a big data storage system that splits data into chunks and stores the chunks across a cluster of computers

As Hadoop matured, other tools were developed to make Hadoop easier to work with. These tools included:

* <b>Apache Pig</b> - a SQL-like language that runs on top of Hadoop MapReduce
* <b>Apache Hive</b> - another SQL-like interface that runs on top of Hadoop MapReduce
Oftentimes when someone is talking about Hadoop in general terms, they are actually talking about Hadoop MapReduce. However, Hadoop is more than just MapReduce. In the next part of the lesson, you'll learn more about how MapReduce works.

# How is Spark related to Hadoop?
Spark, which is the main, is another big data framework. Spark contains libraries for data analysis, machine learning, graph analysis, and streaming live data. Spark is generally faster than Hadoop. This is because Hadoop writes intermediate results to disk whereas Spark tries to keep intermediate results in memory whenever possible.

The Hadoop ecosystem includes a distributed file storage system called HDFS (Hadoop Distributed File System). Spark, on the other hand, does not include a file storage system. You can use Spark on top of HDFS but you do not have to. Spark can read in data from other sources as well such as Amazon S3.

# Streaming Data
Data streaming is a specialized topic in big data. The use case is when you want to store and analyze data in real-time such as Facebook posts or Twitter tweets.

Spark has a streaming library called [Spark Streaming](https://spark.apache.org/docs/latest/streaming-programming-guide.html) although it is not as popular and fast as some other streaming libraries. Other popular streaming libraries include [Storm](http://storm.apache.org/) and [Flink](https://flink.apache.org/).





