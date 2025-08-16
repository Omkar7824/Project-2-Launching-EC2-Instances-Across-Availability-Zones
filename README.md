# Project 2: Launching EC2 Instances Across Availability Zones

## 📌 Objective
Deploy multiple Amazon EC2 instances in different Availability Zones within the same AWS Region to improve availability and reliability.

## 🛠️ Architecture
![Architecture Diagram](./screenshots/Project-2.png)

## 🚀 Steps Performed
1. Launched an **Amazon EC2 instance** in **Availability Zone A** (`us-east-1a`).  
2. Attached an **Amazon EBS volume** to store persistent data.  
3. Configured a **user data script** to display instance details in a web browser.  
4. Launched a **second EC2 instance** in **Availability Zone B** (`us-east-1b`) as part of the DIY Goal.  
5. Verified that both instances were running independently in separate AZs.  

## ✅ Outcome
- Successfully launched **two EC2 instances** across multiple Availability Zones.  
- User data script executed correctly, showing instance metadata in the browser.  
- Improved **fault tolerance** by distributing workloads across AZs.  

## 🧰 AWS Services Used
- **Amazon EC2** – for launching compute instances.  
- **Amazon EBS** – for persistent storage.  
- **User Data** – for automated instance configuration.  
