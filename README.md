# My Kafka Notes

## Command Examples to Installation

### Creating a Topic in Kafka
	kafka/bin/kafka-topics.sh --zookeeper localhost:2181 --create --replication-factor 1 --partitions 1 --topic test

### Show a list of all topics in Kafka
	kafka/bin/kafka-topics.sh --zookeeper localhost:2181 --describe

### Send a Message to Kafka Topic
	kafka/bin/kafka-console-producer.sh --broker-list localhost:9092 --topic test

### Consume a Message from a Kafka Topic
	kafka/bin/kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic test --from-beginning
