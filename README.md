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
├── k8s
│ ├── db
│ │ ├── sql-stateful-set.yaml
│ │ ├── headless-sql-svc.yaml
│ │ ├── sql-config-map.yaml
│ │ ├── sql-secret.yaml
│ │ └── sql-pv.yaml
│ │ └── sql-pvc.yaml
│ ├── api
│ │ ├── app-deployment.yaml
│ │ ├── app-horizontalpodscaling.yaml
│ │ ├── app-service.yaml
│ │ ├── app-config-map.yaml
│ │ └── app-secret.yaml
├── src
│ ├── api
│ │ ├── Dockerfile
│ │ ├── app.js
│ │ ├── package.js
│ │ ├── package-lock.js
└── insert-query.sql
└── README.md

## Repository and Docker URLs

- **GitHub Repository:** [Repository URL](<repository-url>)
- **Docker Hub Image for API Service:** [Docker Hub URL](https://hub.docker.com/repository/docker/singhsahil2711/db-access-service/general)

## Showcase

**URL to access Service API**
   - 

## Video Demonstration

- **Screen Recording:** [Video URL](<video-url>)
