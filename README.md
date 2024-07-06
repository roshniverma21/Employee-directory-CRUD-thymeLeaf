# Employee Directory Web UI

This project provides a web interface for managing an employee directory. Users can perform CRUD operations (Create, Read, Update, Delete) on employee records through a user-friendly interface made with thymeleaf.

## Features

1. **List of Employees**
   - Endpoint: `/employees/list`
   - Description: Displays a list of all employees currently in the directory.

2. **Add a New Employee**
   - Endpoint: `/employees/showFormForAdd`
   - Description: Displays a form for adding a new employee to the directory. Upon submission, the new employee is added to the database and the list is updated accordingly.

3. **Update an Existing Employee**
   - Endpoint: `/employees//showFormForUpdate`
   - Description: Allows users to update the details of an existing employee by clicking on the udpate button and the list is updated accordingly.

4. **Delete an Employee**
   - Endpoint: `/employees/delete`
   - Description: Allows users to delete an employee from the directory by clicking on the delete button and the list is updated accordingly.

## Getting Started

To run the Employee Directory Web UI locally, follow these steps:

1. **Prerequisites:**
   - Make sure you have Java Development Kit (JDK) and Maven installed on your machine.

2. **Clone the repository:**
git clone <repository_url>
cd employee-directory-web-ui

3. **Build and run the application:**
mvn spring-boot

4. **Access the application:**
Open a web browser and go to `http://localhost:8080/`. you will be reidrected to `/employees/list` automatically 

## Technologies Used
- **Spring Boot:** Backend framework for building the web application.
- **Thymeleaf:** Server-side Java template engine for rendering HTML.
- **Spring Data JPA:** Java Persistence API for database interactions.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request for any enhancements or bug fixes.
