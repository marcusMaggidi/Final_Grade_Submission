# Final_Grade_Submission
Student_Grade_Submission_Application

The project utilizes a REST API to manage Student grades, including Create, Update, Delete, and Retrieve operations. Here's an overview of the key features:

1. REST API: A custom REST API has been developed to handle the operations related to students, courses, and grades. The API interfaces with a H2 server, which stores the data.

2. Multi-relational mapping: To establish relationships between entities like student-grade, course-grade, and student-course, multi-relational mapping has been implemented using Spring JPA.

3. 3-Layer Model: The code architecture follows a 3-layer model with a Repository Layer, Service Layer, and Controller Layer.

4. Repository Layer: The Repository Layer inherits from the CRUD Repository class, which provides all the necessary CRUD methods for data manipulation.

5. Service Layer: The Service Layer contains two files, a service interface file, where all the required methods are defined, and a service implementation file, where these methods are implemented.

6. Controller Layer: Within the Controller class, all the HTTP protocols (such as GET, POST, PUT, DELETE) are defined, each with its corresponding handler method to handle the incoming requests.

7. I have additionally added validators, exception handling to my project
