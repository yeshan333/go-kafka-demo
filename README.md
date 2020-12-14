# Kafka Tour with Go

> article: [Play the Kafka](https://shansan.top/2020/12/13/%E8%80%8D%E4%B8%80%E4%B8%8BKafka/)

## Qucikstart

- requirements：
  - docker
  - docker-compose v3
  - Go 1.12+

1、Deploy Kafka & Zookeeper

```shell
git clone https://github.com/yeshan333/go-kafka-demo
cd go-kafka-demo
docker-compose up
```

2、install deps

```shell
go mod download
```

3、start the consumer & producer client

```shell
# terminal 1
go run kafka_producer.go
# terminal 2
go run kafka_consumer.go
```