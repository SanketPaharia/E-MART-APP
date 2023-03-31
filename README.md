# E-MART-APP

This is a full-stack E-commerce web application built with Spring Boot, designed to allow users to browse, search, and purchase products online.
The application includes a variety of features commonly found in e-commerce websites,including a user registration and login system, product search and filtering, shopping cart functionality, order management.

## Installation & Run

* Before running the API server, you should update the database config inside the application.properties file.

* Update the port number, username and password as per your local database configuration.

```
    server.port=5000

    spring.datasource.url=jdbc:mysql://localhost:3306/prd;
    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
    spring.datasource.username=root
    spring.datasource.password=root
```

## Services

- User Service
- Cart Service
- Product Service
- Promo Code Service
- Wallet Service
- Category Service


