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

 
