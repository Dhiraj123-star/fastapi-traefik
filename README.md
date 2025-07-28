
# 🚀 FastAPI + Traefik Reverse Proxy with HTTPS

This project demonstrates a production-style setup for running a **FastAPI** application behind a **Traefik reverse proxy** using **Docker Compose**, secured with **self-signed TLS certificates**, and automatically deployed using **GitHub Actions CI/CD** with Docker Hub.

---

## 🌐 Core Functionality

- ⚡ **FastAPI** serves as a high-performance backend API.
- 🌐 **Traefik** acts as a reverse proxy, dynamically routing **HTTPS** requests to the FastAPI service.
- 🔐 **Self-Signed TLS** enables local HTTPS support for development.
- 📊 **Traefik Dashboard** provides visibility into routing and service health.
- 🐳 **Docker Compose** orchestrates both services in a single, isolated environment.
- 🤖 **GitHub Actions CI/CD** automatically builds and pushes Docker images to Docker Hub.

---

## ✅ Key Features

- Secure reverse proxy using **HTTPS (TLS)**
- Containerized deployment with Docker
- Automatic request routing with Traefik
- Traefik dashboard enabled by default
- Local self-signed certificate generation
- Clean local development workflow
- CI/CD integration using GitHub Actions & Docker Hub

---

## ▶️ Start the Stack Locally

```bash
docker-compose up --build
````

---

## 🔗 Access the Services

* 🌐 [https://localhost](https://localhost) — FastAPI app (secured via HTTPS)
* 📊 [http://localhost:8080](http://localhost:8080) — Traefik dashboard



## 🚀 CI/CD Pipeline

This project includes a GitHub Actions workflow that:

1. Builds the Docker image from the FastAPI + Traefik setup.
2. Tags it as `latest`.
3. Pushes the image to Docker Hub under:
   **[`dhiraj918106/fastapi-traefik`](https://hub.docker.com/repository/docker/dhiraj918106/fastapi-traefik)**

To trigger the pipeline, push to the `main` branch.

---


## 🐳 Docker Hub Repository

* **Docker Hub:** [`dhiraj918106/fastapi-traefik`](https://hub.docker.com/repository/docker/dhiraj918106/fastapi-traefik)

---

## 🔐 Security Best Practice

✅ **Self-signed TLS certificates are ignored via `.gitignore`** to avoid accidental exposure in version control.
🔒 For production, use **Let's Encrypt** with **Traefik's ACME support**.

---

## 📄 License

MIT License © 2025 Dhiraj Kumar

---

