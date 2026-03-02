# AWS-EC2-Auto-Scaling-With-Load-Balancer
AWS EC2 Auto Saling with Application Load Balancer Project demonstrating high availability and automatic scaling.

## Project Overview 
--Implemented AWS Auto Scaling to automatically adjust EC2 instances based on traffic demand. Integrated Application Load Balancer to distribute incoming traffic and ensure high availability, scalability, and cost optimization.

## Tools Usef
- AWS EC2
- Launch Template
- Auto Scaling Group
- Application Load Balancer
- Cloud Watch

  ## Architecture
  User --> ALB --> Auto Scaling Group --> EC2 Instances

  ## Key Configuration
  - Launch Template with Amazon Linux AMI
  - ASG deployed across multiple Availability Zone
  - Health check enabled
  - ClouWatch for scaling actioons
    
  ## Features
  - Automatic scale out and scale in
  - High availability across multiple AZs
  - Load distribution using ALB
  - Self-healing (unhealthy instances replaced automatically)
  - Performance monitoring with cloudWatch
