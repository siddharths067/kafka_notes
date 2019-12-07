# My Kafka Notes

## Command Examples to Installation

### Creating a Topic in Kafka
	```kafka/bin/kafka-topics.sh --zookeeper localhost:2181 --create --replication-factor 1 --partitions 1 --topic test```

### Show a list of all topics in Kafka
	```kafka/bin/kafka-topics.sh --zookeeper localhost:2181 --describe```
