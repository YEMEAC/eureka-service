# Eureka-service


This repository is part of a tripled of microservices to play with Eureka service discovery. In this trippled, this  microservice plays the role as eureka-service, the other microservices will register them self and talk to each other consuming this service as "address book" we could say. 
To execute:

```
gradle bootRun
```

This service will be running on port: 8761. To see eureka dashboard:

```
  http://localhost:8761/
```
