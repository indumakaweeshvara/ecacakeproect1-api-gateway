# EcaBookshop API Gateway

API Gateway component of the EcaBookshop microservices architecture.

## Student Information
- **Student Name**: Induma Kaweeshvara
- **Student Number**: 241722023

## Repository Description
The API Gateway acts as the single entry point for all client requests in the EcaCakeProject1 architecture. It handles routing and forwards calls to the appropriate microservices (Customer, Cake, and Order services) via Spring Cloud Gateway.

## Technology Stack
- **Framework**: Spring Boot
- **Infrastructure**: Spring Cloud Gateway, Spring Cloud Starter Netflix Eureka Client
- **Build Tool**: Maven

## Setup / Getting Started Instructions
1. Ensure the Service Registry is running on port `9001` and Config Server on `9000`.
2. Build the application using Maven:
   ```bash
   mvn clean package -DskipTests
   ```
3. Run the application:
   ```bash
   java -jar target/api-gateway-1.0.0.jar
   ```
   The gateway will start on port `7000`.
