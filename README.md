# AquaManage

AquaManage is a comprehensive application designed for managing aquariums and related services using a microservices architecture. The application features a frontend for monitoring and controlling various sensors in marine and planted tanks, and a backend for managing user accounts, tanks, actuators, and sensors.

## 🖥️ Frontend Overview

The **Aquarium Automation App Frontend** provides a user-friendly interface for monitoring and controlling sensors in marine and planted tanks.

### Built With

- **React** – Frontend framework for building interactive UIs
- **Bootstrap** – Toolkit for responsive design and styling
- **Swagger** – API documentation and testing tool
- **OpenAPI Generator** – For generating API client libraries

### Features

- Real-time sensor data monitoring
- Interactive controls for environment management
- JWT authentication for secure access
- Two dashboards for **Marine** and **Planted** tanks
- API integration with Swagger for backend interactions

### Running the App

Run the app at [http://localhost:5173](http://localhost:5173).

## 🛠️ Backend Overview

The AquaManage backend is built using **Java Spring Boot** with a microservices architecture, utilizing **JDBC** and **JPA** for database interactions. It is containerized using **Docker** and orchestrated with **Docker Compose**, and stores data in **PostgreSQL** databases.

### Features

- **User Management**: Register, authenticate, and manage user profiles.
- **Tank Management**: Handle configurations for various aquarium types (marine, planted).
- **Actuator Management**: Control and monitor actuators for environmental adjustments.
- **Sensor Management**: Collect and manage sensor data for real-time monitoring.

### Technologies Used

- **Java Spring Boot**: Framework for building robust web applications.
- **Microservices Architecture**: Decomposed services for scalability and maintainability.
- **JDBC and JPA**: For efficient database interactions.
- **Docker**: Containerization for simplified deployment and scaling.
- **Docker Compose**: Manages multi-container Docker applications.
- **PostgreSQL**: Reliable relational database for data storage.

### API Endpoints

**Base URLs**: 
- User Service: `http://localhost:8081/api/v1`
- Tank Service: `http://localhost:8082/api/v1`
- Actuator Service: `http://localhost:8083/api/v1`
- Sensor Service: `http://localhost:8084/api/v1`


## 📝 License

This project is licensed under the MIT License. See the LICENSE file for more details.
