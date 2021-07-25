# noobDE-project-1: Covid Analysis

- move the data to hdfs using -copyFromLocal

## Starting the pyspark

```bash
pyspark --conf spark.executor.extraClassPath=./driver/ojdbc7.jar --driver-class-path ./driver/ojdbc7.jar --jars ./driver/ojdbc7.jar
```