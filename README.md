# Guestbook Application with Spring Cloud

## Overview

This is a guestbook application built using Spring Cloud. It allows users to sign a guestbook and view all the entries. The application demonstrates how to use Spring Cloud for microservices architecture, including service discovery, load balancing, and configuration management.

## Features

- **User Registration and Login:** Register an account and log in to manage your guestbook entries.
- **Sign Guestbook:** Add new entries to the guestbook.
- **View Guestbook Entries:** Browse through the list of guestbook entries.
- **Service Discovery:** Use Spring Cloud Eureka for service discovery.
- **Load Balancing:** Leverage Ribbon for load balancing between microservices.
- **Centralized Configuration:** Manage configuration using Spring Cloud Config Server.

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven 3.6 or higher
- Docker (optional, for containerized deployment)

### Setup and Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/<your-repo-id>/guestbook-application-spring-cloud.git
    cd guestbook-application-spring-cloud
    ```

2. **Install dependencies:**

    ```bash
    mvn install
    ```

3. **Run the application:**

    - Start the Spring Cloud Config Server, Eureka Server, and other microservices as needed.
    - You can use Docker Compose for easy setup of the complete environment if provided.

4. **Open the application:**

    The application will be available at [http://localhost:8080](http://localhost:8080).

### Usage

1. **Register an account** to start using the application.
2. **Login** with your credentials.
3. **Sign the guestbook** by adding new entries.
4. **View guestbook entries** to see all the submissions.

## API Endpoints

- **POST /api/register** - Register a new user.
- **POST /api/login** - Authenticate user credentials.
- **POST /api/guestbook** - Add a new guestbook entry.
- **GET /api/guestbook** - Retrieve a list of guestbook entries.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.


