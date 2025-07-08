# CI/CD Pipeline Implementation using Jenkins 

This project demonstrates an end-to-end CI/CD pipeline using **Jenkins**, **GitHub**, **Docker**, and **AWS EC2**. It automates the process of building, testing, and deploying a Django ToDo application.

---

## 🚀 Features

- CI/CD pipeline using **Jenkins**
- Dockerized Django application
- Automated deployment to **AWS EC2**
- Integration with **GitHub** for source control
- Real-time build, test, and deployment automation
- Infrastructure-as-Code using **Jenkinsfile**

---

## 🛠️ Tech Stack

- Python, Django
- Jenkins
- Docker
- Git & GitHub
- AWS EC2
- Nginx (Optional for reverse proxy)
- Webhooks (for GitHub-Jenkins integration)

---

## 📦 Project Structure

```bash
.
├── Jenkinsfile         # Pipeline as code
├── Dockerfile          # Docker build instructions
├── docker-compose.yml  # Optional for multi-container setup
├── requirements.txt
├── manage.py
├── todo/               # Django project folder
└── README.md
