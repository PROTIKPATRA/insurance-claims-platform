# Insurance Claims Platform — CI/CD Pipeline (Azure DevOps)

## 📌 Project Overview

This project demonstrates a complete end-to-end CI/CD pipeline for an Insurance Claims Platform using Azure DevOps, Docker, and multiple Azure services.

The goal is to automate the entire software delivery process from code commit to cloud deployment with monitoring and scalability.

---

## 🏗️ Architecture Flow

- Developer  
  - GitHub Repository  
    - Azure DevOps Pipeline  
      - Code Quality Scan  
        - Docker Build  
          - Azure Container Registry (ACR)  
            - Azure App Service  
              - Azure Database for MySQL  
                - Application Insights  
                  - Azure Monitor  

---

## ⚙️ Tech Stack

- Node.js (Application)
- Azure DevOps (CI/CD)
- GitHub (Source Control)
- Docker (Containerization)
- Azure Container Registry (ACR)
- Azure App Service (Hosting)
- Azure Database for MySQL
- Application Insights (Monitoring)
- Azure Monitor (Logging & Alerts)

---

## 📦 CI/CD Pipeline Workflow

- Code is pushed to GitHub repository  
- Azure DevOps pipeline is triggered automatically on main branch  
- Code quality checks are performed (optional integration)  
- Docker image is built using Dockerfile  
- Docker image is pushed to Azure Container Registry (ACR)  
- Application is deployed to Azure App Service  
- Application connects to Azure MySQL Database  
- Monitoring is enabled using Application Insights and Azure Monitor  

---

## Features

- Automated CI/CD pipeline  
- Self-hosted Azure DevOps agent support  
- Docker-based deployment  
- Cloud-native architecture  
- Scalable and production-ready design  
- Monitoring and logging enabled  
- Secure container registry integration  

---

## 🔐 Security Practices

- No hardcoded secrets in code  
- Secure Azure DevOps service connections  
- Container images stored in private ACR  
- Environment-based configuration management  

---

## 🚀 Future Enhancements

- Kubernetes (AKS) deployment  
- Infrastructure as Code (Terraform / Bicep)  
- Blue-Green deployment strategy  
- Automated rollback system  
- SonarQube full integration  
- Load balancing and autoscaling  

---

## 👨‍💻 Author

Protik Patra  
Devops Engineer  
