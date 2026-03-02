# EKS DevOps Platform

## Overview
This project demonstrates a **full DevOps workflow**:

- Flask microservice development
- Docker containerization
- Kubernetes deployment
- Terraform for AWS infrastructure

The goal is to showcase a **production-ready deployment workflow** using modern DevOps practices.

---

## Features
- Flask API endpoints:
  - `/` : Returns a JSON message with the hostname
  - `/health` : Returns service health status
- Dockerized application
- Kubernetes Deployment and Service
- Terraform scripts for infrastructure provisioning
- CI/CD readiness (ready to integrate with GitHub Actions, Jenkins, etc)

---

## Project Structure

eks-devops-platform/
├── app/ # Flask app code
├── kubernetes/ # Kubernetes manifests
├── terraform/ # Terraform scripts
├── Dockerfile
├── README.md
└── .gitignore
