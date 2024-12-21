# **** CRUD OPERATION OF STUDENT APPLICATION ****
This CRUD operation for a Student application is a simple system developed using Java and Spring Boot. It utilizes Spring Data JPA for database interaction with MySQL. The application allows basic operations like Create, Read, Update, and Delete (CRUD) for managing student data efficiently.

-id (Long): A unique identifier for each student.<br/>
-name (String): The name of the student.<br/>
-email (String): The email address of the student.<br/>
-course (String): The course the student is enrolled in.<br/>
We'll build a RESTful API that allows clients to interact with student data by performing CRUD operations.

#Steps to Create the Project : 

1. Set Up the Project We'll start by setting up the Spring Boot project with dependencies.

-Spring Web: To build the RESTful API.<br/>
-Spring Data JPA: To interact with the database.<br/>
-MySql Database: A simple, in-memory database for testing.<br/>
-Spring Boot DevTools: For faster development (optional).<br/>

You can generate the project using Spring Initializr (https://start.spring.io/), or you can manually add the dependencies to your pom.xml file.

## Run The Application :

[![student2.png](https://i.postimg.cc/y6ZXKssT/student2.png)](https://postimg.cc/F1hJgtff)


##2. Create the Controller Layer
The controller layer handles HTTP requests and responses. We will expose endpoints for the following operations:

-POST: Create a new student<br/>
-GET: Retrieve a list of all students or a single student by ID<br/>
-PUT: Update an existing student's details<br/>
-DELETE: Delete a student by ID<br/>


#CRUD OPERATION :

Post :
[![student-post.png](https://i.postimg.cc/NFM3yFDL/student-post.png)](https://postimg.cc/njyRgH6t)
#
Get :
[![STUDENT1.png](https://i.postimg.cc/DZm6LGVV/STUDENT1.png)](https://postimg.cc/S2FcpJNV)
#
Delete : 
[![student-delete.png](https://i.postimg.cc/zXLm8L3c/student-delete.png)](https://postimg.cc/Mv83Yp77)

#
Get :
[![student-delete-after.png](https://i.postimg.cc/g2RfLfVy/student-delete-after.png)](https://postimg.cc/k2JjkYhD)


# Links :


### [GitHub]( https://github.com/AKHILTHADAKA?tab=repositories )       ### [Linked in]( https://www.linkedin.com/in/akhilthadaka77/ )     ### [Code-Pen]( https://codepen.io/your-work )


