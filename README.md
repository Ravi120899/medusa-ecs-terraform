# Medusa + ECS Fargate + Terraform + GitHub Actions

Deploys Medusa headless backend on AWS ECS with Fargate using IaC.

## 🚀 Stack

- Terraform
- AWS ECS Fargate
- GitHub Actions CI/CD
- Docker

## 🔧 Setup

1. Add AWS credentials to GitHub repo secrets.
2. Push code to `main` branch.
3. GitHub Actions will deploy to ECS.

Access Medusa on port 9000 via public IP.
