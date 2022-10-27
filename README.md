# Cinema application
Web app for a cinema service.
Supports user registration, operating with cinema halls, movies, movie sessions, adding tickets 
to shopping cart and completing order.

## Available functionality
- User registration, login and log out
- Adding and deleting cinema halls, movies as administrator
- Creating and adding movie sessions as administrator
- Finding available movie sessions by date and time
- Creating shopping cart for a user
- Adding tickets to the cart and completing the order

## Architecture
The app is built using a 3-layer structure
- The DAO layer for DB connection
- The Service layer for the main business logic calculation
- The Controller level to send requests and handle responses

## Technologies
- Java, Maven
- Spring Web, Spring Security, Spring MVC
- Tomcat (9.0.50 version)
- Hibernate
- MySQL

## Instructions
- Fork this repository
- Clone the repository to PC
- Edit db.properties class - set needed parameters to establish connection to your own DataBase
  - db.driver=YOUR_DRIVER
  - db.url=YOUR_DATABASE_URL
  - db.user=YOUR_USERNAME
  - db.password=YOUR_PASSWORD
- Install Apache Tomcat.
- Configure the Tomcat server in your IDEA and Run the project.
