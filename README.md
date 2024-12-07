# Product Management System

## Overview

This product management system is built in Go and allows for the management of products, including features like asynchronous image processing, caching, and high scalability. The system supports CRUD operations for products, image processing, caching with Redis, and integration with PostgreSQL.

## Architectural Choices

- **Go (Golang)**: Chosen for its simplicity, speed, and suitability for building scalable systems.
- **PostgreSQL**: Used for storing product and user data due to its robustness and support for complex queries.
- **Redis**: Used for caching product data to improve performance for frequent requests.
- **Message Queue (RabbitMQ/Kafka)**: Used for asynchronous image processing to handle heavy tasks without blocking the main application.
- **Modular Structure**: The code is organized into modules for better maintainability and scalability.

## Setup Instructions

### Prerequisites

- Go 1.18+
- PostgreSQL
- Redis (for caching)

### 1. Clone the repository

```bash
git clone https://github.com/your-username/product-management.git
cd product-management
