# kafka-cheat-sheet

#### Start Zookeper
```
bin/zkServer.sh start
```

#### Zookeper Cli
```
bin/zkCli.sh
```

#### Stop Zookeper
```
bin/zkServer.sh stop
```

#### Kafka Start
```
bin/kafka-server-start.sh config/server.properties
```

#### Kafka Stop
```
bin/kafka-server-stop.sh config/server.properties
```

#### Kill Kafka 
```
kill $(lsof -t -i:9092) 
```

#### Kill Zookeper
```
kill $(lsof -t -i:2181)
```

#### Create Topic
```
bin/kafka-topics.sh --create --zookeeper zookeper-ip:zookeperport --replication-factor 1 --partitions 1 --topic topic-name
```

