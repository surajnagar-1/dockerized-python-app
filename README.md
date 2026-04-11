# 🚀 Dockerized Flask App

A stylish Python Flask web application containerized using Docker.
This project is built for practicing DevOps concepts like containerization, environment variables, and service orchestration using Docker Compose.

---

## 📸 Features

* 🌐 Clean UI using HTML & CSS
* 🐍 Python Flask backend
* 🐳 Docker support
* ⚙️ Environment variables
* ❤️ Health check endpoint
* 📦 Docker Compose support
* 🔄 Jenkins CI/CD pipeline

---

## ▶️ Run Locally

pip install -r requirements.txt
python app.py

App will run on:
http://localhost:5000

---

## 🐳 Run with Docker

docker build -t flask-app .

docker run -p 5000:5000 flask-app

---

## 🚀 Run with Docker Compose

docker-compose up --build

👉 Open in browser:
http://localhost:5000

---

## 🔄 Jenkins CI/CD Pipeline

This project includes a Jenkins pipeline to automate the complete workflow:

### 🔹 Jenkins Pipeline Overview

* **Code Clone** → Pulls latest code from GitHub
* **Build** → Builds Docker image
* **Push to Docker Hub** → Pushes image to Docker Hub
* **Deploy** → Runs container using Docker Compose

---

## 🔗 API Endpoints

/        → Home Page (UI)

/health  → Health Check

---

## ⚙️ Environment Variables

PORT → Application port (default: 5000)

ENV  → Environment mode

---

## 💡 DevOps Concepts Used

* Docker containerization
* Docker Compose orchestration
* CI/CD using Jenkins
* Docker Hub integration
* Environment variable handling

---

## 👨‍💻 Author

Suraj Nagar
Aspiring DevOps Engineer 🚀

---

## ⭐ Support
