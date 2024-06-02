kubectl exec --stdin --tty pod/mysql-demo-pod-0 -- /bin/bash

kubectl rollout status deployment api-service -n nagpdemo


# NAGP 2024 Technology Band III Batch Workshop on Kubernetes & DevOps

## Assignment Overview

This project demonstrates deploying and managing a database and an API service within a Kubernetes (K8s) cluster, implementing ConfigMaps, Secrets, and horizontal scaling using a Horizontal Pod Autoscaler (HPA).

## Table of Contents

- [Project Structure](#project-structure)
- [Repository and Docker URLs](#repository-and-docker-urls)
- [Service API Tier](#showcase)
- [Video Demonstration](#video-demonstration)

## Project Structure
.
├── k8s
│ ├── db
│ │ ├── statefulset.yaml
│ │ ├── service.yaml
│ │ ├── configmap.yaml
│ │ ├── secret.yaml
│ │ └── persistentvolumeclaim.yaml
│ ├── api
│ │ ├── deployment.yaml
│ │ ├── service.yaml
│ │ ├── configmap.yaml
│ │ └── secret.yaml
│ ├── hpa.yaml
├── src
│ ├── api
│ │ ├── Dockerfile
│ │ ├── app.py
│ └── db
│ └── init-db.sql
└── README.md

## Repository and Docker URLs

- **GitHub Repository:** [Repository URL](<repository-url>)
- **Docker Hub Image for API Service:** [Docker Hub URL](https://hub.docker.com/repository/docker/singhsahil2711/db-access-service/general)

## Showcase

**URL to access Service API**
   - 

## Video Demonstration

- **Screen Recording:** [Video URL](<video-url>)
