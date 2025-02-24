Scalable Tier 3 application on AWS

**React frontend**, **Node.js backend**, **PostgreSQL RDS database**, all managed with AWS services. The architecture ensures **high availability, scalability, and security**.

## Architecture Diagram
![3-Tier Architecture Diagram](https://your-aws-diagram-url.png)

## Technologies & AWS Services Used
- **Frontend:** React, hosted on **S3 + CloudFront**
- **Backend:** Node.js (Express.js) running on **EC2 + Load Balancer**
- **Database:** PostgreSQL on **Amazon RDS**
- **Networking & Security:** **VPC, Security Groups, IAM Roles**
- **Scalability:** **Auto Scaling Groups & Application Load Balancer (ALB)**
- **Infrastructure as Code:** Terraform / CloudFormation

## Features
Highly scalable and secure architecture  
Fully automated deployment using **Terraform**  
Load-balanced **EC2 instances** for backend services  
Hosted **React frontend** with a CDN via CloudFront  
**Database tier using Amazon RDS** for persistence  
**IAM Roles & Security Groups** for access control  
