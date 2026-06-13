# 🚀 PiOps - Self-Hosted CI/CD Deployment Platform using Raspberry Pi

PiOps is a lightweight self-hosted deployment platform built on a Raspberry Pi that automates the deployment of Node.js applications using a complete CI/CD pipeline. The project demonstrates how low-cost ARM-based hardware can be leveraged to host and manage modern web applications with industry-standard DevOps practices.

## ✨ Features

* 🖥️ Self-hosted Linux server running on Raspberry Pi
* ⚙️ Automated CI/CD pipeline using Jenkins
* 🐳 Docker-based containerized application deployment
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
    └── Build Docker Image
    │
    ▼
 Raspberry Pi Server
    │
    ├── Docker Container
    ├── Node.js Application
    └── Nginx Reverse Proxy
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
* Jenkins
* Git
* CI/CD Pipelines

### Application

* Node.js
* Express.js

### Networking & Security

* Nginx
* SSH

## 🎯 Objectives

* Build a cost-effective self-hosted deployment environment.
* Learn real-world DevOps workflows and automation.
* Implement continuous integration and deployment practices.
* Explore containerization on ARM-based hardware.
* Gain hands-on experience with Linux server administration.

## 🔄 CI/CD Workflow

1. Developer pushes code to GitHub.
2. Jenkins automatically detects repository changes.
3. Application is built and tested.
4. Docker image is created.
5. Existing container is replaced with the latest version.
6. Nginx routes traffic to the updated application.
7. Users access the newly deployed version with zero manual deployment steps.

## 🚀 Key Learnings

* Linux server administration and process management
* Docker containerization and image management
* Jenkins pipeline creation and automation
* Reverse proxy configuration with Nginx
* SSH-based remote server management
* Continuous Integration and Continuous Deployment practices
* Resource optimization for ARM-based systems

## 📈 Future Enhancements

* HTTPS support with Let's Encrypt
* Kubernetes deployment using K3s
* Monitoring with Prometheus and Grafana
* Multi-application hosting support
* Automated backup and recovery system
* Blue-Green deployment strategy

