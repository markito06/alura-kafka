# Kafka 

#### Describe

```bash
kafka-topics --bootstrap-server localhost:29092 --describe
````

#### Re-partition existent topic

```bash
kafka-topics --alter --bootstrap-server localhost:29092 --topic ECOMMERCE_NEW_ORDER --partitions 3
````


