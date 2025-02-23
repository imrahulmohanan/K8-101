# Kubernetes ConfigMaps & Secrets Sample

# Overview
Deploy an application in a Kubernetes cluster using ConfigMaps and Secrets for secure and dynamic configuration management.

# Steps:
1. Create a ConfigMap
   kubectl apply -f configmap.yaml

2. Create a Secret
   kubectl apply -f secret.yaml

3. Deploy the Application
   kubectl apply -f deployment.yaml

4. Verify Configuration by checking if the application reads and logs values from the ConfigMap and Secret:

   kubectl exec -it pod_name -- sh
    echo $DATABASE_URL
    echo $API_ENDPOINT
    echo $DB_PASSWORD
    echo $API_KEY

