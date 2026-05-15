# aws-vpc-bastion-nat-project
# AWS Secure VPC Architecture Project

## 📌 Project Overview

This project demonstrates a secure AWS networking architecture using:

- VPC
- Public Subnet
- Private Subnet
- Internet Gateway
- NAT Gateway
- Route Tables
- Bastion Host
- EC2 Instances
- SSH Connectivity

---

# 🏗️ Architecture

Internet
↓
Internet Gateway
↓
Public Subnet
↓
Bastion Host
↓ SSH
Private Subnet
↓
Private EC2
↓
NAT Gateway
↓
Internet

---

# ⚙️ AWS Services Used

- Amazon VPC
- Amazon EC2
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups

---

# 🔥 Practical Skills Demonstrated

## AWS Networking
- VPC Creation
- Public & Private Subnets
- Route Tables
- Internet Gateway
- NAT Gateway

## Linux & SSH
- SSH Connection
- chmod 400
- Private Server Access

## Security
- Bastion Host Setup
- Secure Private Infrastructure

---

# 📸 Screenshots

## VPC
![VPC](Screenshot%202026-05-15%20141743.png)

## Internet Gateway
![IGW](Screenshot%202026-05-15%20141816.png)

## Subnets
![Subnets](Screenshot%202026-05-15%20141842.png)

## Route Tables
![RT](Screenshot%202026-05-15%20141919.png)

## EC2 Instances
![EC2](Screenshot%202026-05-15%20143441.png)

## Bastion Host SSH
![SSH](Screenshot%202026-05-15%20143857.png)

## Private EC2 Access
![Private SSH](Screenshot%202026-05-15%20144449.png)

## NAT Gateway
![NAT](Screenshot%202026-05-15%20145125.png)

## Internet Access from Private EC2
![Ping](Screenshot%202026-05-15%20145503.png)

---

# 🚀 Real-World Use Case

This architecture is used in production environments where:

- Private servers should not be directly exposed to the internet
- Secure SSH access is required
- Private instances need outbound internet access

---

# 👨‍💻 Author

Satyam Thorat
