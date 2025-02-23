# K8-101
K8 Sample Codes

1. K8Cluser-Docker :
    This sample project involves deploying an Nginx application in a Kubernetes cluster using a Deployment manifest.
    The deployment supports rolling updates to ensure zero downtime during updates.
    A Kubernetes Service is also created to expose the application, allowing external access.
    Docker Desktop is used as the Kubernetes environment for this deployment.

2. K8Multi-Pod :
   This sample project involves deploying a multi-pod backend service in a Kubernetes cluster using a Deployment manifest.
   The deployment ensures scalability and resilience through labels, selectors, and service discovery.
   A Kubernetes Service is also created to enable internal communication, and a client pod validates connectivity.
   Docker Desktop is used as the Kubernetes environment for this deployment.

3. K8Secret-Config :
   This sample project involves deploying an application in a Kubernetes cluster using a Deployment manifest while securely managing its configuration.
   The deployment integrates ConfigMaps for non-sensitive configuration values and Secrets for handling sensitive data.
   Environment variables from these resources are used to configure the application dynamically.
   Docker Desktop is used as the Kubernetes environment for this deployment.   


