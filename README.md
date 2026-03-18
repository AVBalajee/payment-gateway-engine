<h1 align="center">💳 Payment Gateway Engine 🚀</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Microservice-Payment%20Engine-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Backend-SpringBoot-green?style=for-the-badge" />
</p>

<p align="center">
  <em>
    High-throughput <b>Payment Processing System</b> built using <b>Spring Boot, Kafka, Redis, PostgreSQL</b><br>
    Designed for <b>Scalability ⚡ | Reliability 🔐 | Performance 🚀</b>
  </em>
</p>

---

# 🧠 System Architecture

```
Frontend (React)
        ↓
Spring Boot API
        ↓
PostgreSQL
        ↓
Kafka (Event Streaming)
        ↓
Consumer (Async Processing)
        ↓
Redis (Caching)
        ↓
Zipkin (Tracing)
```

---

# ✨ Features

- ⚡ High-throughput payment processing  
- 🔁 Idempotency (duplicate prevention)  
- 📡 Kafka-based event-driven architecture  
- ⚡ Redis caching for fast response  
- 🔍 Distributed tracing with Zipkin  
- 🐳 Fully Dockerized setup  
- 🎯 Clean layered architecture  
- ⚛️ React frontend dashboard  

---

# 🛠️ Tech Stack

- Java 21  
- Spring Boot  
- PostgreSQL  
- Redis  
- Kafka  
- Docker  
- Zipkin  
- React (Vite)  

---

# 🚀 Setup Guide

## Clone Project
git clone https://github.com/AVBalajee/payment-gateway-engine.git

## Start Docker
docker compose up -d

## Run Backend
cd backend
mvn spring-boot:run

## Run Frontend
cd frontend
npm install
npm run dev

---

# 📡 API Endpoints

POST /api/payments  
GET /api/payments  
GET /api/payments/{id}

---

# 👨‍💻 Author

Balajee A V
