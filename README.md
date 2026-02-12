# Web Application Deployment using AWS, Docker, and Nginx

## 🚀 Project Overview

This project demonstrates a simple DevOps workflow for deploying a containerized web application on AWS. The application is packaged using Docker with Nginx as the web server and hosted on an AWS EC2 instance, making it accessible via the instance’s public IP address.

---

## 🛠️ Technologies Used

* **AWS EC2** – Cloud hosting
* **Docker** – Containerization
* **Nginx** – Web server
* **GitHub** – Version control
* **Linux** – Server environment

---

## 📌 Deployment Architecture

GitHub Repository → AWS EC2 → Docker Image → Docker Container → Nginx → Public Access

---

## ⚙️ Implementation Steps

### 1. Clone the Repository

```bash
git clone https://github.com/ananduashok/Web-application-deployment-using-AWS-Docker-Nginx.git
cd Web-application-deployment-using-AWS-Docker-Nginx
```

### 2. Build the Docker Image

```bash
docker build -t demo-web-app .
```

### 3. Run the Docker Container

```bash
docker run -d -p 80:80 demo-web-app
```

### 4. Access the Application

Open your browser and navigate to:

```
http://<AWS-Public-IP>
```

---

## ✅ Key DevOps Concepts Demonstrated

* Cloud-based deployment using AWS
* Containerization with Docker
* Version control via GitHub
* Reproducible environments with Dockerfile
* Exposing services over the internet

---

## 🔮 Future Enhancements

* Implement CI/CD with GitHub Actions
* Add HTTPS using SSL
* Use Terraform for infrastructure automation
* Deploy with Kubernetes
* Enable monitoring and logging

---

## 📖 Conclusion

This project provides a foundational example of deploying a Dockerized web application on AWS. It highlights essential DevOps practices such as containerization, cloud infrastructure usage, and streamlined deployment.
