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

# Todo-App-CICD-K8s/
│
├── app/                         # Application code (Node.js / Flask etc.)
│   ├── app.js
│   └── package.json
│
├── k8s/                         # Kubernetes manifests
│   ├── deployment.yaml
│   ├── service.yaml
│   ├── hpa.yaml
│   ├── pvc.yaml
│   └── rbac/
│       ├── role.yaml
│       ├── role-binding.yaml
│       └── serviceaccount.yaml
│
├── Jenkinsfile                 # CI/CD pipeline definition
├── Dockerfile                  # Container build file
│
├── screenshots/                # Project outputs
│   ├── jenkins.png
│   ├── pods.png
│   ├── services.png
│   ├── hpa.png
│   └── app.png
│
└── README.md

---

# ⚡ CI/CD Workflow

1️⃣ Developer pushes code to GitHub  
2️⃣ Jenkins pipeline triggers automatically  
3️⃣ Docker image gets built  
4️⃣ Kubernetes deployment updates automatically  
5️⃣ Application scales using HPA  

---

# 📸 Screenshots

## 🔹 Jenkins Pipeline Success
<img width="1330" alt="Jenkins Pipeline Success" src="screenshots/jenkins.png">

---

## 🔹 Kubernetes Pods
<img width="1330" alt="Kubernetes Pods" src="screenshots/pods.png">

---

## 🔹 Kubernetes Deployments
<img width="1330" alt="Kubernetes Deployments" src="screenshots/deployments.png">


---

## 🔹 Horizontal Pod Autoscaler
<img width="1330" alt="HPA" src="screenshots/hpa.png">

---

## 🔹 RBAC Configuration
<img width="1330" alt="RBAC Config" src="screenshots/rbac.png">


---

## 🔹 Application Running
<img width="1330" alt="App Running" src="screenshots/app.png">

---

# ⚙️ Kubernetes Commands

## Apply Configurations


kubectl apply -f .


## Check Pods


kubectl get pods


## Check Services


kubectl get svc


## Check Deployments


kubectl get deployments


## Check HPA


kubectl get hpa


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
