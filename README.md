# Cinema Service

This is fully functioning web application, that represents cinema service. It allows user (with admin role) to manage a list of movies, cinema halls, movie sessions and tickets. 
Every user has his own shopping cart, where he can choose session, cinema hall etc.
All functionality and technologies are described below.

## Functionality list:
* Authorization and authentication of user (With user/admin roles)
* User CRUD operations
* Movie CRUD operations
* Movie session CRUD operations
* Cinema hall CRUD operations
* Generate and add tickets to shopping cart
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
* SOLID
* DAO
* DTO
* N-tier architecture

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
7. I recommend to use Postman to throw http requests, because this has no interface.
