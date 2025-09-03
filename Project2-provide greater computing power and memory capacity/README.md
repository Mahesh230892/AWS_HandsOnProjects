# AWS Simulearn Project – Computing Solution  
> Scaling EC2 for Enhanced Performance and Metadata Management

## 🧩 Overview  
This project demonstrates how to upgrade an existing Amazon EC2 instance to provide greater computing power and memory capacity. It simulates a real-world scenario where a school’s class scheduling system requires improved performance and scalability.

## 🎯 Objectives  
- Scale up EC2 instance type to enhance compute and memory resources  
- Explore secure and efficient connection methods to EC2  
- Retrieve and analyze instance metadata  
- Practice operational tasks using AWS Systems Manager and EC2 Console

## 🛠️ Services Used  
- **Amazon EC2** – Virtual server provisioning and instance type management  
- **AWS Systems Manager** – Secure instance access via Session Manager  
- **EC2 Instance Connect** – Browser-based SSH access without key pair management  
- **Instance Metadata Service (IMDS)** – Retrieve runtime instance details

## 📌 Key Tasks Completed  
- ✅ Changed EC2 instance type from `t3.micro` to `m4.large`  
- ✅ Connected to EC2 using:
  - EC2 Instance Connect  
  - Session Manager  
  - SSH (where applicable)  
- ✅ Viewed instance metadata using public IP  
- ✅ Explored and compared instance families: `t3.large`, `c5.large`, `r5.large`  
- ✅ Validated instance upgrade via AWS test server

## 📂 Application Interaction  
Connected to the sample application hosted on EC2 using terminal commands:
```bash
cd sample_app/
ls
tail -f aws_compute_solutions.log
