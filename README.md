# Metro Ticket Booking System

## Project Overview

This project is a web application for booking metro tickets.  It allows users to register, login, and select their desired route and state to book tickets. The system utilizes a MySQL database (`metro.sql`) to store user information and ticket details.  The application is deployed using Apache Tomcat (version 9.0.62).

## Features

* **User Registration and Login:** Secure user account creation and login functionality.
* **State Selection:** Users can select their desired state (Andhra Pradesh, Delhi, Kolkata, Maharashtra, Tamil Nadu) for travel.
* **Route Selection:**  Specific routes within each state are available for ticket booking (indicated by the JSP files for each state and route).
* **Ticket Booking:**  Functionality to book metro tickets based on selected route and state.
* **Database Integration:** Stores user data and ticket information in a MySQL database.
* **Image and Resource Management:** Includes various images and resources in the `src/main/webapp` directory for visual presentation.

## Installation

1. **Prerequisites:**
    * Java Development Kit (JDK) 
    * Apache Tomcat 9.0.62
    * MySQL Server
    * MySQL Connector/J (mysql-connector-java-5.1.31-bin.jar included in `apache-tomcat-9.0.62/lib`)

2. **Database Setup:**
    * Create a MySQL database.
    * Import the `metro.sql` schema into your MySQL database.

3. **Deployment:**
    * Copy the contents of the `metro/apache-tomcat-9.0.62` directory into your Tomcat installation directory.
    * Ensure that the `mysql-connector-java-5.1.31-bin.jar` is present in the `lib` folder within your Tomcat deployment.
    * Start the Apache Tomcat server.

4. **Access the Application:** Access the application via your web browser at `http://localhost:8080/metro` (or the appropriate port if you've configured Tomcat differently).


## Usage

1. **Registration:** Navigate to the registration page (`Register.jsp`) to create a new user account.
2. **Login:** Use your registered credentials to login (`Login.jsp`).
3. **State Selection:** Select your desired state from the state selection page (`selectstate.jsp`).
4. **Route Selection:** Choose your specific route within the selected state (e.g., `Andhra.jsp`, `Delhi.jsp`, etc.).
5. **Ticket Booking:** Complete the ticket booking process on the relevant route page.

## Contributing

Contributions are welcome! Please refer to the `apache-tomcat-9.0.62/CONTRIBUTING.md` file for guidelines on contributing to this project.

## License

This project is licensed under the Apache License 2.0 - see the provided license text for details.  Note that certain components within Apache Tomcat may have different licensing terms (see included licenses for details).

## Contact Information

[Your Contact Information Here] (Optional)
