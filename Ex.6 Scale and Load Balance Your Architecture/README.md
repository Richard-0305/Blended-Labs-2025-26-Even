# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture

Author : RICHARD PRABU

Reg no : 212223060225

Date : 19-03-2026

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

1.Launch multiple servers.

2.Deploy the application on each server.

3.Create a load balancer.

4.Add servers to the load balancer.

5.Configure auto-scaling.

6.Test load distribution.
---

## Output Screenshots 

<img width="1261" height="531" alt="image" src="https://github.com/user-attachments/assets/c97b4417-77a1-4608-998d-77427197e5b0" />


<img width="1257" height="533" alt="image" src="https://github.com/user-attachments/assets/56055dfc-2e64-446d-9406-9943db6a30f7" />


<img width="1266" height="559" alt="image" src="https://github.com/user-attachments/assets/5d846d89-cb77-418a-a8c7-60dff31b108a" />


<img width="1264" height="594" alt="image" src="https://github.com/user-attachments/assets/c818e7a1-773c-409d-9c38-fcfdd31dcd76" />

<img width="1265" height="533" alt="image" src="https://github.com/user-attachments/assets/43b7e9fa-c477-457c-b7a1-a784ea9fa370" />

<img width="1265" height="532" alt="image" src="https://github.com/user-attachments/assets/54f9d934-352f-4626-aa5d-e21e1a518ad7" />

## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
