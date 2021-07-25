# noobDE-project-1: Covid Data

- move the data to hdfs using -copyFromLocal
```bash
hdfs dfs -copyFromLocal ./data/covid.csv /data/covid.csv
```
## Starting the pyspark

```bash
pyspark --conf spark.executor.extraClassPath=./driver/ojdbc7.jar --driver-class-path ./driver/ojdbc7.jar --jars ./driver/ojdbc7.jar
```
