# Zero Trust Event-Based Architecture

An exploration into Zero Trust Event-Based Architectures as outlined Gary Archer in his article [How to Build Zero-Trust Event-Based Architectures](https://nordicapis.com/how-to-build-zero-trust-event-based-architectures/).

## Getting Started

1. Deploy Kafka: `docker compose up -d`
2. Create a topic

```shell
docker compose exec broker \
kafka-topics --create \
  --topic purchases \
  --bootstrap-server localhost:9092 \
  --replication-factor 1 \
  --partitions 1
```

3. Run Spring Service?

## Resources

- [Getting Started with Apache Kafka and Java](https://developer.confluent.io/get-started/java/)
