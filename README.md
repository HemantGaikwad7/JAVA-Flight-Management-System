# JAVA-Flight-Management-System
Project is created using Java, MVC, Hibernate, MySql, Maven, Tomcat

# Flight Management System

## Developer Information
- **Name**: Hemant Gaikwad

## Project Overview
The Flight Management System is a Java web application developed using the Spring MVC framework. It is designed to facilitate the management of flight data and the booking of flight tickets. The application supports CRUD operations on flight data, user account management, and admin functionalities through a user-friendly interface.

## Features

### CRUD Operations on Flight Data
- **Create, Read, Update, Delete**: Manage flight records including flight number, origin, destination, total seats, and available seats.
- **Error Handling**: Validates input and manages errors related to incorrect or missing data entries.

### User Registration and Management
- **Account Registration**: Allows new users to register by providing a username, email, and password.
- **Account Management**: Supports updating and deleting user accounts.

### Admin Login
- **Secure Access**: Admins can log in using unique credentials.
- **Security Measures**: Ensures that only authorized personnel can access admin functionalities.

### Admin Dashboard
- **Overview**: Displays system statistics, flight details, and user information upon admin login.
- **Navigation**: Provides options to manage flights, user accounts, and other administrative tasks.

### Ticket Booking
- **Interface**: Offers a user-friendly interface for flight selection and ticket booking.
- **Error Messages**: Displays error messages for incorrect data entries during the booking process.

### Error Handling
- **Custom Error Pages**: Handles different types of errors like invalid data entries and unauthorized access.
- **User Guidance**: Provides error messages and suggests corrective actions.

## Technology Stack
- **Java**
- **Spring MVC**
- **Hibernate** (for database access and ORM)
- **MySQL**
- **Maven** (for build and dependency management)
- **Tomcat** (servlet container for deployment)

## Setup and Installation
1. **Prerequisites**:
   - Java JDK 8 or higher
   - Maven
   - MySQL
   - Tomcat 8.5 or higher

2. **Database Configuration**:
   - Create a MySQL database named `flight_management`.
   - Update the `src/main/resources/application.properties` file with your MySQL username and password.

3. **Building the Project**:
   - Navigate to the project directory.
   - Run `mvn clean install` to build the project.

4. **Deploying the Application**:
   - Copy the generated `.war` file from the `target` directory to the `webapps` folder of your Tomcat installation.
   - Start the Tomcat server.

5. **Accessing the Application**:
   - Open a web browser and navigate to `http://localhost:8080/flight_management` to start using the application.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
