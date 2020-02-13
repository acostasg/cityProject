# Spring Boot PostgreSQL tutorial

Spring Boot PostgreSQL tutorial shows how to use PostgreSQL database in a Spring Boot application.

```
pom.xml
src
├───main
│   ├───java
│   │   └───com
│   │       └───zetcode
│   │           │   Application.java
│   │           ├───controller
│   │           │       MyController.java
│   │           ├───model
│   │           │       City.java
│   │           ├───repository
│   │           │       CityRepository.java
│   │           └───service
│   │                   CityService.java
│   │                   ICityService.java
│   └───resources
│       │   application.properties
│       │   data-postgres.sql
│       │   schema-postgres.sql
│       ├───static
│       │       index.html
│       └───templates
│               showCities.html
└───test
    └───java
```

Run:

```sh
mvn spring-boot:run 
```

More information: 
http://zetcode.com/springboot/postgresql/

Requeriments:

* Java sdk 1.8
* Mavem 


