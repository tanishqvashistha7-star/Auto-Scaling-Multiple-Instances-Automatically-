# AWS Auto Scaling with Load Balancer (High Availability Setup)

## 📌 Overview

This project demonstrates how to build a highly available and scalable infrastructure on AWS using Auto Scaling and Application Load Balancer (ALB).

---

## 🏗️ Architecture

* EC2 Instances (Web Servers)
* Launch Template
* Auto Scaling Group (ASG)
* Target Group
* Application Load Balancer (ALB)

Traffic Flow:
User → ALB → Target Group → EC2 Instances (Auto Scaled)

---

## ⚙️ Steps Performed

1. Launched an EC2 instance and configured Nginx web server
2. Created an AMI from the configured EC2 instance
3. Designed a Launch Template using the AMI
4. Created a Target Group (HTTP, Port 80)
5. Configured Health Checks for monitoring instance status
6. Created an Application Load Balancer (Internet-facing)
7. Linked ALB with the Target Group
8. Created an Auto Scaling Group using Launch Template
9. Set desired, minimum, and maximum instance capacity
10. Configured scaling policy based on CPU utilization
11. Tested load balancing and auto scaling using ALB DNS

---

## 🛠️ Technologies Used

* AWS EC2
* Auto Scaling Group
* Application Load Balancer (ALB)
* Target Groups
* Nginx
* Linux Commands

---

## 🔐 Features

* High Availability
* Automatic Scaling
* Load Distribution
* Health Monitoring

---


---

## 🚀 Outcome

Successfully implemented a scalable and highly available architecture where traffic is distributed across multiple EC2 instances and new instances are automatically launched based on demand.
