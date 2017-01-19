## Docke Kafka Streams Example

Featuring:

- Docker 1.12.0
- Docker Compose 1.8.0
- Docker Machine 0.8.0
- Kafkacat 0.8.6
- Zookeeper 3.4.6
- Kafka 0.10.0.1

Step1: docker-compose up (start Kafka broker)

Step2: Run Java App (Require 1.8)

Step3: kafkacat -b 127.0.0.1 -t words-topic -P (Producer)

Step4: kafkacat -b 127.0.0.1 -t counts-topic -C (Consumer)

Ref -> https://www.hugopicado.com/2016/10/05/stream-processing-with-kafka-streams.html