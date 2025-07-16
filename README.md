# CI/CD with GitHub Actions & Kubernetes

This project demonstrates a CI/CD pipeline using GitHub Actions to build a Flask app, create a Docker image, push it to DockerHub, and deploy it to a Kubernetes cluster.

## Steps
 Push to `main` branch  
 Docker image is built & pushed  
 Kubernetes Deployment & Service are updated
### Requirements
- Kubernetes cluster with access (minikube, EKS, GKE, etc.)
- DockerHub account
- GitHub repo with secrets configured

### Secrets to add:
 Name              Description                

 DOCKER_USERNAME   DockerHub username        
 DOCKER_PASSWORD   DockerHub password/token  
 KUBE_CONFIG       kubeconfig content        
