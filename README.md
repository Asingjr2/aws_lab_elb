# AWS-LAB-ELB

### Purpose
- Used to quickly deploy multiple instances sitting behind asg and elb

### Requirements
- AWS account
- AWS console access

### Implementation (Stages) & Removal
- Navigate in AWS console to cloudformation and create stack `network_stack.yaml` entering required parameters
- Once above is complete, create stack `asg_lc.yaml` enter required parameteres

### AWS Cloud Resources
- VPC
- Subnet
- Route Table
- Route
- Security Group
- Autoscaling group
- Elastic Load Balancer
- IAM (multiple)

### Test
- To test successful deployment of aws cloud resources head to EC2 section of console
- Copy `Public DNS` or `IPv4 Public` into console and out basic message...you can refresh page to should automatic distribution of traffic to different servers by comparing instance id
![EC2_Console](/ec2_console.jpg)

