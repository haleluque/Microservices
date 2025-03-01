# Microservice Spring Application

Spring boo project with basic microservices communication with spring cloud

This is a fully built microservices Spring boot application example:
- Spring boot version: 3.4.2
- Java version: 21
- Maven version: 3.9.6

## Main Features

### Limits Service Microservice
- Ports: 8080, 8081, etc.
- Microservice that will retrieve info from the cloud configuration server
- Use of profiles to handle different environments

### Spring Cloud Service
- Ports: 8888
- This service project will have the rol of configuration server, which will provide properties centralized configuration properties for different microservices
- For this example, spring cloud service will be extracting the information from the following repo:
https://github.com/haleluque/git-localconfig-repo