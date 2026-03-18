# AWS CloudCore DevOps Project

## Project Overview

This project demonstrates a highly available AWS infrastructure using core DevOps and cloud services.

The system is designed to automatically scale, monitor performance, and recover from failures.

## Architecture Components

* Amazon VPC
* Public and Private Subnets
* Internet Gateway
* Application Load Balancer
* Target Group
* Auto Scaling Group
* EC2 Instances
* CloudWatch Monitoring
* SNS Alerts
* Lambda Auto-Healing

## Architecture Diagram

Internet
↓
Application Load Balancer
↓
Target Group
↓
Auto Scaling Group
↓
EC2 Instances
↓
CloudWatch → SNS → Lambda

## Key Features

* High availability infrastructure
* Automatic scaling
* Health checks and load balancing
* CPU monitoring with CloudWatch
* Email alert system using SNS
* Self-healing architecture using Lambda

## Tools & Services Used

AWS EC2
AWS VPC
Application Load Balancer
Auto Scaling
CloudWatch
SNS
Lambda
GitHub

## Learning Outcomes

* Designing multi-tier AWS architectures
* Implementing load balancing and auto scaling
* Monitoring infrastructure with CloudWatch
* Implementing automated alerting systems
* Understanding self-healing cloud infrastructure

