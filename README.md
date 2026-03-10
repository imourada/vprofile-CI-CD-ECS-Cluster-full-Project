# 🚀 Full CI/CD Pipeline with Jenkins + AWS ECS/ECR

This repository showcases a complete **Jenkins declarative pipeline** automating the journey from source code to cloud deployment.  
It integrates **GitHub, Maven, SonarQube, Docker, AWS ECR, and AWS ECS** to deliver a robust end‑to‑end DevOps workflow.

---

## 🔧 Pipeline Stages
1. **Code Fetch** – Pull source code from GitHub  
2. **Build & Unit Tests** – Run with Maven  
3. **Static Analysis** – Enforce code quality using Checkstyle & SonarQube  
4. **Quality Gate** – Block deployment if checks fail  
5. **Artifact Archiving** – Store `.war` files for traceability  
6. **Docker Image Build & Push** – Create container image and push to AWS ECR  
7. **Deployment** – Deploy application to AWS ECS  
8. **Environment Hygiene** – Cleanup unused containers, images, and networks  

---

## 🛠️ Tools & Technologies
- **Jenkins** – CI/CD orchestration  
- **Maven** – Build & test automation  
- **SonarQube** – Code quality analysis  
- **Docker** – Containerization  
- **AWS ECR/ECS** – Cloud image registry & deployment  

## 📂 Project Files
- [Dockerfile](./Dockerfile)  
- [Jenkinsfile](./Jenkinsfile)  

## 📌 Visual Flow
GitHub → Jenkins → SonarQube → Docker → AWS ECR → AWS ECS  

*(Attach pipeline diagram here for clarity)*

---

## 🌍 About This Project
This is a **new project** I recently completed to demonstrate my expertise in automation, containerization, and cloud deployment.  
It reflects my passion for building recruiter‑visible DevOps workflows that combine reliability, scalability, and security.

---

## 🔖 Keywords
#DevOps #CICD #Jenkins #AWS #Docker #SonarQube #CloudComputing #Automation #SoftwareEngineering #TechProjects
 
