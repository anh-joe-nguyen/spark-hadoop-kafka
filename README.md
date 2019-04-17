# spark-hadoop-kafka
Read file from hadoop -> push message to kafka

## Build
`sbt clean assembly`
## Run
`$SPARK_HOME/bin/spark-submit --packages org.apache.spark:spark-sql-kafka-0-10_2.11:2.4.1 --master yarn --class com.example.Application /path/to/file.jar`