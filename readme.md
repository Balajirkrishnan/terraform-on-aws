# Terraform on AWS

This repository contains Terraform code for deploying infrastructure on AWS.

Refer: https://catalog.workshops.aws/terraform101/en-US/0-introduction

## Prerequisites

Before you begin, ensure you have the following:

- AWS account
- Terraform installed on your local machine

## Getting Started

To get started with this repository, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/terraform-on-aws.git`
2. Change into the project directory: `cd terraform-on-aws`
3. Initialize Terraform: `terraform init`
4. Configure your AWS credentials: `export AWS_ACCESS_KEY_ID=your-access-key AWS_SECRET_ACCESS_KEY=your-secret-key`
5. Customize the Terraform variables in `variables.tf` according to your requirements.
6. Deploy the infrastructure: `terraform apply`