# Youtube clone - CI/CD Pipeline 🚀
## CI/CD Pipeline for Deploying a Secure Video Streaming Application on AWS

This project focuses on implementing a Continuous Integration (CI) and Continuous Deployment (CD) pipeline using Jenkins. The goal is to deploy a clone of the YouTube application to Amazon Elastic Container Registry (ECR) while incorporating security vulnerability scanning with Trivy. The pipeline also integrates SonarQube for static code analysis and quality gate checks.

### Project Overview

-Performs static code analysis and Quality Gate using sonarqube
-Builds a Docker image for the project and Tags and pushes the Docker image to ECR.
-scans the Docker image for vulnerabilities and produces a report.
-Use Terraform to create an EKS cluster and related resources.
-Use ArgoCD to deploy the application using Kubernetes YAML files. The pods are monitored using Grafana & Prometheus.

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




