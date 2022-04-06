# nodejs-kafka

NOTE: Please use kafka and java version carefully. I have installed kafka version 3, but was not working for me

# Requirements

1. kafka_2.12-2.8.1
2. java v17.0.2

# Steps to start the service

1. First start Kafka Zookeeper
   .\bin\zookeeper-server-start.sh .\config\zookeeper.properties
2. Start the kafka server
   .\bin\zookeeper-server-start.sh .\config\server.properties
3. Start the node js program node .\index.js

# Core Concepts

1. Cluster
2. Broker
3. Producer
4. Consumer
5. Connector
6. Streams

# Reference

https://www.sohamkamani.com/nodejs/working-with-kafka/
https://www.sohamkamani.com/install-and-run-kafka-locally/
https://www.youtube.com/watch?v=udnX21__SuU
https://www.youtube.com/watch?v=aj9CDZm0Glc
