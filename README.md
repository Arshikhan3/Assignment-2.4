# Assignment-2.4
1. Explain hadoop in layman's term
2. Explain the components of Hadoop framework
3. Eplain the reasons to learn Big data technologies

Ans - HADOOP IN LAYMAN'S TERM
Hadoop consists of two components :
1. HDFS - for storage purpose
HDFS is a scalable, fault-tolerant, distributed storage system that works closely with a wide variety of concurrent data access applications, coordinated by YARN. HDFS works under a variety of physical and systemic circumstances.
                                          
2.Mapreduce - for processing purpose
Mapreduce consists of:
Pig - Pig provides an engine for executing data flows in parallel on Hadoop. It includes a language, Pig Latin, for expressing these data flows. Pig Latin includes operators for many of the traditional data operations (join, sort, filter, etc.), as well as the ability for users to develop their own functions for reading, processing, and writing data. Pig runs on Hadoop. It makes use of both the Hadoop Distributed File System, HDFS, and Hadoop’s processing system, MapReduce.
Pig uses MapReduce to execute all of its data processing. It compiles the Pig Latin scripts that users write into a series of one or more MapReduce jobs that it then executes. Pig Latin looks different from many of the programming languages you have seen. There are no if statements or for loops in Pig Latin. This is because traditional procedural and object-oriented programming languages describe control flow, and data flow is a side effect of the program. Pig Latin instead focuses on data flow.

Hive - Apache Hive is a data warehouse infrastructure built on top of Hadoop for providing data summarization, query, and analysis.
Apache Hive supports analysis of large datasets stored in Hadoop's HDFS and compatible file systems such as Amazon S3 filesystem. It provides an SQL-like language called HiveQL with schema on read and transparently converts queries to MapReduce, Apache Tez and Spark jobs. All three execution engines can run in Hadoop YARN. To accelerate queries, it provides indexes, including bitmap indexes.

COMPONENTS OF HADOOP FRAMEWORK - 
The 3 core components of the Apache Software Foundation’s Hadoop framework are:

1. MapReduce – A software programming model for processing large sets of data in parallel.
2. HDFS – The Java-based distributed file system that can store all kinds of data without prior organization. HDFS is the storage sheath of Hadoop. It takes care of storing data of petabyte scale. As, and when data, grows vigorously, it is constantly challenging the human perception of building and stacking data storage in the “vertical” form (i.e. accommodating data growth only on a single machine, the concept of “scaling up” was facing chronic saturation). So if the problem is that data is too big to store in one computer, then the solution is to store Data on multiple computers.
3. YARN – A resource management framework for scheduling and handling resource requests from distributed applications.

REASONS TO LEARN BIG DATA TECHNOLOGIES -
Demand for Big Data skills is extremely high, and being able to prove your
expertise is of essence
• 64% of IT hiring managers rate skilled big data knowledge as havingextremely high or high value when rating expertise of candidates; this is based on a survey by CompTIA.
• According to Forbes, the median advertised salary for professionals with Big Data expertise is $124,000 a year.
• IBM, Cisco, and Oracle together advertised 26,488 open positions that required Big Data expertise in the last twelve months.
