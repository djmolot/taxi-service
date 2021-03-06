# Taxi-Service
### Project description:
```
Web application that supports authentication, registration and CRUD operations with implemented UI.
```
## Features:
- registration like a driver;
- authentication like a driver;
- create/update/remove a manufacturer;
- create/update/remove a car;
- create/update/remove a driver;
- display list of all manufacturers;
- display list of all cars;
- display list of all drivers;
- display list of all cars by current driver;
- add driver to car.
## Project structure (3-layer architecture):
- DAO - Data access layer
- Service - Application logic layer
- Controllers - Presentation layer
## Used technologies and libraries:
- Java 11
- Git
- Apache Maven
- Apache Tomcat
- Apache Log4j 2
- MySQL
- JDBC
- Javax Servlet
- JSP
- JSTL
- HTML/CSS
- Checkstyle plugin
- Project Lombok
## Startup instructions
To start the project, you need to install and configure the Tomcat servlet container (version 9.0.50) in IntelliJ IDEA (Ultimate version);
Configure the connection to the database in the ConnectionUtil class;
Data for creating schema and tables (if not exists) can be found in the init_db.sql file (resource folder);
Run Tomcat.