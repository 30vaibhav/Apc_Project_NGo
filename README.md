# 🏢 Microservices-Based System for NGOs (Java 21 + Spring Boot)

## 📘 Project Overview

This project is a modular, microservices-based application developed using **Java 21** and **Spring Boot 3.x**, designed to digitize and enhance the operations of **Non-Governmental Organizations (NGOs)**. It focuses on creating a scalable and maintainable platform by dividing the application into independent services — enabling better performance, isolation, and development flexibility.

### ✅ Core Microservices:
- **NGO Service** – Manages NGO profiles, registration, and service areas.
- **Donation Service** – Handles donor registration, donation records, and donation tracking.
- **API Gateway** – Centralized routing and security layer for all microservices.

---

## 🛠️ Technologies Used

- **Java 21**
- **Spring Boot 3.x**
- **Spring Cloud Gateway** – For API Gateway
- **Spring Web & Spring Security**
- **Spring Data JPA** – For database operations
- **MySQL / PostgreSQL** – Relational database
- **JWT (JSON Web Tokens)** – For secure authentication
- **Maven** – Project build and dependency management
- **Docker** *(optional)* – For containerization
- **Postman** – For testing REST APIs

---

## 🧱 Architecture

```text
               [ Client (Frontend) ]
                        |
               [ API Gateway (Spring Cloud) ]
                    /                    \
          [ NGO Service ]         [ Donation Service ]

📦 Key Features
🏢 NGO Service

NGO registration and login

NGO profile creation and updates

Service/activity tracking

💳 Donation Service

Donor registration and authentication

Donation entry and history tracking

Link donors to specific NGOs

🚪 API Gateway

Single entry point for client interactions

Secure routing of requests using JWT filters

Load balancing and basic rate limiting (optional)
