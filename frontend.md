# Frontend Detailed Documentation

| **Author** | **Created on** | **Last updated by** |**Version**| **Internal Reviewer** | 
|------------|----------------|---------------------|-----------|---------------|
| Manu Saxena | 16-02-25      | Manu Saxena        | v1 | Siddharth Pawar |  | | |

## **Table of Contents**  
1. [Introduction](#introduction)  
2. [Pre-requisites](#pre-requisites)  
3. [System Requirements](#system-requirements)  
4. [Dependencies](#dependencies)  
   - [Build Time Dependency](#build-time-dependency)  
   - [Run Time Dependency](#run-time-dependency)  
5. [Architecture](#architecture)  
6. [Installation of Software Dependencies](#installation-of-software-dependencies)  
7. [Run the Application](#run-the-application)  
8. [Conclusion](#conclusion)  
9. [Contacts](#contacts)  
10. [Reference](#reference)


## Introduction

The Frontend Web is a ReactJS application that serves as the main user interface for the OT-Microservices stack. It works on multiple platforms and only needs JavaScript runtime modules to run. The ReactJS framework enables full web page interactions.

## Pre-requisites

The frontend app depends on REST APIs from OT-Microservices. To run it properly, make sure the following APIs are set up:

Follow the links below for setup instructions:

* **[Employee API](https://github.com/snaatak-Zero-Downtime-Crew/Documentation/blob/Anuj-SCRUM-6/OT%20MS%20Understanding/Application/Employee/POC/README.MD)** <br>
The Employee REST API is a Golang-based microservice that handles employee-related operations. It manages tasks like employee creation, updates, and records in the OT-Microservices stack.<br>

* **[Attendance API](https://github.com/snaatak-Zero-Downtime-Crew/Documentation/blob/Aayush-SCRUM-2/OT%20MS%20Understanding/Applications/Attendance%20/POC/README.md)**<br>
The Attendance REST API is a Python-based microservice responsible for managing employee attendance in the OT-Microservices stack.<br>

* **[Salary API](https://github.com/snaatak-Zero-Downtime-Crew/Documentation/blob/Nikita-SCRUM-8/OT%20MS%20Understanding/Applications/Salary/POC/README.md)**<br>
The Salary API is a Java-based microservice that handles salary-related records and processes within the OT-Microservices stack.<br>

## System Requirements

| Hardware Specifications | Minimum Recommendation |
| ----------------------- | ---------------------- |
| Processor | 1 CPU, t2.micro EC2 | 
| Ram | 1 GiB |
| Disk | 8 GB |
| OS | Ubuntu 24.04 LTS |
***

## Dependencies

### Build Time Dependency

| Name | Version | Description |
| ---- | ------- | ----------- |
| GNU make | 4.4.1 | To build form Makefile |
| npm | 11.1.0 | Package manager for Javasrcipt |

### Run Time Dependency
| Name | Version | Description |
| ---- | ------- | ----------- |
| Nodejs | v23.8.0 | Javasrcipt runtime environment |

## Architecture




## Installation of Software Dependencies

* **[Frontend]()**<br>
To set up the environment for the frontend application follow the above link.

## Run the Application

If the frontend is displayed correctly, the application is up and running.

![frontend](https://github.com/user-attachments/assets/6d7a46a7-5eed-460b-a014-6dbdfd260a3f)


## Conclusion

The OT-Microservices stack consists of a ReactJS frontend and backend services, utilizing Redis for caching, ScyllaDB for NoSQL storage, and PostgreSQL for relational data. It efficiently manages Employee, Salary, and Attendance data. Redis enhances response speed, while ScyllaDB and PostgreSQL provide reliable data storage. This architecture ensures seamless and efficient employee management.

## Contacts

| Name| Email Address      |
|-----|--------------------------|
| Manu Saxena | manu.saxena@mygurukulam.co|




## Reference
|Link |	Description|
|------------------------------------|------------------------------------|
|https://github.com/OT-MICROSERVICES/frontend| Frontend API
