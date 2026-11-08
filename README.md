# Azure Cloud Security Lab
This project demonstrates practical Azure cloud security skills using an Azure for Students subscription.

The lab focuses on:

 - Azure resource management
 - Virtual networking
 - Network segmentation
 - Network Security Groups
 - Activity Log investigation
 - Role-Based Access Control (RBAC)

# Environment
Subscription: Azure for Students

Region: Australia East

# Resources Created

 - # RG-SecLab
<img width="1262" height="1090" alt="Screenshot 2026-11-09 080948" src="https://github.com/user-attachments/assets/22785b46-5066-4a35-8258-7af97d403b5c" />
 
 - # VNET-SecLab

<img width="1284" height="834" alt="Screenshot 2026-11-09 081143" src="https://github.com/user-attachments/assets/1e687b84-1029-4785-9ef0-2f6743e69159" />

 - # Subnets

 <img width="1234" height="952" alt="Screenshot 2026-11-09 074646" src="https://github.com/user-attachments/assets/4d900a7f-bca2-4e99-b6f7-b7592bf33ae6" />
  
 - # NSG-Management

 <img width="1276" height="754" alt="Screenshot 2026-11-09 081411" src="https://github.com/user-attachments/assets/05febc2a-19e7-4653-97c8-49ee86543206" />

# Architecture Diagram

<img width="472" height="510" alt="Screenshot 2026-11-09 081639" src="https://github.com/user-attachments/assets/b26c5cb5-86da-48a1-bc36-9f6cf11c143d" />

# Security Review Report

Network Segmentation
Three separate subnets were deployed:
 - Management
 - Servers
 - DMZ
This reduces the risk of lateral movement and supports security-zone separation.

# Network Security Controls
A Network Security Group was deployed to establish traffic filtering capability.

# Logging
Azure Activity Logs were reviewed to verify:

 - Resource creation
 - Administrative actions
 - Successful deployment activities

<img width="1150" height="1294" alt="Screenshot 2026-11-09 082740" src="https://github.com/user-attachments/assets/628efa2f-0415-4dfc-b932-4b0987e4327b" />


# Future Hardening
Future improvements include:

 - Linux VM deployment
 - SSH key authentication
 - NSG rule tuning
 - Azure Monitor
 - Defender for Cloud

# Skills Demonstrated

 - Azure
 - Cloud Security
 - Network Security
 - RBAC
 - Azure Activity Logs
 - Virtual Networks
 - Security Architecture


