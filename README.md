# Terraform AWS Infrastructure 🚀

This project builds a modular AWS infrastructure using Terraform and includes CI/CD automation via GitHub Actions.

It provisions:
- ✅ Multiple EC2 instances
- ⚖️ An Application Load Balancer (ALB)
- 🛢 An RDS PostgreSQL database
- 📦 An S3 bucket for logs or storage
- 🔄 GitHub Actions CI/CD for Terraform

Everything is modular:

- `modules/ec2/`
- `modules/alb/`
- `modules/rds/`
- `modules/s3/`

## ✅ How to Use

```bash
terraform init
terraform plan
terraform apply

