
---

## Spring Cloud Setup

This project is a **Docker Compose** file that contains [Eureka](https://bitbucket.org/spacebarmediadev/eureka-service/), [Config Server](https://bitbucket.org/spacebarmediadev/config-server) [Api Gateway](https://bitbucket.org/spacebarmediadev/api-gateway) and [Admin Service](https://bitbucket.org/spacebarmediadev/admin-service) components with a **PostgreSQL DB** and **Amazon DynamoDB**, ready to be integrate with any microservice implemented locally


###Instalation
1. git clone https://{your_user}@bitbucket.org/spacebarmediadev/cloud-in-local.git
2. cd cloud-in-local
3. docker-compose up
4. if it desired to run it by parts:
    *   docker-compose -f core.yml up
    *   docker-compose -f microservices.yml up  


###Links
* Eureka: [http://localhost:8761](http://localhost:8761)
* Admin: [http://localhost:7500](http://localhost:7500)
* PostgreSQL DB [http://localhost:5432](http://localhost:5432)
* DynamoDB DB [http://localhost:8000/shell/](http://localhost:8000/shell/)


###Create PostgreSQL DB's

DB details as follows:
* Host: **localhost**
* Port: **5432**
* DB: **postgres**
* Username: **postgres**
* Password: **postgres**

To create a DB instance type the command below:

**CREATE DATABASE mydb OWNER postgres;**

