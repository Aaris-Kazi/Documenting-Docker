# Kafka Run on Docker

### Pull the latest image
    docker pull apache/kafka:latest
    
### Run the latest image
    docker run -d --name broker -p 9092:9092 apache/kafka:latest

### Docker execute the shell script
    docker exec --workdir /opt/kafka/bin/ -it broker sh

### Create the topic
    ./kafka-topics.sh --bootstrap-server localhost:9092 --create --topic test-topic
