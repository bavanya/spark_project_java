# sample_spark_project

### This repository gives fundamental idea on the use of the sparkRDDs and sparkSQL for big data processing.

An uber jar must be generated which can then be used to run the spark application locally.
Maven can be used to build the jar file.

The command is: **mvn package**.

Then running the spark application can be done using the commands from: [https://spark.apache.org/docs/latest/submitting-applications.html](https://spark.apache.org/docs/latest/submitting-applications.html).

Using spark in the projects is especially useful in cases where parallel computation is possible and the data is huge enough to case a latency in the sequential processing. 

For example, when we need to apply fixed rules and transform each data point in a dataset. Parallel computation is possible in this case since the computations required for the data points are independant of each other. 
