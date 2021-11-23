# webinar-kafka-demo
### MNDWRK - Apache Kafka Webinar

## Getting started

```console
docker-compose up -d

kafka-console-producer --topic meetup-demo-inbound --bootstrap-server localhost:9092

```

#### Payload
```json
{"source": "CCTV", "description":"Green signal"}
```