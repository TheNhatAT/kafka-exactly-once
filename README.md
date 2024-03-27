Demo fork from kafka open source repo

--
This module contains some Kafka client examples.

Start a Kafka 2.5+ local cluster with a plain listener configured on port 9092.
Run ./bin/java-producer-consumer-demo.sh 10000 to asynchronously send 10k records to topic1 and consume them.
Run ./bin/java-producer-consumer-demo.sh 10000 sync to synchronous send 10k records to topic1 and consume them.
Run ./bin/exactly-once-demo.sh 6 3 10000 to create input-topic and output-topic with 6 partitions each, start 3 transactional application instances and process 10k records.