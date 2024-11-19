# 🛒 Microservices E-Commerce

**microservices-ecom** is a simple e-commerce platform that demonstrates a microservices architecture using **Go**, **gRPC**, **Docker**, and **SQL**. This project provides the core structure of an online store with a modular, scalable, and efficient design.

---

## 🚀 Features

- **Microservices Architecture**:
  - Independent services for user management, product catalog, orders, and payments.
- **gRPC Communication**:
  - Efficient inter-service communication using high-performance RPC.
- **SQL Database**:
  - Reliable and consistent data storage with a well-designed schema.
- **Docker Support**:
  - Easy deployment and scaling with containerized services.
- **REST Gateway**:
  - Exposes a RESTful API for user-friendly interaction.

---

## 🛠️ Technologies Used

- **Go (Golang)**: The main programming language.
- **gRPC**: For efficient inter-service communication.
- **SQL Database**: PostgreSQL or MySQL for data storage.
- **Docker**: For containerization of services.
- **Protobuf**: For defining gRPC service messages and methods.
- **Swagger**: For REST API documentation.

---

## 📂 Project Structure

```plaintext
microservices-ecom/
│
├── auth-service/        # Handles user registration, login, and profile management
├── product-service/     # Manages product catalog and inventory
├── order-service/       # Processes customer orders
├── cart-service/     # Handles payment transactions
├── inventory-gateway/         # REST API gateway for user interaction 
├── docker-compose.yml   # Docker Compose configuration
└── README.md            # Project documentation```
