# Aws-wordpress-cloudformation-infrastructure
Highly available WordPress deployment using AWS CloudFormation and infrastructure automation

## 📌 Project Overview

This project demonstrates automated deployment and monitoring of a highly available WordPress environment using AWS CloudFormation and AWS infrastructure services.

The solution provisions a production-ready WordPress instance on Amazon EC2 and implements monitoring, scalability, and infrastructure automation using Infrastructure as Code (IaC) principles.

The project also includes a separate development/testing environment configured using Auto Scaling Scheduled Actions to optimize cloud resource usage during business hours.

---

## 🎯 Objectives

* Deploy a live WordPress environment using AWS CloudFormation
* Create a reusable Amazon Machine Image (AMI)
* Configure a development/testing environment using Auto Scaling Groups
* Automate infrastructure deployment using Infrastructure as Code
* Monitor production availability using Route53 Health Checks
* Optimize infrastructure cost using scheduled scaling policies

---

## 🛠️ AWS Services Used

| AWS Service                | Purpose                         |
| -------------------------- | ------------------------------- |
| AWS CloudFormation         | Infrastructure as Code          |
| Amazon EC2                 | WordPress Hosting               |
| Auto Scaling Group         | Dev/Test Environment Automation |
| Amazon Machine Image (AMI) | Reusable Server Image           |
| Route53 Health Checks      | Monitoring & Availability       |
| Security Groups            | Network Security                |
| Amazon VPC                 | Networking Infrastructure       |

---

## ⚙️ Project Workflow

1. CloudFormation template provisions WordPress infrastructure
2. EC2 instance launches automatically
3. WordPress and MySQL are configured
4. Production environment becomes publicly accessible
5. AMI is created from production server
6. Dev/Test environment is deployed using Auto Scaling Group
7. Scheduled Actions automatically start and stop development resources
8. Route53 Health Checks monitor production availability

---

## 🧱 Infrastructure Components

The project provisions the following resources:

* EC2 WordPress Instance
* Security Groups
* Auto Scaling Group
* Scheduled Scaling Policies
* Route53 Health Checks
* WordPress Web Server
* MySQL Database
* Amazon Linux Environment

---

## 📂 Repository Structure

```bash
aws-wordpress-cloudformation-infrastructure/
│
├── cloudformation/
│   └── wordpress-template.json
│
├── screenshots/
│   ├── project-architecture.png
│   ├── cloudformation-stack.png
│   ├── wordpress-production-instance.png
│   ├── ami-creation.png
│   ├── auto-scaling-group.png
│   ├── route53-health-check.png
│   └── wordpress-website-running.png
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## 🚀 Key Features

* Automated WordPress deployment using CloudFormation
* Infrastructure as Code (IaC)
* Production and Development environments
* Auto Scaling Scheduled Actions
* Route53 Health Monitoring
* Reusable AMI deployment strategy
* AWS infrastructure automation

---

## 🔒 Security Best Practices

* Controlled SSH access using Security Groups
* Parameterized database credentials
* Infrastructure provisioning through CloudFormation templates
* Environment separation between production and development

---

## 🔮 Future Improvements

* Integrate RDS instead of local MySQL
* Add Elastic Load Balancer (ELB)
* Configure HTTPS using ACM
* Add CloudWatch Monitoring
* Implement Multi-AZ architecture
* Add CI/CD deployment pipeline

---

## 👨‍💻 Author

Devang Mehta

AWS Cloud & DevOps Portfolio Project

