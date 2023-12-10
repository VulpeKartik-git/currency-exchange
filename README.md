# currency-exchange

Title: Spring Boot Microservices: Currency Conversion System with Netflix Eureka and Distributed Tracing using Zipkin

Description:

Welcome to the Currency Conversion System, a resilient and scalable microservices architecture built using Spring Boot and seamlessly hosted on the Netflix Eureka naming server. This project consists of two main microservices: the currency-exchange-service and currency-conversion-service. These microservices communicate with each other via a Feign-based REST client, providing a robust and fault-tolerant solution for currency-related operations. I have seamlessly integrated distributed tracing using Zipkin, allowing you to trace and monitor requests across your microservices. Additionally, Zipkin has been effortlessly launched as a Docker image on your local system to facilitate efficient tracking and analysis.

Key Features:

Microservices Architecture: The project is designed around two microservices, each serving a specific purpose—currency exchange rates retrieval and currency conversion.

Feign REST Client: The microservices seamlessly communicate with each other through a Feign-based REST client, ensuring simplicity and ease of integration.

Service Discovery with Netflix Eureka: Hosted on the Netflix Eureka naming server, the microservices dynamically discover and register with each other, enabling effortless communication and scalability.

API Gateway: All microservices traffic is efficiently managed and routed through a centralized entry point provided by the Spring Cloud Gateway.

Logging Filter: The Spring Cloud Gateway incorporates a logging filter, offering comprehensive insights into the request/response lifecycle for enhanced debugging and monitoring.

Fault Tolerance with Resilience4j: Resilience4j is utilized to build fault-tolerant microservices, ensuring robustness even in the face of transient failures.

Actuator Endpoints: Monitoring and managing the microservices are simplified with Spring Boot Actuator, providing various endpoints for health checks, metrics, and operational functionalities.

Dependencies Used:

spring-boot-starter-actuator
spring-cloud-starter-gateway
spring-cloud-starter-netflix-eureka-client
spring-boot-devtools
spring-boot-starter-test
[Other required dependencies]
How to Use:

Currency Exchange Service: Obtain real-time currency exchange rates by interacting with the currency-exchange-service.

Currency Conversion Service: Utilize the currency-conversion-service to convert a specified quantity of one currency to another.

API Gateway: Access the entire system efficiently through the API Gateway, managing and routing traffic seamlessly.

Distributed Tracing: Leverage Zipkin to trace requests across microservices, gaining insights into the entire request flow for efficient monitoring and optimization.

Explore the power of Spring Boot and microservices hosted on Netflix Eureka with this Currency Conversion System, providing flexibility, scalability, and fault tolerance for your currency-related operations.

To use: To use this microservice projct clown the below four repositories and run it on your IDE.
1.api-gateway
2.naming-server
3.currency-exchange-service
4.currency-conversion-service
