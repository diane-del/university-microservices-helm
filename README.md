# University Microservices - Kubernetes & Helm

This project contains the Kubernetes and Helm deployment configuration for a University Microservices architecture.

## Architecture

The system is composed of:

- API Gateway
- Student Service
- Course Service
- Enrollment Service
- Grade Service
- PostgreSQL databases per service

All services are containerized with Docker and deployed on Kubernetes using Helm charts.

---

## Technologies Used

- Java Spring Boot
- Docker
- Kubernetes
- Helm
- ArgoCD
- PostgreSQL

---

## Project Structure
helm/
└── University/
├── Chart.yaml
├── values.yaml
├── templates/
└── charts/


---

## Deployment

Install with Helm: helm install university ./helm/University


Or deploy using ArgoCD via Helm source.

---

## Author

Diane Dongmo Feulefack
