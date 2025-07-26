
# 🚀 FastAPI + Traefik Reverse Proxy Setup

This project demonstrates a minimal setup for running a FastAPI application behind a Traefik reverse proxy using Docker and Docker Compose.

---

## 🌐 Core Functionality

* **FastAPI** serves as a high-performance backend API.
* **Traefik** acts as a reverse proxy, dynamically routing HTTP requests to the FastAPI service.
* **Docker Compose** orchestrates both services in a single, isolated environment.
* **Traefik Dashboard** provides visibility into routing and service health.

---

## ✅ Key Features

* Containerized deployment with Docker
* Automatic request routing with Traefik
* Centralized traffic management
* Easy local development and testing

---

## 🚀 Getting Started

Bring up the stack with:

```bash
docker-compose up --build
```

Then visit:

* [http://localhost](http://localhost) — FastAPI app
* [http://localhost:8080](http://localhost:8080) — Traefik dashboard

---

