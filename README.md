# Mondi Data Manager

The base docker-kafka is based on wurstmeister/kafka-docker: https://github.com/wurstmeister/kafka-docker

## introduction

In this docker Kafka, the data producer and consumer are manually put into then
producers and consumers repository.

## Adding topics

Topics can be added in the docker-compose.yml file

## Get up and running

To get up and running, first build an image:

```
docker build -t data_manager_kafka
```

Check that the image is there

```
docker image ls
```

Run Kafka

```
docker-compose up
```

## To note

The java data producers and consumers are automatically built with class defined.
