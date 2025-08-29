# AWS VPC with Terraform, EC2, and Application Load Balancer

**Featured blog:**  
Check out the full walkthrough and insights on Hashnode: [AWS VPC with Terraform (EC2 + ALB) by Jeet Kansagra](https://jeetkansagra.hashnode.dev/aws-vpc-with-terraform-ec2-alb).

---

## Description

This project uses Terraform to provision a basic AWS environment:
- A custom VPC with two public subnets in different Availability Zones.
- An Internet Gateway and Route Table for outbound internet access.
- A Security Group allowing HTTP and SSH access from anywhere.
- Two EC2 instances with user data scripts for initial setup.
- An Application Load Balancer that distributes traffic to the EC2 instances.
- Outputs the DNS name of the Load Balancer for easy access.

Ideal for demonstrating how to get started with AWS infrastructure as code using Terraform.

---

## Highlights

- **Modular and clear**: Each component (VPC, Subnets, IGW, SG, EC2, ALB) is defined cleanly.
- **Cross-AZ redundancy**: Two subnets in different zones improve resiliency.
- **User data included**: Automates web server configuration on EC2.
- **Immediate feedback**: Easily retrieve the load balancer’s DNS name once provisioned.
