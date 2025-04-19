🚀 TASK 5: Build a Kubernetes Cluster Locally with Minikube

🎯 Objective

Deploy and manage an application in Kubernetes using Minikube.

🛠️ Tools Required

Minikube

kubectl

Docker (optional for custom images)

✅ Steps to Complete the Task

1️⃣ Install Minikube & Start the Cluster

minikube start

To verify:

kubectl get nodes
2️⃣ Create Deployment YAML

deployment.yaml

Apply the deployment:

kubectl apply -f deployment.yaml

3️⃣ Expose the App using a Service

service.yaml

Apply the service:

kubectl apply -f service.yaml

To access the app:

minikube service my-app-service

4️⃣ Verify Pods and Services

kubectl get pods

kubectl get services

5️⃣ Scale the Deployment

kubectl scale deployment my-app-deployment --replicas=4

kubectl get pods

📸 Deliverables

deployment.yaml and service.yaml files.

Screenshots of:

kubectl get pods

kubectl get services

App running in the browser
