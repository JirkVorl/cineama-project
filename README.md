# Cinema Service

This is fully functioning web application, that represents cinema service. It allows user (with admin role) to manage a list of movies, cinema halls, movie sessions and tickets. 
Every user has his own shopping cart, where he can choose session, cinema hall etc. 
It uses 3-Tier architecture: 
1. DAO layer - implements database access.
2. Service layer - implements all business logic.
3. Controllers layer - responsible for breakpoints, that allows user to use app.
All functionality and technologies are described below.

## Functionality list:
* Authorization and authentication of user (With user/admin roles)
* Admin can manage movies, cinema halls and movie sessions
* User can generate and add tickets to shopping cart
* Create orders

## Used Technologies
* Java (ver. 11)
* Maven
* Tomcat
* Spring Core
* Spring Security
* Spring MVC
* Hibernate
* MySQL Database

## Used Patterns
* DAO
* DTO

# Things you should do if you want to try it yourself:
1. Fork this repo
2. Clone to your IDE 
3. Edit db.properties file. Set your parameters here:
```java
    db.driver=YOUR_DRIVER
    db.url=DATABASE_URL
    db.user=YOUR_USERNAME
    db.password=YOUR_PASSWORD
```
5. Install and configure Tomcat version 9.0.50
6. Run
7. I recommend to use Postman to send http requests, because this has no interface.
