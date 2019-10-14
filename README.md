# Microservices made easy with MicroProfile & Open Liberty

## Introduction
Cloud-native is an approach to application development and deployment. It's the product of a number of industry movements over the past 10-15 years - agile development practices, DevOps, Microservices and Cloud. Cloud-native applications are developed using agile practices, use continuous integration/continuous delivery to streamline deployment, are architected around team-aligned microservices, and leverage the cloud for rapid deployment at scale.

When choosing which technologies to use for cloud-native microservices, the combination of open source and open standards can be very important. The combination enables a low cost (free) of entry and at the same time avoids being locked in to a single vendor implementation.

### MicroProfile

![alt text](https://github.com/jamiecoleman92/microservices-made-easy/raw/master/microprofile_logo_new.png "MicroProfile Logo")


Eclipse MicroProfile is a set of industry specifications for developing and deploying cloud-native Java Microservices. The specifications address the important challenges of cloud-native microservices, such as toleration of service failures, security, service metrics and health, and more. Open Liberty is an open source, lightweight, composable Java server that implements the MicroProfile specifications.

### Open Liberty

![alt text](https://github.com/jamiecoleman92/microservices-made-easy/raw/master/OL_logo_navy.png "Open Liberty Logo")


Open Liberty is fast to start up with a low memory footprint and live reload for quick iteration. Simple to add and remove features from the latest versions of MicroProfile and Jakarta EE. Zero migration let’s you focus on what's important, not the APIs changing under you.

### Kubernetes

![alt text](https://github.com/jamiecoleman92/microservices-made-easy/raw/master/kubernetes_logo.png "Kubernetes Logo")


Kubernetes is an Open Source platform for deployment, scaling and managing containers and services. It uses a declarative yaml-based approach to describe deployments, for example, the containers to be deployed, their scaling requirements, the services they provide, and so on.

This workshop demonstrates how to address cloud-native microservice requirements using the combination of MicroProfile, Docker and Kubernetes technologies.

If you have feedback on a specific guide, we'd appreciated a github issue or pull request against that guide, and similarly if you have feedback on this workshop document, please raise an issue or submit a pull request.

If you want to learn more about MicroProfile, Open Liberty and Kubernetes after you have finished this workshop, head over to our developer site and try out some more guides

https://openliberty.io/guides/
![alt text](https://github.com/jamiecoleman92/microservices-made-easy/raw/master/guides.png "Guides Site")
## Pre-requisites

To use these guides you need the following pre-requisites:
1. A Java 8 JDK (e.g. https://adoptopenjdk.net/?variant=openjdk8&jvmVariant=openj9)
2. Apache Maven 3.5.4 or later (https://maven.apache.org/). Older versions may not work.
3. A git client
4. An editor with Java support (e.g. Eclipse, VS Code, IntelliJ)
5. Docker & Kubernetes:
   1. Windows: https://docs.docker.com/docker-for-windows/#kubernetes 
   2. Mac: https://docs.docker.com/docker-for-windows/#kubernetes
   3. Linux: https://github.com/kubernetes/minikube#installation)

## Lets start making microservices already!

This workshop is comprised of three guides and one bonus guide for those feeling adventorus. You can take the guides in any order you like but I would suggest doing them in the order bellow. Once you have finished a guide please go back to this page and select the next one from the list!

If you have any questions/problems please feel free to ask me anything. Happy Coding!

 ### Building fault-tolerant microservices with the @Fallback annotation

![alt text](https://github.com/jamiecoleman92/microservices-made-easy/raw/master/fault_tolerance.PNG "Fault Tolerance")

Learn how to use the MicroProfile Fault Tolerance specification to enable applications to function even when one
of the microservices is unavailable.

The Guide: https://openliberty.io/guides/microprofile-fallback.html

If you have feedback or find problems, please raise an issue here:
https://github.com/OpenLiberty/guide-microprofile-fallback

### Checking the health of microservices on Kubernetes

![alt text](https://github.com/jamiecoleman92/microservices-made-easy/raw/master/health.PNG "Health")

Learn how to check the health of microservices on Kubernetes by setting up readiness probes to inspect MicroProfile Health Check endpoints.

The Guide: https://openliberty.io/guides/kubernetes-microprofile-health.html

If you have feedback or find problems, please raise an issue here:
https://github.com/OpenLiberty/guide-kubernetes-microprofile-health

### Documenting RESTful APIs

![alt text](https://github.com/jamiecoleman92/microservices-made-easy/raw/master/openapi.PNG "OpenAPI")

Explore how to document and filter RESTful APIs from code or static files by using MicroProfile OpenAPI.

The Guide: https://openliberty.io/guides/microprofile-openapi.html

If you have feedback or find problems, please raise an issue here:
https://github.com/OpenLiberty/guide-microprofile-openapi

## Extra

### Providing metrics from a microservice
 
![alt text](https://github.com/jamiecoleman92/microservices-made-easy/raw/master/metrics.PNG "Metrics")

Learn how to provide system and application metrics from a microservice using MicroProfile Metrics.

The Guide: https://openliberty.io/guides/microprofile-metrics.html

If you have feedback or find problems, please raise an issue here:
https://github.com/OpenLiberty/guide-microprofile-metrics

![alt text](https://github.com/jamiecoleman92/microservices-made-easy/raw/master/OL_logomark_400_wht.png "Open Liberty Logo")