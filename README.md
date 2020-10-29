# Title of the project  

Patient Payment Management System



 # Assignee

Changsheng Liu



# Duration 

06/2020 – Till Time

 

# Object of the project

This main objective of the system is to update the payment system for users who need to pay their bills. The bill payment has been established by years and full of hot fix dispatches. This project is about to create a brand-new system based on up-to-date technology which could recruit enough engineers, provide modern interactive frontpage and cloud support. 

 

# Project Category

Cloud Service Application 

 

# Language and software tool used 

 

Frontend: Angular 

 

Backend: Java EE/Spring Family

 

DataBase: Oracle / MongoDB

 

Platform: Linux with Kubernetes and Docker 

 

# Structure of the project

## Proposed System

In the proposed system, user can pay his/her bill from website or App on the phone. On the other hand, an administrator could monitor the bill payment summary across the platform. The whole system will work on cloud. So the company will never maintain the physical servers any more. 

 

## Module Description

1. RDBMS Module

2. - The database is established by Oracle-11g

3. - Service use JPA to build the connection to database

4. Service Module

5. - Service provide HTTP endpoint by SpringMVC

6. - Service provide transaction function to provide bill payment

7. - Service is based on architecture of microservice.

8. - Service provide multithreading capability as well as consistency of data.

9. Message Module 

10. - Based on RabbitMQ, each microservice could talk with each other by sending and receiving messages in the system

11. Frontend Module 

12. - Use Angular 8 to provide user friendly webpage for patients to pay the bills by either browsers or pages in Apps.

13. Host Service Module

14. - Host all components including DB and each service in Docker as single process.

15. - Manage the whole bunch of processes by Kubernetes. 

16. - Deliver part of the services to AWS