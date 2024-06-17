# CloudVendor API
 To configure MySQL database for Spring Boot REST API using application.yaml and implement Service and Repository patterns for establishing communication between Spring Boot REST API and MySQL database. Spring Boot Project code structure for REST API is explained. Finally application will be tested by Postman tool and MySQL Workbench. Data exchange format will be used as JSON.
 Session for Controller Layer operations - Create, Read, Update and Delete.
 Exception handling is essential for small to large applications.
 APIs must have exceptions handled properly for giving proper response back to client.
 
# Some Key points for REST API - 

 REST APIs also called as RESTful APIs
# REST = Representational State Transfer 
# API = Application Programming Interface
  REST is a set of architectural constraints, not a protocol or a standard. API developers can implement REST in a variety of ways
  A REST API is an application programming interface that follows the constraints of REST architectural style and allows for interaction with RESTful web services
  REST APIs work over HTTP
  Delivers information using any one of the following formats - 
  JSON (Most popular) ,  Text , HTML , XML , Javascript and more 

#Spring Boot Key points -
@SpringBootApplication for starting
 Easily create stand-alone, production-grade Spring based Applications
 Tomcat, Jetty are embedded
 Provides starter dependencies
 Automatically configure Spring and third party libraries
 Provides production ready features such as health checks, metrics, etc.
 No code generation, No XML configuration.

 
 <img width="1400" alt="Screenshot 2024-05-13 192820ss" src="https://github.com/anjalikhushi/CloudVendor-RESTful-API/assets/82653640/cd686c49-8f2a-4661-90ad-c3bff6f28b4a">
 
Cloud Vendor API is further evolved and junit test cases are written for all 3 layers i.e. controller layer , service layer and repository layer. All layers are unit tested using junit, assertj, mockito, h2database and springframework test package . Code coverage method is also demonstrated in this session. Software testing expected from java developers is explained here.
Unit Testing is mandatory task to perform in java projects from every Java developer. Unit testing java projects helps to enhance java code quality and prevents java spring boot application from bugs. This tutorial will be helpful for backend developers and also for full stack developers.

# JUNIT -
Unit testing framework for Java and its frameworks. 
JUnit 5 is the next generation of JUnit. 
 The goal is to create an up-to-date foundation for developer-side testing on the JVM. This includes focusing on Java 8 and above, as well as enabling many different styles of testing.
# AssertJ -
 AssertJ is a Java library that provides a rich set of assertions and truly helpful error messages.
It improves test code readability, and is designed to be super easy to use within your favorite IDE.
# Mockito  -
 Mockito is a mocking framework for Java. 
 It lets you write beautiful tests with a clean & simple API. 
 The tests are very readable and they produce clean verification errors.
 Mockito 3.x requires Java 8 or above.
# H2 Database -
 H2 Database is Java SQL Database
 Very fast and open source
 Used as In-Memory Database
 Spring Boot can auto-configure embedded H2 databases. 
 # Unit Testing
<img width="650" alt="test" src="https://github.com/anjalikhushi/CloudVendor-RESTful-API/assets/82653640/6f5ee9a8-0d14-49bc-a98d-1e99ddce1e31">

<img width="650" alt="test1" src="https://github.com/anjalikhushi/CloudVendor-RESTful-API/assets/82653640/c0645bd2-7d28-4889-84aa-5230fa293e2f">

# Swagger API Documentation

API Documentation is essential part of any REST API application. Swagger addresses the burning problem of api developers and cuts down the pain of manual documentation and auto generates the required api documentation. Swagger generates document for Java Spring Boot REST ASPI application automatically.

<img width="650" alt="swagger" src="https://github.com/anjalikhushi/CloudVendor-RESTful-API/assets/82653640/6fa106b5-79a5-4007-8634-985771b81192">

<img width="650" alt="swagger2" src="https://github.com/anjalikhushi/CloudVendor-RESTful-API/assets/82653640/e214fe13-42fc-4554-917f-272497a94f5f">

# Spring boot Actuator

Spring boot actuator is very helpful for building production ready spring boot applications. spring actuator in spring boot provides lot of operational features which helps for managing the spring boot apps such as monitoring , audit and health checks. In this spring boot actuator tutorial we will learn actuator spring boot from the basics to the implementation in a cloud vendor project using Maven build tool. 

# Key points -
1. Production Ready features
2. Manage / monitor spring boot application using HTTP or JMX - Audit, Health, Metrics
3. “spring-boot-actuator” module provides all the production ready features
4. Dependency - “spring-boot-starter-actuator”
5. HTTP base endpoint - /actuator

<img width="650" alt="actuator1" src="https://github.com/anjalikhushi/CloudVendor-RESTful-API/assets/82653640/d32f2ac9-f91f-41d8-9828-9cfffa25ab05">


<img width="650" alt="actuator" src="https://github.com/anjalikhushi/CloudVendor-RESTful-API/assets/82653640/47b6effd-8e1e-4aae-a92a-9d3494e19624">






