Hanumat Kripa ❤️
# Deploy Application on Amazon EKS

This project demonstrates deploying and exposing a containerized application on **Amazon EKS (Elastic Kubernetes Service)** using Kubernetes.

---

## Project Summary

- Provisioned an Amazon EKS cluster using eksctl
- Configured managed EC2 worker nodes
- Deployed an Nginx container on Kubernetes
- Exposed the application using Service type LoadBalancer
- Accessed the application via AWS ELB public DNS

---

## Tools & Services

- Amazon EKS
- Kubernetes
- EC2
- eksctl
- kubectl
- Docker

---

## Architecture

User → AWS Load Balancer → Kubernetes Service → Pod (Nginx)

---

## Result

The application was successfully deployed and accessed publicly.

---
## Screenshots

### Amazon EKS Cluster
[
](https://github.com/iamdeepaktiwari08/AWS-eks-nginx-deployment/blob/main/eks-nginx-deployment/%E2%94%80%20screenshots/AWS-EKS-CLUSTER.PNG)
### EC2 Instance
![EC2](./─%20screenshots/AWS-EC2.png)

### Kubernetes Deployment (Terminal)
![Terminal](./─%20screenshots/terminal.png)

### Application Output (Nginx)
![Nginx](./─%20screenshots/Nginx.png)
- Hands-on experience with Amazon EKS
- Understanding of Kubernetes Deployments and Services
- Real-world troubleshooting of node group and networking issues
## Thank You

Thank you for visiting this repository.  
Your feedback is appreciated.
