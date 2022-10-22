# Aplicaçoes para comparação do desempenho de Message Brokers (Apache Kafka vs RabbitMQ)

## RabbitMQ

#### Como subir container do RabbitMQ?

```shell
$ cd rabbitmq
$ docker-compose --compatibility up -d
```

#### Rodar aplicação de benchmark

```shell
cd rabbitmq
$ java -jar perf-test-latest.jar
```

#### Obs: É necessário que o java esteja instalado na máquina.

## Apache Kafka

#### Como subir container do Apache Kafka?

```shell
$ cd kafka
$ docker-compose --compatibility up -d
```


docker run  -v ./output/:/tmp/output gkoenig/kafka-producer-benchmark:0.1 --bootstrap-servers localhost:9092
