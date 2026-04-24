# 🚀 DevOps Engineer Portfolio

<div align="center">

![DevOps Banner](https://img.shields.io/badge/DevOps-Engineer-0A66C2?style=for-the-badge&logo=devdotto&logoColor=white)
![Workshop](https://img.shields.io/badge/Cloud_Train-DevOps_Workshop-00C4CC?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Actively_Learning-28a745?style=for-the-badge)

**Trained at [Cloud Train](https://www.thecloudtrain.com) | 7-Day Intensive DevOps Workshop**

*Bridging the gap between Development and Operations through automation, containerization, and continuous delivery.*

</div>

---

## 👨‍💻 About Me

I have completed an intensive **7-Day DevOps Workshop** by **Cloud Train**, where I gained hands-on experience with industry-standard DevOps tools and practices. This portfolio showcases everything I learned and built during the workshop.

---

## 🛠️ Tech Stack & Skills

<div align="center">

| Category | Tools |
|----------|-------|
| **Version Control** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) |
| **CI/CD** | ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white) |
| **Containerization** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| **Configuration Mgmt** | ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white) |
| **Orchestration** | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white) |
| **Monitoring** | ![Nagios](https://img.shields.io/badge/Nagios-Monitoring-2C3E50?style=flat&logo=nagios&logoColor=white) |

</div>

---

## 📚 Workshop Curriculum — What I Learned

### 🔷 Day 1 — Introduction to DevOps
> **Concepts Covered:**
- Agile Model and the need for DevOps
- What is DevOps? DevOps culture & principles
- DevOps Lifecycle (Plan → Code → Build → Test → Release → Deploy → Operate → Monitor)
- Overview of popular DevOps tools

---

### 🔷 Day 2 — Version Control | GitHub
> **Concepts Covered:**
- What is Version Control? (Centralized vs Distributed)
- Introduction to Git & Git Lifecycle
- How Git works internally
- Common Git commands (`init`, `clone`, `add`, `commit`, `push`, `pull`)
- Working with Branches and Merging

> **🧪 Hands-On Practice:**
- Created a local Git repository
- Committed and pushed code to GitHub
- Worked with branches (`feature`, `main`) and performed merges

---

### 🔷 Day 3 — Continuous Integration | Jenkins
> **Concepts Covered:**
- Introduction to Continuous Integration (CI)
- What is Jenkins? Installing Jenkins
- Jenkins Master-Slave Architecture
- Jenkins integration with other DevOps tools
- Understanding CI/CD Pipelines
- Creating an end-to-end automated CI/CD Pipeline

> **🧪 Hands-On Practice:**
- Set up Jenkins on a server
- Created a Jenkins Pipeline job
- Configured an automated CI/CD pipeline that pulls code from GitHub and builds it

---

### 🔷 Day 4 — Containerization | Docker
> **Concepts Covered:**
- Introduction to Virtualization vs Containerization
- Docker ecosystem: Images, Containers, Volumes, Networks
- Docker Lifecycle
- Installing Docker & common Docker commands
- Creating a Docker Hub account
- Committing changes in a container
- Pushing images to Docker Hub
- Writing Dockerfiles

> **🧪 Hands-On Practice:**
- Built a custom Docker image using a `Dockerfile`
- Ran containers and committed changes
- Pushed a container image to Docker Hub

---

### 🔷 Day 5 — Configuration Management | Ansible
> **Concepts Covered:**
- What is Ansible? How Ansible works
- Ansible Architecture (Control Node, Managed Nodes, Inventory)
- Setting up Master-Slave configuration
- Ansible Playbooks (YAML-based automation)
- Ansible Roles
- Applying configuration using Ansible

> **🧪 Hands-On Practice:**
- Configured an Ansible control node with managed nodes
- Wrote and executed Ansible Playbooks to automate server configuration
- Used Ansible Roles to manage reusable configurations

---

### 🔷 Day 6 — Container Orchestration | Kubernetes
> **Concepts Covered:**
- Introduction to Kubernetes (K8s)
- Kubernetes Architecture (Master Node, Worker Node, etcd, API Server, Kubelet)
- Kubernetes Installation (Minikube / Kubeadm)
- Creating Deployments using YAML files
- Services in Kubernetes (ClusterIP, NodePort, LoadBalancer)
- Ingress in Kubernetes

> **🧪 Hands-On Practice:**
- Deployed containerized applications on a Kubernetes cluster
- Wrote Kubernetes YAML manifests for Deployments and Services
- Configured Ingress for routing traffic

---

### 🔷 Day 7 — Continuous Monitoring | Nagios
> **Concepts Covered:**
- What is Continuous Monitoring? Why it matters
- Introduction to Nagios & Nagios Architecture
- Monitoring services using Nagios
- Nagios Plugins — what they are and how to use them
- Monitoring system information (CPU, memory, disk) with Nagios Plugins

> **🧪 Hands-On Practice:**
- Set up Nagios monitoring server
- Configured Nagios to monitor host and services
- Used Nagios Plugins to track system health metrics

---

## 🗂️ Repository Structure

```
devops-portfolio/
│
├── 01-git-github/
│   ├── git-commands.md          # Commonly used Git commands
│   └── branching-strategy.md   # Git branching workflow
│
├── 02-jenkins-cicd/
│   ├── Jenkinsfile              # Sample CI/CD Pipeline
│   └── jenkins-setup.md        # Jenkins setup guide
│
├── 03-docker/
│   ├── Dockerfile               # Sample Dockerfile
│   ├── docker-commands.md       # Docker commands reference
│   └── docker-compose.yml       # Sample Docker Compose file
│
├── 04-ansible/
│   ├── inventory                # Ansible inventory file
│   ├── playbook.yml             # Sample Ansible Playbook
│   └── roles/                   # Ansible Roles directory
│
├── 05-kubernetes/
│   ├── deployment.yaml          # K8s Deployment manifest
│   ├── service.yaml             # K8s Service manifest
│   └── ingress.yaml             # K8s Ingress manifest
│
├── 06-nagios/
│   ├── nagios-setup.md         # Nagios installation guide
│   └── monitoring-config/       # Nagios config files
│
└── README.md                    # This file
```

---

## 🏆 Key Projects

### 1. 🔁 End-to-End CI/CD Pipeline
> **Tools Used:** Git + Jenkins + Docker + Kubernetes
- Code pushed to GitHub → Jenkins triggers build → Docker image created → Deployed on Kubernetes

### 2. 📦 Dockerized Web Application
> **Tools Used:** Docker, Dockerfile, Docker Hub
- Built a web application container, pushed to Docker Hub

### 3. ⚙️ Automated Server Configuration with Ansible
> **Tools Used:** Ansible, Playbooks, Roles
- Automated installation and configuration of web servers across multiple nodes

### 4. 📊 Infrastructure Monitoring with Nagios
> **Tools Used:** Nagios, Nagios Plugins
- Set up monitoring for CPU, memory, and disk usage across servers

---

## 📈 DevOps Lifecycle — How It All Connects

```
Plan → Code (Git/GitHub) → Build (Jenkins) → Test (Jenkins) 
  → Package (Docker) → Deploy (Kubernetes) → Monitor (Nagios)
       ↑                                              |
       └──────────── Feedback Loop ──────────────────┘
```

---

## 📜 Workshop Certificate

- **Workshop:** Cloud Train — DevOps Workshop (7 Days)
- **Platform:** [www.thecloudtrain.com](https://www.thecloudtrain.com)
- **Topics Covered:** DevOps, Git/GitHub, Jenkins, Docker, Ansible, Kubernetes, Nagios

---

## 📬 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@email.com)

</div>

---

<div align="center">

⭐ **If you found this helpful, please star this repository!** ⭐

*Built with ❤️ after completing the Cloud Train DevOps Workshop*

</div>
