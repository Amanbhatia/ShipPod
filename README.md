# ShipPod

A fictitious company that delivers packages using its delivery pods.

## Getting Started

### Prerequisites

* Java 8
* Apache Maven 3.* or higher.

### Executing and Running

In the command window go to project root directory shippod-register-pod-service

```
mvn clean package
java -jar target/shippod-register-pod-service.jar

```

Alternatively, you can also run  the jar by using below maven command.

```
mvn spring-boot:run
```

## Browse and test

Go to the browser and open below URL, to see the WADL
 ```
http://localhost:5000/api/?_wadl.
```
Swagger JSON document URL.
 ```
 http://localhost:5000/api/swagger.json
```
Swagger UI URL.
 ```
 http://localhost:5000/api/api-docs?url=/api/swagger.json
```
