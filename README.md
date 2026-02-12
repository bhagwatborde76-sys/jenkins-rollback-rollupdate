# jenkins-rollback-rollupdate

# CI/CD Pipeline with Jenkins, Docker, Kubernetes (Rolling Update & Rollback)

This project demonstrates a production-style **CI/CD pipeline** that automates containerized application deployment to Kubernetes using **Jenkins**.  
It includes **Docker image build, AWS ECR push, Kubernetes deployment, rolling updates, and rollback strategy**.

The goal of this project is to showcase practical **DevOps pipeline implementation** and **deployment lifecycle management**.

---

## Architecture Overview

GitHub → Jenkins Pipeline → Docker Build → AWS ECR → Kubernetes (EKS) → Service Exposure

---

## Tech Stack

**CI/CD**
- Jenkins Pipeline

**Containerization**
- Docker

**Container Orchestration**
- Kubernetes (EKS)

**Cloud**
- AWS ECR
- AWS EKS

**Other Tools**
- GitHub
- kubectl
- Linux

---

## Repository Structure

.
├── Dockerfile
├── jenkins-file
├── deployment.yaml
├── app1-svc.yaml
├── index.html
└── app2/
