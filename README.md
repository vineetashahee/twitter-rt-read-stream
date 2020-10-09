# Prerequisite

* Java 8 or above
* Basic knowledge of Kafka Producer and Consumer
* Basic knowledge of Elasticsearch
* Twitter Developer account
* Bonsai account, if running Elasticsearch on cloud- Optional

# Installation

## Kafka installation

```bash
brew install kafka
```
Starting Zookeper server
```bash
zokeeper-server-start /usr/local/etc/kafka/zookeeper.properties
```
Starting Kafka server
```bash
kafka-server-start /usr/local/etc/kafka/server.properties
```

## Elasticsearch installation
```bash
brew tap elastic/tap
```
```bash
brew install elastic/tap/elasticsearch-full
```
Starting Elasticsearch server
```bash
cd elasticsearch-7.9.2/bin
./elasticsearch
```
