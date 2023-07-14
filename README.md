# :oncoming_taxi: QuickRide :oncoming_taxi:
### Project descriprion:
``` text
This is a basic web-application which allow you to make operations with driver, manufacturer and car.
It is created for internal communication within taxi companies.
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

## :triangular_ruler: Project structure :triangular_ruler:
3 tier architecture 
- DAO -> all interaction with DataBase
- SERVICE -> all busines-logic
- Controller -> work with WEB

## :wrench: Technologies :wrench:
- Java 11 
- Servlet Api
- JDBC
- SQL
- GIT
- Maven
- JSP
- JSTL
- Apache Tomcat 9.0.50
- HTML, CSS

## :question: How to use :question:
- Replace username, password, JDBC driver and URL in `connectionUtil`
- Run script from the `resources/init_db.sql`
- Add `Apache Tomcat 9.0.50`
- Register as a new driver
- Use all functions
- Logout
