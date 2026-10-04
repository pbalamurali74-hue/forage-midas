# 🏦 Midas Core — Financial Transaction Microservice

A Java/Spring Boot backend developed during the **JPMorgan Chase Advanced Software Engineering Virtual Experience Program** on Forage.

## What this project demonstrates
- Real-time financial transaction ingestion with **Apache Kafka**.
- REST integration with an external incentives service.
- Transaction persistence using **Spring Data JPA**.
- Balance management and REST API exposure.
- Modular backend architecture and Maven-based development.

## Architecture
```
Transaction Events
       ↓
Apache Kafka
       ↓
Kafka Consumer
       ↓
Incentives REST Service
       ↓
Spring Data JPA
       ↓
User / Transaction Records
       ↓
Balance REST API
```

## Tech Stack
Java 17 • Spring Boot • Apache Kafka • Spring Data JPA • Maven • REST APIs

## Run locally
```bash
./mvnw spring-boot:run
```

See the source and configuration files for the exact Kafka and application setup.

## Why it matters
This project demonstrates backend engineering concepts relevant to **Java Developer, Backend Engineer and Software Engineer** roles: event-driven architecture, APIs, persistence and service integration.

## Author
**Purushotham Balamurali**  
[GitHub](https://github.com/pbalamurali74-hue) • [LinkedIn](https://www.linkedin.com/in/purushothambalamurali/)