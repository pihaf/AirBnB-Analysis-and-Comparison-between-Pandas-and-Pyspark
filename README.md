# AirBnB-Analysis-and-Comparison-between-Pandas-and-Pyspark

Pyspark is run with HDFS using three nodes. In this context, Pyspark is much slower because the data is not large enough to fully use the capability of the nodes. The dataset fits comfortably in memory and the computation can be done on a single machine, Pandas can be faster because it avoids the overhead of distributed computing. 