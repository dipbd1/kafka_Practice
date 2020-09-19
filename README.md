**

# Hello There,


I am **Dip** and I was practicing ***kafka***. If everything Goes  well,
it's highly possible I am now at architect level where I dont need to code anymore. 
Thats **github**, for reminding me I can code!

 

## So
Here run 

    node producer.js

to make some topic and inject data on them.

And, run 

    consumer.js

# Kafka

**Start Zookeeper**

    bin/zookeeper-server-start.sh config/zookeeper.properties

**Start Kafka Server**

    bin/Kafka-server-start.sh config/server.properties

**Topic list**

    bin/Kafka-topics.sh --list --zookeeper localhost:2181

**We can also consume data from a Kafka topic by running the consumer console command on the terminal, as shown below**

    bin/kafka-console-consumer.sh --bootstrap-server localhost:9092  --topic kafka-example-topic --from-beginning


to have a realtime watch on them.

Wallah!! So easy. But people are now using kafka js instead of kafka-node!

