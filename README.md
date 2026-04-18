# 🚀 DevOps Project: Docker + Kubernetes + CI/CD

## 📌 Overview
This project demonstrates a complete DevOps workflow including containerization, Kubernetes deployment, and CI/CD automation.

## ⚙️ Tech Stack
- Python (Flask)
- Docker
- Kubernetes
- GitHub Actions

## 🔥 Features
- Containerized web application
- Kubernetes deployment with multiple replicas
- Liveness health check (`/health`)
- CI/CD pipeline using GitHub Actions
- Docker Hub integration

## 🌐 Endpoints
- `/` → Main app
- `/health` → Health check
- `/env` → Environment variables
- `/api/data` → POST API

## 🚀 How to Run

```bash
docker build -t myapp .
docker run -p 5000:5000 myapp
