
---

## Spring Cloud Setup

This project is a **Docker Compose** file that contains [Eureka](https://github.com/gnovoab/discovery-service), [Config Server](https://github.com/gnovoab/config-service), [Api Gateway](https://github.com/gnovoab/api-gateway), and [Admin Service](https://github.com/gnovoab/admin-service) components with a **PostgreSQL DB**, ready to be integrate with any microservice implemented locally


###Instalation
1. git clone https://github.com/gnovoab/cloud-in-local.git
2. cd cloud-in-local
3. docker-compose up
4. if it desired to run it by parts:
    *   docker-compose -f core.yml up
    *   docker-compose -f microservices.yml up  


###Links
* Eureka: [http://localhost:8761](http://localhost:8761)
* Admin: [http://localhost:7500](http://localhost:7500)
* PostgreSQL DB [http://localhost:5432](http://localhost:5432)


###Create PostgreSQL DB's

DB details as follows:
* Host: **localhost**
* Port: **5432**
* DB: **postgres**
* Username: **postgres**
* Password: **postgres**

To create a DB instance type the command below:

**CREATE DATABASE mydb OWNER postgres;**

