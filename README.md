 ## 👨‍💻 Author

 
 # Sameer | 👨‍💻☸️ DevOps & Agentic Ai Engineer 🤖☁️ (Aspiring)

 
# Project: Todo-App-CICD-K8s using jenkins on kubernetes.



# 🚀 Todo-App-CICD-K8s

A production-ready DevOps project demonstrating deployment of a Dockerized Todo Application on Kubernetes with complete CI/CD automation using Jenkins.

---

# 📖 Project Description

This project showcases how a containerized Node.js Todo application can be deployed and managed in a Kubernetes cluster with advanced DevOps practices such as:

✅ CI/CD Automation using Jenkins  
✅ Kubernetes Deployments & Services  
✅ RBAC Authorization  
✅ Horizontal Pod Autoscaler (HPA)  
✅ Persistent Volume Claims (PVC)  
✅ Docker Containerization  

---

# 🛠️ Tech Stack

| Tool | Purpose |
|------|----------|
| Docker | Containerization |
| Kubernetes | Container Orchestration |
| Jenkins | CI/CD Pipeline |
| Node.js | Backend Application |
| YAML | Kubernetes Configurations |

---

# 🏗️ Kubernetes Architecture


Developer → GitHub → Jenkins Pipeline → Docker Build → Kubernetes Deployment


---


.📁 Project Structure
├── k8s/
│   ├── k8s-Rbac/
│   ├── k8s-ConfigMap.yaml
│   ├── k8s-Deployment.yaml
│   ├── k8s-Hpa.yaml
│   ├── k8s-Ingress.yaml
│   ├── k8s-Namespace.yaml
│   ├── k8s-Secret.yaml
│   └── k8s-Service.yaml
│
├── app/
│   ├── src/
│   ├── spec/
│   ├── package.json
│   ├── yarn.lock
│
├── docker/
│   └── Dockerfile
│
├── compose.yaml
├── screenshots/
│
├── README.md
├── CONTRIBUTING.md
├── LICENSE
---



# 📸 Screenshots

## 🔹 Jenkins Pipeline Success
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/ef05b7ab-add4-40ee-bd08-f93759e3bb15" />


---

## ## 🔹 Application Running
<img width="2560" height="1553" alt="image" src="https://github.com/user-attachments/assets/5df51471-7d1d-4b4e-aacc-9040f4c482fd" />

---

## 🔹 Kubernetes Pods
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/fbafa21a-0fd7-4482-bffb-d7d46ecd8120" />

---

## 🔹 Kubernetes Deployments
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/9e98c783-2aca-40d5-9f7a-e192c7d90a5e" />

---

## 🔹 Horizontal Pod Autoscaler
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/93cf27da-57be-4bd2-ae5b-99df5adfcc52" />


---

## 🔹 RBAC Configuration

# ROLE 
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/02344548-08a4-4eaa-87d4-69ad995cf8c0" />


---


# Kubernetes Service
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/45d7ae77-4dc8-4cce-9f71-f61affa11bfe" />


# ⚡ CI/CD Workflow

1️⃣ Developer pushes code to GitHub  
2️⃣ Jenkins pipeline triggers automatically  
3️⃣ Docker image gets built  
4️⃣ Kubernetes deployment updates automatically  
5️⃣ Application scales using HPA  


---

# 🔐 RBAC Implementation

RBAC was configured to manage secure access control inside the Kubernetes cluster using:

- Roles
- RoleBindings
- Service Accounts

---

# 📈 Future Enhancements

- Helm Charts
- Prometheus Monitoring
- Grafana Dashboards
- ArgoCD GitOps
- Ingress Controller

---


# ⭐ If you liked this project, give it a star!
