# PCF & Spring Workshop
## Pivotal Software and Perficient St. Louis
Cloud Native application development with Spring, .Net and Pivotal Cloud Foundry. Join Pivotal and Perficient for a full-day hands-on workshop to introduce key concepts in modern cloud native application development and delivery. This workshop will introduce concepts of cloud-native, Spring and .Net application development, and container workload deployments with Pivotal Cloud Foundry, as well as application monitoring with PCF Metrics and platform monitoring with PCF Healthwatch. The labs will leverage Spring Boot 2.0, Spring Actuator, Spring Cloud Data Flow for PCF, and other PCF 2.0 topics.

## Topics
- Cloud Native Architecture and Security
- PCF 2.0 with Pivotal Application Service (PAS) and Pivotal Container Service (PKS) Overview
- What's new in PCF 2.1
- Spring Boot 2.0 apps dev and Spring Actuator
- Application deployment on PAS
- Spring Cloud and Spring Cloud Data Flow (SCDF) for PCF
- Deploying an SCDF workflow to PCF
- Scaling Applications with Autoscaler and CLI
- Deploying container workloads to PKS

**working list of possible topics**
- Cloud Native arch and security (Pivotal)
- PCF 2.0 - Pivotal Application Service (PAS) and Pivotal Container Service (PKS) Overview (Pivotal)
- What's new in PCF 2.1 (Pivotal)
- Deploying apps in containers to PKS (chris)
- Developing apps with .Net and Windows 2016 for PCF (chris)
- Spring Boot 2.0, Actuator Security, Spring Cloud and Spring Cloud Data Flow (SCDF) for PCF (dave & chris)
- PAS Deployment Basics and using SCDF (prft? - create datasource, load data, create flow to transform and push to a destination)
- Scaling Applications with the new Autoscaler and CLI (slides)
- PCF Metrics and PCF Healthwatch (chris)


# ORIGINAL MATERIAL FROM LAST YEAR
**Events**
- Visit [registration](https://pivotal.io/event/cloud-native-workshop/stl) for this workshop. 
- Registration is open for the [Pivotal Cloud Native Roadshow](https://pivotal.io/event/pivotal-cloud-native-roadshow/stlouis) being presented on November 14th, 2016, at Washington University Knight Center. 
- Stay informed for the [2017 SpringOne Platform](https://springoneplatform.io/) to be held in San Francisco, CA, December 4-7, 2017.

## Agenda

Time | Session
---- | -------
8:30 AM - 9:00 AM | _Registration and Breakfast_
9:00 AM - 9:30 AM | _Session 1: Cloud Native Architectures & Frameworks_ (Steve)
9:30 AM - 11:30 AM | _Session 2: Pivotal Cloud Foundry Overview with Labs*_ (Chris)
11:30 AM - 12:00 PM | _Session 3: Spring Boot and Actuator with Labs*_ (Sharath)
12:00 PM - 1:00 PM | _Working Lunch with Guest Speaker from Perficient - Discussion about a Project_ (TBD)
1:00 PM - 2:00 PM | _Session 4: Spring Data on Cloud Foundry with Labs*_ (Steve)
2:00 PM - 3:00 PM | _Session 5: Spring Cloud Services on Cloud Foundry_ (Navjot)
3:00 PM - 4:00 PM | _Session 6: Route Services with Apigee with Labs*_ (Navjot)
4:00 PM - 4:30 PM | _Wrap-up, Q&A, Course evaluation_

_*See [Course Materials](#course-materials) section below for slides and labs_

This is a _loose_ schedule for the day. We will adjust as necessary based on our pace through the material.

The lectures for this workshop are generally light and are only intended to set the stage for the hands-on labs.
The overwhelming majority of our time will be spent engaging with the technology directly!

## Getting started

**Prerequisites**

Start by downloading and installing the appropriate prerequisite tools.
- [Cloud Foundry CLI](https://goo.gl/M0pH4i) to interact with a cloud foundry instance
- [Apache Maven](http://info.pivotal.io/HI002010A6ZlRJR1NeU00eC) to build labs using Maven
- [Gradle](https://services.gradle.org/distributions/gradle-3.1-all.zip) to build labs using Gradle
- [Git Client](https://git-scm.com/downloads) to clone Github repo or download and unzip
- An IDE, like [Spring Tool Suite](https://spring.io/tools/sts/all) or [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
- [Java SE Development Kit](http://info.pivotal.io/n0I60i3021AN0JU0le10CRR)

**Download materials**

Next, download the course materials.  This can be accomplished either through the GitHub website by downloading a repository zip and unzipping locally, or if you have Git installed, use the following commands:

```
$ git clone https://github.com/cbusch-pivotal/stl-cloud-native-spring-workshop
$ cd stl-cloud-native-spring-workshop/
```

**PCF Environments**

Finally, in order to perform the labs, you must be connected or logged into a live PCF environment. Initially you were asked to create a Pivotal Web Services (PWS) account for use in labs and afterwards. Two other environments have also been made available for use. Please see the [Pivotal Cloud Foundry Environment document](Common/env_info.md) for details. You should have been assigned a student number and PCF instance at registration. Otherwise the instructors will provide that information for your use.

## Course Materials

#### _Session 1: Cloud Native Architectures & Frameworks_ [(Slides)](session_01/Session_01-Cloud_Native_Architectures_and_Frameworks-2xpg.pdf)

#### _Session 2: Pivotal Cloud Foundry Overview_ [(Slides)](session_02/Session_02-Pivotal_Cloud_Foundry-The_Cloud_Native_Platform-2xpg.pdf)
  - [Lab 1 - From Zero to Pushing Your First Application](session_02/lab_01/lab_01.adoc)
  - [Lab 2 - Binding to Cloud Foundry Services](session_02/lab_02/lab_02.adoc)
  - [Lab 3 - Scaling Applications](session_02/lab_03/lab_03.adoc)
  - [Lab 4 - Monitoring Applications](session_02/lab_04/lab_04.adoc)

#### _Session 3: Spring Boot and Actuator_ [(Slides)](session_03/Session_03-Spring_Boot_Actuator-2xpg.pdf)
  - [Lab 5 - Introspection, Monitoring, and Metrics using Spring Boot Actuator](session_03/lab_05/lab_05.adoc)

#### _Lunch Session: Perficient_ [(Slides)](session_lunch/pivotal-prft-intellivisit-2xpg.pdf)

#### _Session 4: Spring Data on Cloud Foundry_ [(Slides)](session_04/Session_04-Spring_Data-2xpg.pdf)
  - [Lab 6 - Build a Hypermedia-Driven RESTful Web Service with Spring Data REST](session_04/lab_06/lab_06.adoc)
  - [Lab 7 - Leveraging Spring Cloud Connectors for Service Binding](session_04/lab_07/lab_07.adoc)

#### _Session 5: Spring Cloud Services on Cloud Foundry_ [(Slides)](session_05/Session_05-Spring-Cloud-Services-2xpg.pdf)
_Extra credit - labs can be done on your own!_
  - [Lab 8 - Binding Spring Cloud Services](session_05/lab_08/lab_08.adoc)
  - [Lab 9 - Service Registry](session_05/lab_09/lab_09.adoc)
  - [Lab 10 - Config Server](session_05/lab_10/lab_10.adoc)
  - [Lab 11 - Circuit Breaker Dashboard](session_05/lab_11/lab_11.adoc)

#### _Session 6: Route Services with Apigee_ [(Slides)](session_06/Session_06-Route_Services_and_Apigee_Edge-2xpg.pdf)
  - [Lab 12 - PCF Route Service with Apigee](session_06/lab_12/lab_12.adoc)
  - [Lab 13 - Apigee DevJam](session_06/lab_13/lab_13.adoc)

#### _Wrap-up, Q&A, Course evaluation_ [(Slides)](session_wrapup/Session_Wrap-up-2xpg.pdf) [(Evaluation)](https://goo.gl/forms/aD5y2Rlhn99CZUaA2)

## Hosts and Instructors
- Chris Busch, Pivotal Platform Architect, cbusch@pivotal.io
- Dave Stockmann, Perficient Principle Architect, dave.stockmann@perficient.com
- Cory Jett, Pivotal Platform Architect, cjett@pivotal.io
- Jenny McLaughlin, Pivotal Platform Architect, jmclaughlin@pivotal.io
- Sharath Sahadevan, Pivotal Platform Achitect, ssahadevan@pivotal.io
- Steve Womack, Pivotal Platform Architect, swomack@pivotal.io
- SALES TEAM????

