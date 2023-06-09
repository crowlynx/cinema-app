# 🎬 **CINEMA-APP** 🎬

## 🎥 Description

The main goal of this project was to develop a simple web application for cinema. 
This application will help you automate the work of staff with visitors and orders - 
the administrator can work with the placement of films, cinema halls, sessions and user 
control, and the client can access the library with the search for films, tickets and 
decoration orders. The service supports two-role authentication - admin and user. For unregistered 
website users registration pages are available. The service is simple, easy to use and efficient.

## 🔍 Features

As an "ADMIN", you have access to the following:
* add new cinema hall with capacity and description
* add new movie with title and description
* add new movie session with movie id, cinema hall id and show time
* delete movie session
* update movie session
* get user by email

For "ADMIN" & "USER":
* get available movie session by id and show time
* get all movies
* get all cinema halls

And as a "USER":
* complete order
* add tickets to shopping cart
* get order history
* get shopping cart

Also, registration is available for all.

## 📼 Structure

The structure of this project is presented as follows:
* 📁 сonfig: ---> the Spring configuration used by the application
* 📁 controller: ---> endpoints for the web interface
* 📁 dao: ---> the data access objects and database logic
* 📁 dto: ---> the data transfer object for requests and responses
* 📁 exception: ---> custom processing exception
* 📁 lib: ---> email and password validators
* 📁 model: ---> models as entities in the database
* 📁 security: ---> security configuration
* 📁 service: ---> services and business logic
* 📁 util: ---> utility class

## 🗽️ Instructions

* Install MySQL, TomCat v.9.0.50
* Clone the project from GitHub
* Establish connection with DB (enter your data in the db.properties file)
* Configure and run Tomcat

In the DataInitializer class, the email and password of the admin and user are presented as a test sample,
which you can change if you wish:

"ADMIN"
* email: "admin@i.ua"
* password: "admin123"

"USER"
* email: "user@i.ua"
* password: "user321"

## 🎞️ Technologies

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black)
![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
