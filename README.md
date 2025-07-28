
# 🚀 FastAPI + Traefik Reverse Proxy with HTTPS

This project demonstrates a production-style setup for running a FastAPI application behind a **Traefik reverse proxy** using **Docker Compose**, secured with **self-signed TLS certificates**.

---

## 🌐 Core Functionality

- **FastAPI** serves as a high-performance backend API.
- **Traefik** acts as a reverse proxy, dynamically routing **HTTPS** requests to the FastAPI service.
- **Self-Signed TLS** ensures local HTTPS support for development.
- **Traefik Dashboard** provides visibility into routing and service health.
- **Docker Compose** orchestrates both services in a single environment.

---

## ✅ Key Features

- Containerized deployment with Docker
- Secure reverse proxy using HTTPS (TLS)
- Automatic request routing with Traefik
- Centralized traffic management
- Traefik dashboard enabled
- Clean local development workflow

---



### Start the stack

```bash
docker-compose up --build
```

---

## 🔗 Access the Services

* [https://localhost](https://localhost) — FastAPI app (secured via HTTPS)
* [http://localhost:8080](http://localhost:8080) — Traefik dashboard


## 📌 Notes

* TLS termination is handled by Traefik.
* FastAPI is not exposed directly — all traffic flows through Traefik.

