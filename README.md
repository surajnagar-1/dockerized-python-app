# 🚀 Dockerized Flask App 

A stylish Python Flask web application containerized using Docker.
This project demonstrates **multi-stage builds with Distroless images** and **Docker Compose orchestration** for DevOps practice.

---

## 📸 Features

* 🌐 Clean UI using HTML & CSS
* 🐍 Python Flask backend
* 🐳 Docker support
* ⚙️ Environment variables
* ❤️ Health check endpoint
* 🚀 Multi-stage Docker build
* 🔒 Distroless image (secure & lightweight)
* 📦 Docker Compose support

---

## ▶️ Run Locally

pip install -r requirements.txt
python app.py

App will run on:
http://localhost:5000

---

## 🐳 Run with Docker (Basic)

### 🔹 Build Image

docker build -t flask-docker-app .

### 🔹 Run Container

docker run -p 5000:5000 flask-docker-app

---

## 🚀 Run with Docker Compose (Distroless)

docker-compose up --build

👉 Open in browser:
http://localhost:5000

---

## 🔗 API Endpoints

/        → Home Page (UI)
/health  → Health Check

---

## ⚙️ Environment Variables

PORT → Application port (default: 5000)
ENV  → Environment mode (development/production)

---

## 💡 DevOps Concepts Used

* Docker containerization
* Multi-stage builds
* Distroless images (security best practice)
* Docker Compose orchestration
* Environment variable handling
* Health check endpoint

---

## 🔒 Why Distroless?

* Smaller image size
* No unnecessary tools (more secure)
* Reduced attack surface
* Production-ready approach

---

## 👨‍💻 Author

Suraj Nagar
Aspiring DevOps Engineer 🚀

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

