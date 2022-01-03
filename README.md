# Kafka_producer
Kafka producer program for KCKU Apache homework

### Build

```https://github.com/Libazhe/Kafka_producer.git```

### Run code

```java -jar ./target/producer-1.0-SNAPSHOT-jar-with-dependencies.jar producer --brokers <IP:PORT> --topic <topic-name> --records <num of records> --recordSize <size of records>```

### e.g.

```java -jar ./target/producer-1.0-SNAPSHOT-jar-with-dependencies.jar producer --brokers 127.0.0.1:9092 --topic test --records 1000 --recordSize 1000```

### Notice

*If yuo ues docker to run your kafka, please don't use 127.0.0.1 or 127.0.1.1 to be your broker IP*  
