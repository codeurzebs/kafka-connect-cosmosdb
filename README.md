# Kafka Connect for Azure Cosmos DB
________________________

**Kafka Connect for Azure Cosmos DB** consists of 2 connectors - a [Source Connector](./doc/README_Source.md) and a [Sink Connector](./doc/README_Sink.md). 

The Source Connector is used to pump data from [Azure Cosmos DB](https://azure.microsoft.com/services/cosmos-db//) via its Change Feed to
[Apache Kafka](https://kafka.apache.org/). 

The Sink Connector reads messages from Kafka and sends them to Cosmos DB. 


## Contribute
This project welcomes contributions, feedback and suggestions. 
If you would like to become a contributor to this project, please refer to our [Contribution Guide](CONTRIBUTING.MD).

## Setup

## Configuration

## References
It is worth looking through this material to get better understanding of how Kafka Connect and these connectors work and how to use them. 

[Kafka Connect](https://docs.confluent.io/current/connect/index.html)
[Kafka Connect Concepts](https://docs.confluent.io/current/connect/concepts.html)
[Installing and Configuring Kafka Connect](https://docs.confluent.io/current/connect/userguide.html)
[Tutorial: Moving Data In and Out of Kafka](https://docs.confluent.io/current/connect/quickstart.html)

It is also worth understanding how Cosmos DB and its Change Feed works

[Cosmos DB]()
[Cosmos DB Change feed](https://docs.microsoft.com/azure/cosmos-db/change-feed)
[Cosmos DB Change feed processor](https://docs.microsoft.com/en-us/azure/cosmos-db/change-feed-processor)