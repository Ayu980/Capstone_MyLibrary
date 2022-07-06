# Springboot Application
## MyLibrary
MyLibrary is a simple web application, a user can store and retrive Books information. 

### Technologies 
* SpringBoot
* Maven
* Java Corretto 11
* Spring JPA
* MariaDB
* Spring Security
* Thymeleaf
* Lombok
* BootStrap
* HTML
* CSS
### Business Requirement
To create a basic personal library web application where users can sign up and store, retrive and view their books.
### Work-Flow
Website with links to each service
* homepage
* books 
* categoris 
* author
* publisher
### Models
* models requires:
* no args constructor
* all args constructor
* required args constructor
* setters and getter
* toString (exclude collections to avoid infinite loops)
* override equals and hashcode methods (don't use lombok here)
* helper methods

Book (@Table(name = "Books")

Field | Datatype | Description | Database Attributes
| :--- | ---: | :---: | :---:
id  | Long  | Book unique id | Primary Key
name  | String | Book Name | 100 Characters, not null
ISBN  | String | Book uiniqe code | 100 Characters, not null
description | String | Information about the book | 250 Characters 


@Author

Field | Datatype | Description | Database Attributes
| :--- | ---: | :---: | :---:
id  | Long  | Book unique id | Primary Key
name  | String | Book Name | 100 Characters, not null
ISBN  | String | Book uiniqe code | 100 Characters, not null
description | String | Information about the book | 250 Characters 

