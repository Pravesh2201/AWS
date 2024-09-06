# Assignment-01 (load Balancer & Auto Scaling Group) 
## Objective: 
The goal of this assignment is to design and implement a cloud infrastructure that supports the deployment of a Spring 3 Hibernate application. The infrastructure will be designed for high availability, scalability, and security. The application will be deployed on private servers to ensure a secure environment. 
Spring 3 Hibernate Link- 
https://github.com/opstree/spring3hibernate.git
  
Task Overview:  Infrastructure Design and Diagram Submission 
  
 -  Design a comprehensive infrastructure diagram. 
 -  The diagram should illustrate all key components, including networking, servers, load balancers, and auto-scaling groups. 
 -  Submit the diagram for review. 
 -  Final Implementation Code 

# Diagram

![Screenshot 2024-09-07 at 12 01 50 AM](https://github.com/user-attachments/assets/c55b7e87-512e-4022-9a4e-24f7abb82307)

# Basic Requirements
__________________________________________________________________________________________________________________________________________________________________________________
## Create VPC, 2 Subnets (Public and Private), Route Table, IGW Gateway, NAT Gateway

![VPC](https://github.com/user-attachments/assets/42603685-c7b6-431d-bf9e-68c63487fa74)

# Create a instance forspring3hibernate and make the AMI of it.

![Instances](https://github.com/user-attachments/assets/05287958-77b8-4424-854e-897cfaeedd8a)

![Launch_Template](https://github.com/user-attachments/assets/739ac10f-bc36-45b8-94bd-b18810625db1)

![Instance_launch_option](https://github.com/user-attachments/assets/72b6f38b-a49c-4609-8968-4d5817c9e9cd)


# Create a Target group for Load Balancer

![Target_group](https://github.com/user-attachments/assets/e1ed7a63-ef1b-46da-9bcf-c9cee758df01)

# Create a Load Balancer and attach Target Group to it.

![LB1](https://github.com/user-attachments/assets/5b9204ef-b4d8-4c08-9726-8fd5f77094e1)

![Loadbalancer_conf](https://github.com/user-attachments/assets/1a5dccf6-e0f3-4a69-82ba-99b5854efa56)

![LB_Final](https://github.com/user-attachments/assets/02293ea7-8c08-4f87-94ad-dd630cae6f7f)

# Create a Launch Template Create a Autoscaling group and attach Load Balancer to it.

![ASG](https://github.com/user-attachments/assets/f5bf6087-74a8-47c1-bd8e-41724d24c4d0)

![ASG2](https://github.com/user-attachments/assets/647939c6-9c6e-4360-a990-4f78abf55d19)


# Go to web browser and hit the Load Balancer dns

![o:p1](https://github.com/user-attachments/assets/3b8d65de-19a2-42f5-8c59-679480dd53cc)

![o:p2](https://github.com/user-attachments/assets/5caff539-e998-4b68-85c0-f64823257b3b)

![o:p3](https://github.com/user-attachments/assets/2331be04-5727-4cc0-b16c-ac75d4fab0b9)


