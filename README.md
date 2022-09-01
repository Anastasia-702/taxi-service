# Taxi Service

This is web application that supports four basic CRUD operations for working with relational database.
It provides authentication and registration as a driver and allows logged driver to use following
features:

- Create car/manufacturer/driver;
- Display list of all cars/manufacturers/drivers;
- Display list of all cars for currently logged driver;
- Add driver to car;
- Delete car/manufacturer/driver.

## Structure
Project has a three-tier architecture:
1. The presentation tier (controllers);
2. The application logic tier (service);
3. The data tier (DAO).

## Technologies
- Java Servlet API;
- JSP;
- JSTL;
- JDBC API;
- Apache Tomcat v.9.0.50;
- Apache Maven;
- MySQL;
- HTML;
- CSS.

## Launch
1. Clone or download repository;
2. Configure Tomcat (v.9.0.50);
3. Create schema by running script from src/main/resources/init_db.sql in MySql Workbench;
4. Add your database URL, username, password and JDBC driver into corresponding fields in src/main/java/taxi/util/ConnectionUtil;
5. Run the application.
