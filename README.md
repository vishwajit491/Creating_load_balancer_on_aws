# Creating_load_balancer_on_aws
AWS Application Load Balancer setup for distributing traffic across multiple EC2 instances with health checks and high availability.

# AWS Application Load Balancer (ALB)

## 📌 Project Overview

This project demonstrates how to configure an **AWS Application Load Balancer (ALB)** to distribute incoming web traffic across multiple Amazon EC2 instances.

The setup helps demonstrate important cloud concepts such as **traffic distribution, health checks, high availability, and scalable web application architecture**.

## 🏗️ Architecture

Internet
   ↓
Application Load Balancer
   ↓
Target Group
   ↓
EC2 Instance 1
   ↓
EC2 Instance 2

## ☁️ AWS Services Used

- Amazon EC2
- Application Load Balancer (ALB)
- Target Groups
- Security Groups
- VPC
- Availability Zones

## ⚙️ What I Implemented

- Created multiple EC2 instances
- Installed and configured a web server on the EC2 instances
- Created an Application Load Balancer
- Configured a Target Group
- Registered EC2 instances with the Target Group
- Configured HTTP listener on port 80
- Configured Security Groups
- Enabled health checks
- Tested traffic distribution through the Load Balancer DNS

## 🔍 Health Check

The Application Load Balancer continuously checks the health of registered EC2 instances.

If an instance becomes unhealthy, the Load Balancer stops sending traffic to that instance.

## 🧪 Testing

The ALB DNS name was opened in a web browser to verify that the application was accessible.

Different responses from the EC2 instances can be used to demonstrate traffic distribution.

## 🚀 Real-World Use Cases

- High-availability web applications
- E-commerce applications
- Production web servers
- Microservices applications
- Scalable cloud applications
- Applications requiring automatic health checks

## 📚 Key Concepts Learned

- Load balancing
- Target groups
- Health checks
- EC2 integration
- Security Groups
- High availability
- Traffic distribution
- Scalable AWS architecture

## 👨‍💻 Author

**Vishwajit Hulawale**

AWS | Cloud | DevOps Enthusiast
