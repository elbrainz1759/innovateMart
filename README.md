Terraform infrastructure for deploying InnovateMart's retail store application on Amazon EKS.

## 📋 Project Overview

This project provisions a production-grade EKS cluster for InnovateMart's microservices application.

## 🏗️ Architecture

- **VPC** with public and private subnets across 3 AZs
- **EKS Cluster** with managed node groups
- **IAM Roles** with least privilege access
- **CI/CD Pipeline** using GitHub Actions

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/elbrainz1759/innovateMart.git
cd innovateMart

# Initialize Terraform
cd infrastructure/environments/prod
terraform init

# Plan and apply
terraform plan
terraform apply
 
