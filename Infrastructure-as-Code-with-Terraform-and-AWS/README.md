# Terraform AWS Infrastructure

This project demonstrates how to use Terraform to set up a scalable infrastructure on AWS. It provisions an entire VPC with public and private subnets, security groups, and an EC2 instance.

### Technologies
- Terraform
- AWS (VPC, EC2, RDS, S3)
- GitHub Actions (for automated deployments)

### Usage
- Clone the repo
- Update the `terraform.tfvars` with your AWS credentials
- Run `terraform apply`

### Features
- Highly available infrastructure with public/private subnets
- Security group management for controlled access
- Automated CI/CD pipeline to apply changes
