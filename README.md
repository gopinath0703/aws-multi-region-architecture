# 🌍 Multi-Region Architecture Simulation on AWS

## 📌 Project Overview
Deployed an application across multiple AWS regions (Mumbai and Singapore)
to understand high availability, latency differences, and global infrastructure.

## 🛠️ AWS Services Used
- Amazon EC2 (in multiple regions)
- Amazon S3
- Security Groups
- VPC (Basic)
- AWS Global Infrastructure

## 📋 Steps Followed
1. Launched EC2 instances in Mumbai (ap-south-1) region
2. Launched EC2 instances in Singapore (ap-southeast-1) region
3. Deployed same application in both regions
4. Compared response time and latency between regions
5. Analyzed cost and performance trade-offs
6. Understood high availability using global infrastructure

## 📈 Results
- Mumbai region showed lower latency for Indian users
- Singapore region served Southeast Asian users faster
- Understood importance of region selection for performance
- Achieved high availability by running in multiple regions

## 🏗️ Architecture
User Request → Route to Nearest Region → EC2 (Mumbai) / EC2 (Singapore)

## 💡 Key Learnings
- Region selection impacts application performance significantly
- Multi-region setup ensures high availability and disaster recovery
- Cost varies between AWS regions

## 👨‍💻 Author
**Gopinath T** — AWS Certified Solutions Architect
- GitHub: https://github.com/gopinath0703
- Email: gopinathdhanasampath23@gmail.com
