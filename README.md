# API Stock

The **API Stock** is a microservice designed to manage the inventory of articles, including the management of brands and categories. This API allows you to add new articles associated with a brand and a category, as well as to create, update, and delete brands and categories. Additionally, the API implements robust security validation with Spring Security, where access to certain functionalities is controlled via token-based authentication and user roles. The API is documented with OpenAPI and Swagger, which facilitates easy exploration and testing of endpoints.

## Features

- **Article Management:** Add, update, and manage articles, each associated with a brand and a category.
- **Brand and Category Management:** Create, update, and delete brands and categories.
- **Inventory Tracking:** Manage the stock levels of articles in the inventory.
- **Authentication and Authorization:** Secure access using Spring Security, with token validation and role-based access control.
- **API Documentation:** Interactive OpenAPI documentation integrated with Swagger.
- **Microservices Architecture:** Scalable microservice for effective inventory management.
- **Url local:** h

## Technologies

- Java
- Spring Boot
- Spring Security
- RESTful API
- Microservices Architecture
- OpenAPI / Swagger
- Gradle

## Getting Started

### Prerequisites

- Java 17 or higher
- Gradle
- A compatible SQL Database

## API Endpoints
Access the interactive documentation via Swagger UI: **http://localhost:7070/swagger-ui.html**

This interface provides interactive documentation for all available endpoints, making it easy to understand and test the API.
### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/EstebanRCarmona/Api-Stock-emazon.git
