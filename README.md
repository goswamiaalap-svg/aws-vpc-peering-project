# aws-vpc-peering-project
AWS VPC networking project with public and private subnets, route tables, Internet Gateway, and VPC peering.
# AWS VPC Peering Project

## Overview
This project demonstrates AWS networking using two Virtual Private Clouds (VPCs), public and private subnets, custom route tables, Internet Gateway routing, and VPC peering.

## Architecture
- **VPC A:** `10.10.0.0/16`
- **VPC B:** `10.20.0.0/16`
- Public and private subnet configuration
- Internet Gateway for public subnet internet access
- Route tables for local and inter-VPC traffic
- VPC peering connection between VPC A and VPC B

## Technologies Used
- Amazon Web Services (AWS)
- Amazon VPC
- Subnets and Route Tables
- Internet Gateway
- VPC Peering
- Amazon EC2 (if included in the final setup)

## Implementation Steps
1. Created and configured VPC A and VPC B.
2. Created public and private subnets.
3. Attached an Internet Gateway to VPC B.
4. Configured route tables for public and private subnets.
5. Configured VPC peering routes for communication between the VPCs.
6. Reviewed route table associations and route status.
7. Captured AWS console screenshots as project evidence.

## Screenshots
See the `screenshots/` directory for configuration evidence.

## Validation
Document successful connectivity tests here, including the source and destination instances, protocol, and result. Do not claim connectivity was verified unless you tested it.

## Learning Outcomes
- Understanding AWS VPC networking
- Configuring public and private subnet routing
- Understanding Internet Gateway routing
- Configuring routes for VPC peering
- Learning cloud networking fundamentals

## Security Notes
Never commit AWS access keys, private keys (`.pem`), passwords, or other credentials. Restrict SSH access to trusted IP addresses.
