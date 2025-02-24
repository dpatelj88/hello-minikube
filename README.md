# hello-minikube Project

# 1. Install Prerequisites
Make sure you have the following installed:

Docker Desktop (with Kubernetes enabled)

Minikube

kubectl (Kubernetes CLI)

VS Code (with Docker and Kubernetes extensions)

# 2. Create a Simple Docker App 
Open VS Code and create a new directory for hello-minikube project.

mkdir hello-minikube

cd hello-minikube

code .

# 3. Create OR Copy 
Dockerfile and deployment.yaml files from this repo

# 4. Command 
kubectl apply -f deployment.yaml

kubectl get pods

kubectl get svc

minikube service hello-minikube-service --url

# 5. checking pod log

kubectl logs -f hello-minikube-service

# 6. Delete deployment if needed

kubectl delete deployment hello-minikube
