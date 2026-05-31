# Microservices Containerization Assessment

## Overview

This project demonstrates the containerization of a Node.js microservices application using Docker and Docker Compose.

### Services

* User Service (Port 3000)
* Product Service (Port 3001)
* Order Service (Port 3002)
* Gateway Service (Port 3003)

---

## Prerequisites

* Docker Desktop (includes Docker Compose)
* Git

---

## Project Structure

```text
Microservices/
├── gateway-service/
│   └── Dockerfile
├── order-service/
│   └── Dockerfile
├── product-service/
│   └── Dockerfile
├── user-service/
│   └── Dockerfile
├── docker-compose.yml
└── README.md
```

---

## Build and Run

Navigate to the project directory and run:

```bash
docker compose up --build
```

---

## Verify Running Containers

```bash
docker ps
```

---

## Test Services

### User Service

```text
http://localhost:3000/users
```

### Product Service

```text
http://localhost:3001/products
```

### Order Service

```text
http://localhost:3002/orders
```

### Gateway Service

```text
http://localhost:3003/api/users
http://localhost:3003/api/products
http://localhost:3003/api/orders
```

---

## Screenshots (Please see folder)

Include screenshots of:

* Docker Compose build and startup
* Running containers (`docker ps`)
* User Service response
* Product Service response
* Order Service response
* Gateway Service response

---

# Thank you