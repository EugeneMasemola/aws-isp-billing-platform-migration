# Architecture Overview

This project uses a secure AWS migration architecture designed for scalability, high availability, and operational reliability.

## Main Components

- Dev, UAT, and Production environments
- Public and private subnets
- EC2 instances for application and FreeRADIUS services
- Amazon RDS MariaDB with Multi-AZ
- Application Load Balancer
- Auto Scaling Groups
- Amazon S3 for storage and backup lifecycle policies
- CloudWatch for monitoring, logs, and alerts
- Security Groups for controlled access

## Security Design

Application and database resources are placed in private subnets where possible. Access is controlled using Security Groups, IAM permissions, and restricted network rules.

## Availability Design

The platform uses Multi-AZ RDS, load balancing, and Auto Scaling Groups to improve fault tolerance and reduce downtime.
