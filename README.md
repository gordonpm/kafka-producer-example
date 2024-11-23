## Project Overview
An example of Kafka producer built with Spring Boot. API is provided to send message to Kafka.

### How to Run
1. Start Zookeper with this command:  
<em>bin/windows/zookeeper-server-start.bat</em>  


2. Start Kafka server with this command:  
<em>bin/windows/kafka-server-start.bat</em>  


3. Get API to send message to Kafka:
http://localhost:9191/producer-app/publish/{messageText}  
Expected response is 200 with response text of "Message published successfully".
