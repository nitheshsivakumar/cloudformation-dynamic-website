# 🛒 Infrastructure as Code: Deploy a Dynamic Website on AWS with CloudFormation

## 📌 Project Overview

This project involves deploying a **dynamic e-commerce website** on **AWS** using **AWS CloudFormation** to provision and manage cloud infrastructure as code. The goal was to create an automated, scalable, and secure deployment for the application.

## 🎯 Problem Solved

- **Automated Infrastructure Deployment**: Eliminated manual setup by using **AWS CloudFormation** to define infrastructure in YAML.
- **Scalability & High Availability**: Used **Auto Scaling, Elastic Load Balancer (ELB), and Multi-AZ RDS** for reliability.
- **Security & Access Control**: Implemented **IAM roles, security groups, and HTTPS using AWS Certificate Manager**.
- **Database Automation**: Created and managed **Amazon RDS (MySQL)** via CloudFormation.
- **Repeatable & Consistent Infrastructure**: Deployed the entire stack in a structured and controlled manner.

---

## 🏗️ Architecture Overview

### 🔹 Key AWS Services Used
- **AWS CloudFormation** - Infrastructure as Code (IaC) for managing AWS resources.
- **Amazon VPC** - Custom networking with private and public subnets.
- **Internet Gateway & NAT Gateway** - Secure internet access for public and private instances.
- **Amazon EC2** - Hosting the web application.
- **Elastic Load Balancer (ELB)** - Distributing traffic across EC2 instances.
- **Auto Scaling Group** - Scaling EC2 instances based on demand.
- **Amazon RDS (MySQL)** - Managed database service with Multi-AZ deployment.
- **Amazon Route 53** - Managing DNS records for domain resolution.
- **AWS Certificate Manager (ACM)** - Enabling HTTPS for secure communication.
- **IAM Roles & Policies** - Managing permissions and access control.
- **Amazon S3** - Storing CloudFormation templates and static assets.
- **Amazon CloudWatch** - Monitoring application and infrastructure performance.

📌 **Reference Architecture:**  
![Architecture](Ecommerce-CloudFormation.jpg)

---

## 🚀 What I Did

1️⃣ **Defined Infrastructure as Code (IaC) using CloudFormation**  
- Created a **CloudFormation template** to define all AWS resources in YAML.  
- Used **parameterized stacks** for flexible deployment.  

2️⃣ **Provisioned EC2 Instances & Auto Scaling**  
- Deployed **EC2 instances** for the application layer.  
- Configured an **Auto Scaling Group** to dynamically adjust instances based on traffic.  

3️⃣ **Implemented Load Balancing & High Availability**  
- Used an **Application Load Balancer (ALB)** to distribute incoming traffic.  
- Deployed **Multi-AZ RDS (MySQL)** for database redundancy.  

4️⃣ **Automated Security & Networking Setup**  
- Defined **IAM roles and security groups** for access control.  
- Used **NAT Gateway** for secure internet access in private subnets.  

5️⃣ **Integrated Domain & SSL Encryption**  
- Managed **DNS records** via **Amazon Route 53**.  
- Configured **SSL certificates** via **AWS Certificate Manager** for HTTPS security.  

6️⃣ **Infrastructure Monitoring & Logging**  
- Enabled **Amazon CloudWatch** to monitor application health and performance.  
- Used **CloudFormation stack policies** to prevent accidental deletions.  

---

## 📊 Key Benefits

✅ **Automated Infrastructure** - Eliminates manual setup with CloudFormation.  
✅ **Scalable & Fault-Tolerant** - Auto Scaling and Multi-AZ RDS ensure reliability.  
✅ **Secure & Controlled Access** - IAM roles, VPC isolation, and HTTPS encryption.  
✅ **Cost-Optimized** - Dynamically scales resources to reduce unnecessary costs.  
✅ **Repeatable & Version-Controlled** - CloudFormation stacks make deployment consistent.  

---
