🚀 CI/CD Day 5 — Docker Hub → Kubernetes Deployment

Today I deployed my Dockerized application to Kubernetes using the image published on Docker Hub.

🔹 What I implemented:
• Created a Kubernetes Deployment
• Pulled Docker image from Docker Hub
• Verified Pod status
• Created a NodePort Service
• Exposed the application through Minikube
• Tested the application from the browser

🔹 Deployment Flow:

Docker Hub
   ↓
Kubernetes Deployment
   ↓
Pod
   ↓
NodePort Service
   ↓
Browser
   ↓
Hello from CI/CD ✅

🐳 Docker Image:
sathvika1203/cicd-day4-app:latest

☸️ Kubernetes:
Deployment: day5-app
Service: day5-service
Type: NodePort

This helped me understand how a container image moves from a registry into a Kubernetes environment and becomes an accessible application.

Next: Automating Kubernetes deployment through GitHub Actions.

#Kubernetes #Docker #CICD #DevOps #GitHubActions #CloudComputing #LearningInPublic

<img width="959" height="559" alt="Screenshot 2026-10-07 192622" src="https://github.com/user-attachments/assets/13511928-9640-4f1e-ba8f-33a1f248c78b" />
<img width="958" height="561" alt="Screenshot 2026-10-07 192640" src="https://github.com/user-attachments/assets/a769858a-1a75-4844-b1c8-5f5251916fac" />
<img width="959" height="563" alt="Screenshot 2026-10-07 192657" src="https://github.com/user-attachments/assets/1aa5008c-cb6d-4f26-a69b-58f9f6e34602" />


