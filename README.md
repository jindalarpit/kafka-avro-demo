# Learning

# Content

 - Avro examples
 - Kafka Avro Producer & Consumer
 - Schema Evolutions

# Setup

Run `mvn clean package` in all sub-projects to generate java class for avro schema

using podman kafka environment can be created using following command

```aidl
podman run --rm -p 2181:2181 -p 127.0.0.1:3030:3030 -p 127.0.0.1:8081-8083:8081-8083 \                                                       ─╯
       -p 127.0.0.1:9581-9585:9581-9585 -p 127.0.0.1:9092:9092 -e ADV_HOST=127.0.0.1 \
       lensesio/fast-data-dev:latest
```
