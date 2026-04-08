# 🚀 MERN Memories App (Kubernetes Deployment)

This is a full-stack MERN (MongoDB, Express, React, Node.js) application that allows users to create, view, and manage memories (posts). The project is deployed using Docker and Kubernetes.

---

## 📌 Features

* Create, update, and delete memories
* Like posts
* Responsive UI using React
* REST API using Node.js & Express
* MongoDB database integration
* Dockerized application
* Kubernetes deployment

---

## 🛠️ Tech Stack

* Frontend: React.js
* Backend: Node.js, Express.js
* Database: MongoDB
* Containerization: Docker
* Orchestration: Kubernetes

---

## 📂 Project Structure

```
project_mern_memories/
│── client/      # React frontend
│── server/      # Node.js backend
│── k8s/         # Kubernetes YAML files
```

---

## ⚙️ Setup & Run Locally

### 1. Clone the repository

```
git clone https://github.com/YOUR_USERNAME/mern-memories.git
cd mern-memories
```

### 2. Setup Backend

```
cd server
npm install
npm start
```

### 3. Setup Frontend

```
cd client
npm install
npm start
```

---

## 🌐 Environment Variables

Create a `.env` file inside the `server` folder:

```
CONNECTION_URL=mongodb:
PORT=5000
```

---

## 🐳 Docker Setup

### Build images

```
docker build -t mern-server ./server
docker build -t mern-client ./client
```

---

## ☸️ Kubernetes Deployment

Apply Kubernetes configs:

```
kubectl apply -f k8s/
```

Check resources:

```
kubectl get pods
kubectl get svc
```

Access app:

```
minikube service client-service
```

---

## 📸 Screenshots

(Add screenshots of your app here)

---

## 👨‍💻 Author

**Abhay Kumar**

* GitHub: https://github.com/ABHAY9927

---

## ⭐ Acknowledgement

This project is inspired by the original MERN tutorial project.

---

## 📌 Future Improvements

* Add authentication (JWT)
* Deploy on cloud (AWS / GCP)
* Add CI/CD pipeline

---
