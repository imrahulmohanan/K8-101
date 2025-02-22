# Kubernetes Deployment Guide

# Overview
Deploy a containerized Nginx web application on a Kubernetes cluster using Docker Desktop.

# Steps

1. Build & Test Docker Image
    docker build -t my-nginx-app .
    docker run -d -p 8080:80 --name nginx-4K8Cluster my-ngnx-app

2. Create Deployment (deployment.yaml)

    Apply the deployment : 
    kubectl apply -f deployment.yaml

3. Create Service (service.yaml)

    Apply the service:
    kubectl apply -f service.yaml

4. Access the Application
    
    http://localhost:30080
   
5. Cleanup

    kubectl delete -f service.yaml
    kubectl delete -f deployment.yaml
