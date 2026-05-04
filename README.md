# Job Portal System

A full-stack Job Portal System with a Java Spring Boot backend and an HTML/CSS/JS frontend.

## Project Structure

This project is separated into two main directories:

- `/frontend` - Contains the user interface (HTML, CSS, JS).
- `/backend` - Contains the Java Spring Boot REST API and server logic.

## Prerequisites

- **Backend:** Java (JDK 17 or later) and Maven
- **Frontend:** Any modern Web Browser
- **Database:** (Ensure your database configuration in the backend's `application.properties` or `application.yml` is set up correctly)

## Getting Started

### 1. Setting up the Backend

1. Open a terminal and navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Build the project using Maven:
   ```bash
   mvn clean install
   ```
3. Run the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```
   The backend server will start (usually on `http://localhost:8080`).

### 2. Setting up the Frontend

1. Open the `frontend` directory.
2. You can simply open the `index.html` file in your preferred web browser, or use a local development server like Live Server (VS Code extension) to serve the files.

## Features

- User Authentication (Login/Register)
- Job Listings and Search
- Application Tracking
- (Add more features specific to your implementation here)

## Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
