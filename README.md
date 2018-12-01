# HFS_Clust
# How to Use:
Multiset Hesitant Fuzzy Set Clustering Using  Apache Spark
This is a code Snippet designed for data clustering using Hesitant Fuzzy Sets.
It is written in Scala so the JRE of Java and Scala Compilers with Apache Spark frameworks are obligated before begining with this code.
You can download JRE from Here:
[The JRE (Java Runtime ENvironment)](https://www.java.com/en/download/)
You can also find the latest Scala by using wether sbt or IDE integrated version of that from Here:
[The Scala Website](https://www.scala-lang.org/download/)
It works with Apache Spark which can also be found in: [The Apache Spark Website](https://spark.apache.org/downloads.html).
These Setting must then be applied to your server.
The pseudo distributed configuration of the scala assumes that there is only a master and some slave nodes. The master or cordinator node is configured at 127.0.0.1:8088. Benefiting from a virtual machine powered by java, four distinct number of processiong nodes (slave nodes) are appointed to be the slave nodes.  The RDD configuration is within the driver program. It only needs at least 2 giga byte of data in the file system it is being run. According to the volume of the datasets used for clustering this volume must be enhanced. The file named configuration,bat contains the details of configuration details. 
