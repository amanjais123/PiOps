# 🚀 PiOps - Self-Hosted CI/CD Deployment Platform using Raspberry Pi

PiOps is a lightweight self-hosted deployment platform built on a Raspberry Pi that automates the deployment of Node.js applications using a complete CI/CD pipeline. The project demonstrates how low-cost ARM-based hardware can be leveraged to host a full-stack application stack, including the application server, MongoDB database, and deployment infrastructure, using industry-standard DevOps practices.

## ✨ Features

* 🖥️ Self-hosted Linux server running on Raspberry Pi
* ⚙️ Automated CI/CD pipeline using Jenkins
* 🐳 Docker-based containerized deployment
* 🗄️ Self-hosted MongoDB database running on Raspberry Pi
* 🌐 Nginx reverse proxy for application routing
* 🔒 Secure remote server management via SSH
* 📦 Git-based automated build and deployment workflows
* 📊 Resource-efficient deployment optimized for ARM architecture
* 🔄 Continuous Integration and Continuous Delivery for Node.js applications

## 🏗️ Architecture

```text
Developer
    │
    ▼
 GitHub Repository
    │
    ▼
 Jenkins Pipeline
    │
    ├── Build Application
    ├── Run Tests
    └── Build Docker Images
    │
    ▼
 Raspberry Pi Server
    │
    ├── Nginx Reverse Proxy
    ├── Node.js Application Container
    └── MongoDB Container
    │
    ▼
 End Users
```

## 🛠️ Tech Stack

### Infrastructure

* Raspberry Pi
* Linux (Raspberry Pi OS)

### DevOps

* Docker
* Docker Compose
* Jenkins
* Git
* CI/CD Pipelines

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Networking & Security

* Nginx
* SSH

## 🎯 Objectives

* Build a completely self-hosted application infrastructure.
* Automate application deployment through CI/CD pipelines.
* Host both application and database services on Raspberry Pi hardware.
* Implement containerized deployments for portability and scalability.
* Gain hands-on experience with Linux server administration and DevOps workflows.

## 🔄 CI/CD Workflow

1. Developer pushes code to GitHub.
2. Jenkins automatically triggers the pipeline.
3. Application is built and validated.
4. Docker images are created and updated.
5. Node.js application and MongoDB services are deployed on Raspberry Pi.
6. Nginx routes incoming requests to the application container.
7. Users access the latest deployed version without manual intervention.

## 🚀 Key Highlights

* Hosted both the Node.js application and MongoDB database locally on Raspberry Pi.
* Automated end-to-end deployments using Jenkins and Docker.
* Configured Nginx reverse proxy and SSH-based remote administration.
* Achieved a low-cost, self-managed infrastructure without relying on cloud hosting services.
* Demonstrated real-world DevOps concepts including CI/CD, containerization, service orchestration, and server management.

## 📈 Future Enhancements

* HTTPS with Let's Encrypt
* Kubernetes (K3s) deployment on Raspberry Pi
* Monitoring with Prometheus and Grafana
* Automated database backups and disaster recovery
* Multi-service deployment support
* Blue-Green and Canary deployment strategies
