# S3 Bucket Creation Using Terraform

This project demonstrates how to create and manage an AWS S3 bucket using Terraform.
It follows Infrastructure as Code (IaC) principles, allowing you to provision, update,
and destroy AWS resources in a consistent, repeatable, and version-controlled way.

This repository is intended for:
- Beginners learning Terraform + AWS
- DevOps practice projects
- Interview preparation
- Reusable boilerplate for real projects

---

## What This Project Does

- Creates an AWS S3 bucket
- Uses variables for flexibility
- Outputs useful resource information
- Follows Terraform best practices
- Can be easily extended for production use

---

## Prerequisites

Before you start, make sure you have:

- An AWS account
- An IAM user or role with S3 permissions
- AWS CLI installed and configured
- Terraform installed (v1.x recommended)

Verify installations:
```bash
aws --version
terraform --version
