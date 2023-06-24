<h1 align="center"> 👤User Management System👤</h1>

>### Framework Used 
* [SpringBoot](javatpoint.com/spring-boot-tutorial)

>### Language Used
* [Java](https://www.java.com/en/download/help/whatis_java.html)
>## Data flow
In this project, we have four layers-
* **Controller** - The controller layer handles the HTTP requests, translates the JSON parameter to object, and authenticates the request and transfer it to the business (service) layer. In short, it consists of views i.e., frontend part.
* **Repository** - Here database is stored, for which I have used arrayList. In the database layer, CRUD (create, read, update, delete) operations are performed.
* **Service** -The business layer handles all the business logic. It consists of service classes and uses services provided by data access layers.
* **DataBase Class** - Here the class user is defined and the whatever a user class will load. e.g -userId, userName, address, phone number etc.

>## Data Structure used in my project
In our project [ArrayList](https://www.geeksforgeeks.org/internal-working-of-arraylist-in-java/) and the methods involved with ArrayList, like add method for posting new User, remove method for deleting a user, combination of add and remove method for update user and linear search function for searching a user in Java by specific userId.
>## Project Summary
Our project basically maintains the upcoming user information which includes -
* UserId
* Name
* UserName
* Address
* Phone Number

You can read, read by specific id, update userName of specific userId, delete a user by their userId by api calls.
