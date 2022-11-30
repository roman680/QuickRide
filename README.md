# :oncoming_taxi: Taxi-Service :oncoming_taxi:
### Project descriprion:
``` text
This is a basic web-application which allow you to make operations with driver, manufacturer and car.
```
## :zap: Service features :zap:
- register as a driver
- delete a registered driver
- create/delete/update a car
- create/delete/update a manufacturer
- create/delete/update a driver
- display a list of drivers/cars/manufacturer
- add driver to car
- driver logout

#### ⚠️ You need to be registered as a driver to get access to all functions of the app ⚠️

## :wrench: Technologies :wrench:
- Dependency injection and JDBC to word with database
- CRUD operation for each DAO class
- 3-tier architecture  DAO -> SERVICE -> WEB
- Servlet controllers and Filter to handle HTTP requests
- Java 11 and Apache Tomcat 9.0.50

## :question: How to use :question:
- Replace username, password, JDBC driver and URL in `connectionUtil`
- Run script from the `resources/init_db.sql`
- Add `Apache Tomcat 9.0.50`
- Register as a new driver
- Use all functions
- Logout
