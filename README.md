# aws-vpc-networking-project
AWS VPC &amp; Networking Project showcasing VPC creation, peering, and route configuration


## Description
This project demonstrates my hands-on experience with AWS networking by designing and implementing a secure, scalable network architecture using multiple Virtual Private Clouds (VPCs). The project focuses on network isolation, private communication between environments, and high availability.

## Project Details
- Created two separate VPCs with non-overlapping CIDR blocks:
  - Test VPC: 10.0.0.0/24
  - Production VPC: 192.0.0.0/16

- Designed public and private subnets across different Availability Zones:
  - Public subnet in us-east-2b
  - Private subnet in us-east-2c

- Established a VPC Peering connection between the two VPCs for secure, private communication.

- Configured route tables for seamless traffic flow and validated connectivity between EC2 instances.

- ## Screenshots

### VPC & Network Setup
![VPC Creation and CIDR Configuration](screenshots/vpc-creation-cidr.png)

### Subnet Architecture
![Public Subnet Setup](screenshots/public-subnet-setup.png)
![Private Subnet Setup](screenshots/private-subnet-setup.png)

### Internet Access & Routing
![Internet Gateway and Route Table Configuration](screenshots/internet-gateway-routing.png)

### VPC Peering Configuration
![VPC Peering Request](screenshots/vpc-peering-request.png)
![VPC Peering Acceptance](screenshots/vpc-peering-acceptance.png)

### Connectivity Validation
![Inter-VPC Network Ping Test](screenshots/network-ping-test.png)


## Skills & Technologies Used
AWS VPC, Subnets, Route Tables, Internet Gateway, VPC Peering, Availability Zones, EC2 Networking

## Outcome
Successfully implemented a production-style AWS networking architecture that separates test and production environments while maintaining secure private connectivity.

