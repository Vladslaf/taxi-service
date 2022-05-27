# Taxi service application
![](src/main/resources/images/taxi-picture.jpg)

### Functionality:
- Log in and Registration

Signed in users can do:
- Display all Drivers
- Display All Drivers Of Current Driver
- Display all Cars
- Display all Manufacturers
- Create new Driver
- Create new Car
- Create new Manufacturer
- Add driver to car
- Log out
  ![](src/main/resources/images/home-screen.png)

### Project designed and created using SOLID principles and 3-layered architecture:
- DAO - Data access layer
- Service - Application layer
- Controllers - Presentation layer

### Technologies:
- Java 11
- Maven
- Apache Tomcat
- MySQL
- JDBC
- Servlet
- JSTL
- JSP
- HTML, CSS

### How to run this application
1. Install MySQL
2. Install Tomcat 9.0.50 or 9.0.63 version
3. Fork this project to your repository
4. Clone it using one of the "Code" options, which is more suitable for you
5. To initialize the database run this file "src/main/resources/init_db.sql"
WARNING: It will drop an existing database with name "taxi", and create new.
6. Optionally: add some data to database
7. Go to the ConnectionUtil class located in "src/main/java/taxi/util" and add your url to database, login, password.
   (Be careful with adding URL. You might need to add a Timezone to it too)
9. Add configuration: Tomcat Server/local, application context set to "/".
10. Run the project.
