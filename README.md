# KAFKA-EX-03
This project is the third homework assignment for the Kafka course.   It demonstrates the basic usage of **Apache Kafka  with Java and Maven, focusing on producer–consumer architecture and message streaming.

##  Features
- Java project built with **Maven**
- Implementation of a **Kafka Producer** to send messages
- Implementation of a **Kafka Consumer** to read messages
- Configurations for topic creation, serialization, and message handling
- Docker usage for running Kafka locally

---

##  Technologies Used
- **Java 17**
- **Apache Kafka**
- **Maven**
- **Docker & Docker Compose**

---

##  Project Structure
kafka-03-homework/
│── src/
│   └── main/java/com/example/kafka/
│       ├── ProducerApp.java
│       ├── ConsumerApp.java
│       └── …
│── pom.xml
└── README.md

<img width="970" height="539" alt="Screenshot 2025-09-09 at 14 29 14" src="https://github.com/user-attachments/assets/7ae17e2e-927f-437e-bd6a-b4039d5201e2" />

## Start Kafka with Docker
docker-compose up -d

## Build the project
mvn clean package

## Run Producer
mvn exec:java -Dexec.mainClass="com.example.kafka.ProducerApp" 
<img width="731" height="786" alt="Screenshot 2025-09-09 at 14 37 15" src="https://github.com/user-attachments/assets/a401b1fb-2c43-4db0-9adf-7c827a982b1e" />
<img width="1103" height="610" alt="Screenshot 2025-09-09 at 14 38 18" src="https://github.com/user-attachments/assets/e3729429-1c53-4f85-88eb-c633d589c71c" />

## Run Consumer
mvn exec:java -Dexec.mainClass="com.example.kafka.ConsumerApp"
<img width="1129" height="786" alt="Screenshot 2025-09-09 at 14 39 15" src="https://github.com/user-attachments/assets/5240b659-6b7b-478f-bf9c-47efaf3f3f94" />
<img width="1126" height="791" alt="Screenshot 2025-09-09 at 14 39 51" src="https://github.com/user-attachments/assets/98a03db6-3861-4595-878b-94c6217a7801" />
<img width="1114" height="789" alt="Screenshot 2025-09-09 at 14 40 51" src="https://github.com/user-attachments/assets/fd0641b2-1c3d-45b7-b46f-aa21096405cb" />

## Summary
- This demonstrates that the **Kafka Producer–Consumer communication** works correctly.  
- By observing the successful sending and receiving of messages, the homework requirements are fulfilled.  




