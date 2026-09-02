# 👋 Hi, I'm Ayub

☁️ Designing and automating production-style cloud infrastructure 🚀

## About Me

DevOps/Cloud Engineer with a background in Computer Science, building hands-on, production-style AWS infrastructure. Focused on infrastructure as code, containerisation, and secure, automated CI/CD.

🔭 Currently learning Kubernetes, working toward an EKS-based deployment next.

## Tech Stack

![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?logo=amazons3&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?logo=amazonaws&logoColor=white)
![CI/CD](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![OIDC](https://img.shields.io/badge/OIDC-2E8B57?logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-CC0000?logo=linux&logoColor=white)
![Route53](https://img.shields.io/badge/Route%2053-1B660F?logo=amazonaws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)

## Featured Projects

### [Gatus — AWS ECS Monitoring Platform](https://github.com/01-Ayubmohamed/ecs-project)
Production-style monitoring platform deployed on AWS ECS Fargate, built with a two-stack Terraform architecture (8 reusable modules, 48 resource blocks). Hardened multi-stage Docker build (2.54GB → 48.3MB, a 98% reduction), 4 OIDC-authenticated GitHub Actions pipelines, security scanning via Grype and Checkov, and a local pre-commit hook suite enforcing the same checks before code reaches CI.

**Tech:** AWS • ECS Fargate • Terraform • GitHub Actions • OIDC • Docker • Grype • Checkov • Route 53 • ACM

### [WordPress on AWS (Terraform)](https://github.com/01-Ayubmohamed/wordpress-terraform)
3-tier WordPress deployment (ALB, EC2, RDS MySQL) provisioned through 4 reusable Terraform modules, with least-privilege security groups isolating each layer and automated installation via cloud-init.

**Tech:** AWS • EC2 • RDS • ALB • Terraform • cloud-init

### [Highly Available ALB Web App](https://github.com/01-Ayubmohamed/alb-autoscaling-web-app)
Scalable, highly available web application spanning 2 Availability Zones, with an Auto Scaling Group (2-4 instances), an Application Load Balancer with health checks, and HTTPS via Route 53 and ACM.

**Tech:** AWS • EC2 • ALB • Auto Scaling • Route 53 • ACM

### [VPC with Bastion Host](https://github.com/01-Ayubmohamed/vpc-bastion-host)
Secure custom VPC with a public bastion host and a private EC2 instance, restricted security groups, a NAT gateway for outbound-only access, and CloudWatch monitoring.

**Tech:** AWS • VPC • EC2 • NAT Gateway • CloudWatch

### [Flask & Redis Container App](https://github.com/01-Ayubmohamed/docker-redis-web-app)
Multi-container application with a Flask web app and Redis, orchestrated with Docker Compose, using a Docker volume to persist data across container restarts.

**Tech:** Docker • Docker Compose • Flask • Redis
