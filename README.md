AWS Infrastructure Automation & Web Deployment using Terraform

Project Overview

This project demonstrates how to create and manage AWS infrastructure using Terraform and deploy a web server using Nginx.

The infrastructure is created as code using Terraform, while the EC2 instance is configured with Nginx to host a custom web page.

Architecture

```text
Internet
   |
   v
Internet Gateway
   |
   v
AWS VPC (10.0.0.0/16)
   |
   v
Public Subnet (10.0.1.0/24)
   |
   v
Security Group
   |
   v
EC2 Instance (t3.micro)
   |
   v
Nginx Web Server
   |
   v
Custom Website
```
Technologies Used
- AWS
- Terraform
- Linux
- Git
- GitHub
- Nginx
- SSH


Infrastructure Created with Terraform

Terraform is used to create and manage the following AWS resources:

- VPC
- Public Subnet
- Internet Gateway
- Route Table
- Route Table Association
- Security Group
- EC2 Instance


Web Server

An EC2 instance is used to host an Nginx web server.

Nginx is configured to serve a custom HTML web page, which can be accessed through the public IP address of the EC2 instance.


Terraform Commands

terraform init
terraform validate
terraform plan
terraform apply
terraform destroy

Project Structure

DevOps-Terraform-AWS/
|
|-- main.tf
|-- variables.tf
|-- outputs.tf
|-- README.md
|-- .gitignore

Security

- SSH access is restricted to the configured IP address.
- AWS credentials and private key files are not stored in the GitHub repository.
- Terraform state files are excluded using .gitignore.

Learning Outcomes

- Learned AWS infrastructure provisioning using Terraform.
- Practiced creating VPC, subnet, security group and EC2 resources.
- Learned how to configure Nginx on an EC2 instance.
- Practiced using Git and GitHub for version control.

Author

Created as part of a DevOps learning project using AWS and Terraform.
