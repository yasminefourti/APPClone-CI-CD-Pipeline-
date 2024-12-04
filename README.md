# Youtube clone - CI/CD Pipeline 🚀
## CI/CD Pipeline for Deploying a Secure Video Streaming Application on AWS

This project focuses on implementing a Continuous Integration (CI) and Continuous Deployment (CD) pipeline using Jenkins. The goal is to deploy a clone of the YouTube application to Amazon Elastic Container Registry (ECR) while incorporating security vulnerability scanning with Trivy. The pipeline also integrates SonarQube for static code analysis and quality gate checks.

### Project Overview

This project demonstrates deploying an **Youtube clone** using a set of DevOps tools and practices:

- **Static Code Analysis:** Performs static code analysis and enforces a **Quality Gate** using **SonarQube**.
- **Containerization:** Builds a Docker image for the project, tags it, and pushes it to **Amazon ECR**.
- **Vulnerability Scanning:** Scans the Docker image for vulnerabilities using **Trivy** and produces a detailed report.
- **Infrastructure as Code (IaC):** Uses **Terraform** to provision an **EKS cluster** and its related resources.
- **Continuous Deployment:** Deploys the application to Kubernetes using **ArgoCD** and **Kubernetes YAML files**.
- **Monitoring and Observability:** Monitors the application's pods using **Grafana** and **Prometheus**.


### ⚙️  Tools & Technologies:

1. **Terraform**: Infrastructure as Code (IaC) tool used to create AWS resources such as EC2 instances and EKS clusters.  
2. **GitHub**: Source code management platform for version control.  
3. **Jenkins**: Automation server used for managing the CI/CD pipeline.  
4. **SonarQube**: Platform for continuous inspection of code quality and security vulnerability analysis.  
5. **NPM**: Build tool for Node.js projects.  
6. **Aqua Trivy**: Security vulnerability scanner for Docker images.  
7. **Docker**: Containerization tool for creating and managing application containers.  
8. **AWS ECR (Elastic Container Registry)**: Fully managed Docker container registry for storing Docker images.  
9. **AWS EKS (Elastic Kubernetes Service)**: Managed container orchestration platform to deploy and manage Kubernetes clusters.  
10. **AWS CLI**: Command-line interface for interacting with AWS services.  
11. **ArgoCD**: Continuous deployment tool for Kubernetes applications.  
12. **Prometheus & Grafana**: Monitoring and alerting tools for visualizing metrics and ensuring application performance. 

## 🙌 Contributors

- **Yasmine Fourti** - DevOps Engineer ([GitHub Profile](https://github.com/yasminefourti))  




