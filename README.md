<h1 align="center">
  ClubLink: Streamlined College Club Management Solution
</h1>

<p align="center">
  <img src="https://github.com/Manoj-2702/College-Club-Management-System/assets/103581128/ce5e5f56-9397-47b0-9303-ec5db7532c76" alt="Logo" />
</p>

The College Club Management System is a comprehensive web application designed to streamline the administration of college clubs, events, and membership. Built using Spring Boot, Maven, SQL, and Java, this system empowers universities and colleges to efficiently manage their extracurricular activities.

## Features

- **User Authentication**: Separate login and registration pages for members, club heads, and faculty.
- **Home Page**: Default home page displaying all ongoing events of all clubs.
- **Member Dashboard**: Allows members to view and apply for clubs, view their club memberships, and register for events.
- **Club Head Dashboard**: Provides club heads with features to manage club members, create and manage events, and handle club membership applications.
- **Faculty Dashboard**: Enables faculty members to view all clubs under their supervision.

## Folder Structure

- **Models**: Contains Java classes representing the entities such as Member, Club, Event, etc.
- **Views**: Contains HTML templates for different pages like login, registration, dashboards, etc.
- **Controllers**: Contains Java classes responsible for handling HTTP requests and routing them to appropriate methods.
- **Services**: Contains Java classes implementing business logic and interacting with repositories.
- **Design Patterns**: Implements various design patterns such as MVC, Facade, and Single Responsibility to ensure modular and maintainable codebase.

## Technologies Used

- **Spring Boot**: The application is built using the Spring Boot framework, leveraging its powerful features for rapid development and easy deployment.
- **Maven**: Maven is used for dependency management and project build automation.
- **SQL**: The system utilizes a relational database management system (RDBMS) for efficient data storage and retrieval.
- **Java**: The core application logic is implemented using the Java programming language, ensuring cross-platform compatibility and robust performance.


## Getting Started

1. Clone the repository to your local machine.
2. Import the project into your preferred IDE (Eclipse, IntelliJ, etc.).
3. Set up the required dependencies and configurations like the sql database connection(Java, Spring Boot, Maven).
4. Run the application locally using the embedded server provided by Spring Boot.
5. Access the application through your browser using the specified port (in this case, `localhost:8080`).

## Acknowledgements

- This project was developed as part of the Object Oriented Analysis and Design course at PES University.
