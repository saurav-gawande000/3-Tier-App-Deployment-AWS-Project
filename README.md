3-Tier Architecture Application Deployment on AWS
---
Overview
---
This project implements a scalable 3-tier web application architecture on AWS with:

Web Tier (Presentation Layer): NGINX servers

Application Tier (Business Logic Layer): Node.js servers

Database Tier (Data Layer): MySQL RDS instance
1. VPC Setup
   
   # Create VPC with CIDR 192.168.0.0/16
# Configure with:
# - 2 Availability Zones
# - 2 Public Subnets
# - 4 Private Subnets (APP1, APP2, DB1, DB2)
# - 1 NAT Gateway

