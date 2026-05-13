# AWS ISP Billing Platform Migration

## Overview
This project demonstrates the migration of a monolithic ISP billing platform from a VM-based environment to AWS. The solution was designed for high availability, scalability, secure networking, monitoring, and automated backups.

---

## Technologies Used
- AWS EC2
- Amazon RDS MariaDB
- Amazon S3
- Amazon VPC
- Application Load Balancer
- Auto Scaling Groups
- CloudWatch
- FreeRADIUS
- Linux
- Security Groups

---

## Key Features
- Designed AWS architecture for Development, UAT, and Production environments
- Migrated a monolithic VM-based system to AWS
- Implemented high availability using Multi-AZ RDS
- Configured Application Load Balancer for traffic distribution
- Used Auto Scaling Groups for scalability and resilience
- Deployed FreeRADIUS on EC2
- Configured secure UDP authentication using ports 1812 and 1813
- Designed secure VPC networking with public and private subnets
- Implemented monitoring for CPU, memory, logs, and alerts using CloudWatch
- Automated backups using RDS snapshots and S3 lifecycle policies
- Optimized the system to support 800 concurrent users

---

## Architecture
The platform uses a secure multi-environment AWS setup with:
- Load balancing
- Managed relational database services
- S3 storage
- Secure VPC networking
- Monitoring and alerting
- Scalable compute infrastructure

---

## Outcome
The migration improved:
- System resilience
- Scalability
- Fault tolerance
- Operational reliability

---

## Future Improvements
- Terraform Infrastructure as Code
- CI/CD pipeline automation
- Centralized logging
- Cost optimization dashboard
