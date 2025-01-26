Todo App
A simple Todo Application built using Spring Boot, demonstrating the use of RESTful APIs, JPA, and database integration. This app allows users to manage their to-do tasks through basic CRUD operations.

Features
* Create a new to-do task
* Read all to-do tasks
* Update an existing to-do task
* Delete a to-do task
  
Technologies Used
* Java 18
* Spring Boot (for building the backend)
* Spring Data JPA (for database interaction)
* H2 Database (for lightweight, in-memory database)
* Maven (for dependency management)
  
Setup Instructions
1. Clone the repository - git clone https://github.com/your-username/todo-app.git
2. Navigate to the project directory - cd todo-app
3. Build the project with Maven - mvn clean install
4. Run the application
You can run the application using Maven: mvn spring-boot:run
By default, the application will run on http://localhost:8080.

5. Access the API Endpoints
GET http://localhost:8080/api/todos: Get all to-do tasks
POST http://localhost:8080/api/todos: Create a new to-do task
PUT http://localhost:8080/api/todos/{id}: Update an existing to-do task
DELETE http://localhost:8080/api/todos/{id}: Delete a to-do task
Example POST request (Create a Todo)
To create a new to-do task, send a POST request with the following body:

{
  "title": "Buy groceries",
  "description": "Milk, Eggs, Bread",
  "done": false
}


![image](https://github.com/user-attachments/assets/5de50418-d4f2-459e-a1ea-bf0134e435d2)


Project Structure

![image](https://github.com/user-attachments/assets/03edfa9a-9a76-4698-a8f7-fccd46b7c44b)


![image](https://github.com/user-attachments/assets/bb72c97f-ca35-43a2-a28e-8f4b0a6748a0)


