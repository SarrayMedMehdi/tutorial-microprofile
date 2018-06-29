# MicroProfile Tutorial

This tutorial demonstrates the use of MicroProfile technologies for implementing a set of cloud-native microservices. The tutorial is 
made up of a number of Open Liberty Guides each of which demonstrates different MicroProfile technologies. Each Guide is 
designed to be taken independently so if you just want to learn about a specific technology you can just take that guide.  
If, however, you're goal is to learn about all the MicroProfile capabilities, then working through them in the order shown below is recommended.

### Pre-requisites

To use these guides you need the following pre-requisites:
1. A Java 8 JDK (e.g. https://adoptopenjdk.net/?variant=openjdk8-openj9)
1. Apache Maven (https://maven.apache.org/)
1. An editor with Java support (e.g. Eclipse, VS Code, IntelliJ)

## Introduction

Cloud-native is an approach to application development and deployment.  It's the product of a number of industry movements over the past 10-15 years - agile development practices, DevOps, Microservices and Cloud.  Cloud-native applications are developed using agile practices, use continuous integration/continuous delivery to streamline deployment, are architected around team-aligned microservices, and leverage the cloud for rapid deployment at scale.

Cloud-native doesn't change the principals around which solutions are chosen and so often avoiding vendor lock-in is key.  Open source and open standards are essential enablers for avoiding vendors lock-in.  

Eclipse MicroProfile is a set of industry specifications for developing and deploying cloud-native Java Microservices.  The specifications address the important challenges of cloud-native microservices, such as toleration of service failures, security, service metrics and health, and more.

Each guide in this tutorial demonstrates how to address a particular cloud-native microservice need using MicroProfile technology and can be taken independently, or in the order they are introduced, below.

If you have feedback on a specific guide, we'd appreciated a github issue or pull request against that guide, and similarly if you have feedback on this tutorial document.  

### Creating a RESTful web service

Learn how to create a REST service with JAX-RS, JSON-P, and Open Liberty that will expose the JVM’s system properties.

The Guide: https://openliberty.io/guides/rest-intro.html

If you have feedback or find problems, please raise an issue here: https://github.com/OpenLiberty/guide-rest-intro


### Injecting dependencies into microservices    

Learn how to use Contexts and Dependency Injection to manage and inject dependencies into RESTful web services.      
        
The Guide: https://openliberty.io/guides/cdi-intro.html
       
If you have feedback or find problems, please raise an issue here:
https://github.com/OpenLiberty/guide-cdi-intro


### Consuming RESTful services with template interfaces    

Learn how to use MicroProfile Rest Client to invoke RESTful microservices over HTTP in a type-safe way.      
        
The Guide: https://openliberty.io/guides/microprofile-rest-client.html
       
If you have feedback or find problems, please raise an issue here:
https://github.com/openliberty/guide-microprofile-rest-client


### Configuring Microservices

Learn how to inject external static and dynamic configuration to microservices using MicroProfile Config.

The Guide: https://openliberty.io/guides/microprofile-config.html

If you have feedback or find problems, please raise an issue here:
https://github.com/OpenLiberty/guide-microprofile-config


### Building fault-tolerant microservices with the @Fallback annotation

Learn how to use the MicroProfile Fault Tolerance specification to enable applications to function even when one
of the microservices is unavailable.

The Guide: https://openliberty.io/guides/microprofile-fallback.html

If you have feedback or find problems, please raise an issue here:
https://github.com/OpenLiberty/guide-microprofile-fallback
       

### Securing microservices with JSON Web Tokens

You’ll explore how to control user and role access to microservices with MicroProfile JSON Web Token (MicroProfile JWT).

The Guide: https://openliberty.io/guides/microprofile-jwt.html
        
If you have feedback or find problems, please raise an issue here:
https://github.com/OpenLiberty/guide-microprofile-jwt



### Documenting RESTful APIs

Explore how to document and filter RESTful APIs from code or static files by using MicroProfile OpenAPI.

The Guide: https://openliberty.io/guides/microprofile-openapi.html

If you have feedback or find problems, please raise an issue here:
https://github.com/OpenLiberty/guide-microprofile-openapi



 ### Providing metrics from a microservice
 
Learn how to provide system and application metrics from a microservice using MicroProfile Metrics.

The Guide: https://openliberty.io/guides/microprofile-metrics.html
           
If you have feedback or find problems, please raise an issue here:
https://github.com/OpenLiberty/guide-microprofile-metrics



### Adding health reports to microservices
   
Learn how to provide and check the health of a microservice using MicroProfile Health.

The Guide: https://openliberty.io/guides/microprofile-health.html
           
If you have feedback or find problems, please raise an issue here:
https://github.com/OpenLiberty/guide-microprofile-health



### Enabling distributed tracing in microservices

Explore how to enable and customize tracing of JAX-RS and non-JAX-RS methods by using MicroProfile OpenTracing.

The Guide: https://openliberty.io/guides/microprofile-opentracing.html

If you have feedback or find problems, please raise an issue here:
https://github.com/OpenLiberty/guide-microprofile-opentracing

