# AWS Infrastructure Automation & Web Deployment using Terraform

## 📌 Project Overview

This project demonstrates how to create and manage AWS infrastructure using Terraform and deploy a web server using Nginx.

The infrastructure is created as code using Terraform, while the EC2 instance is configured with Nginx to host a custom web page.

## 🏗️ Architecture

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
```text

## 🛠️ Technologies Used

- AWS
- Terraform
- Linux
- Git
- GitHub
- Nginx
- SSH
