# kafka-rabbitmq

Console Producer
bin/kafka-console-producer.sh --broker-list localhost:9092 --topic test

Console Consumer
bin/kafka-console-consumer.sh --zookeeper localhost:2181 --topic test --from-beginning

Producer API's : 

https://kafka.apache.org/090/javadoc/index.html?org/apache/kafka/clients/producer/KafkaProducer.html

Consumer API's :

https://kafka.apache.org/090/javadoc/index.html?org/apache/kafka/clients/consumer/KafkaConsumer.html



