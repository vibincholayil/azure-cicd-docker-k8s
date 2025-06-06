# Manual CI/CD Pipeline Implementation with Azure DevOps, Docker, and Kubernetes.

## Introduction  
It’s a hands-on documentation of step-by-step implementation of a full CI/CD pipeline using Azure DevOps, Docker, and Kubernetes. I have deployed a secret-santa project at the end.  

---

## DevOps technologies used

- **Azure DevOps**
- **Docker**
- **Kubernetes (AKS)**
- **Azure Ubuntu VM**
- **GitHub**
- **Docker Hub**

## My steps:
 - Project Setting.
 - Ubuntu VM in Azure
 - Set up Azure DevOps agent and install Docker 
 - Connect GitHub for code and pipeline trigger 
 - Build Docker image and pushing to Docker Hub 
 - Create Kubernetes cluster in Azure 
 - Created release pipeline for K8s
 - Managing the app with Kubernetes and pipelines

## Step 1 : Project Setting  
Resource name: **Azure DevOps**

I have created a project setting in “Azure Devops organization”.   
Organization Name: “Vibincholayil”  

Settings change 1:  
Organization settings → Pipeline → Settings → [off] “Disable creation of classic build pipelines” and “Disable creation of classic release pipelines” (Enable this two option will help me to create new pipeline with “use the classic editor”)  
Settings change 2:  
Organization settings → Security → Policies → [on] “Allow public projects”  
I have created a project named “myproject”in my organisation  
Navigation Flow: My Azure DevOps Organizations → Create Project → Done  




