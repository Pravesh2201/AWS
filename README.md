# Assignment-02 (Deployment Strategies)


In this assignment you have to learn about deployment strategies:
    -   Recreate deployment 
    -   Rolling deployment 
    -   Blue-green deployment 
    -   A/B  deployment
    -   Canary deployment 

After this you need to implement these 2 below deployment strategies:
Must Do
    -   Recreate deployment 
    -   Rolling deployment 

 Good To Do

    -    Blue Green deployment 
    -    Canary deployment 

 Recommendation

    -    Don't straight forward jump into creating the utility, first do it manually

           github-link --> https://github.com/OT-TRAINING/DeploymentStrategies
------------------------------------------------------------------------------------------------------------------------
# First Create a basic infra.
------------------------------------------------------------------------------------------------------------------------
# 1. VPC

![VPC](https://github.com/user-attachments/assets/c71afb09-69fa-45c0-bec4-fb7017580381)

# 2. Subnet

![Subnet](https://github.com/user-attachments/assets/7904f4ab-285f-48e3-9a37-97be01d1edcd)

# 3. Route Table

![RT](https://github.com/user-attachments/assets/41e06db4-8eaa-4175-b7ec-ac2ba232b83a)

# 4.  Load Balancer

![LB](https://github.com/user-attachments/assets/08c95aed-426b-4d7b-aeec-6adebbd77940)

# 5. Launch Template
![Launch](https://github.com/user-attachments/assets/abb6f0d3-1362-4fe9-a38c-7cd42aca927d)

# Create a autoscaling group using target traking policy and add the created launch template in it.

# Here I select the minimum and desired value 1 and max 2.
![ASG](https://github.com/user-attachments/assets/df0ebb3e-d534-4017-b5a8-9520f7645fde)
![ASG2](https://github.com/user-attachments/assets/e7f99578-ce14-4360-8ba3-c182bbb6282c)

![releaseV1](https://github.com/user-attachments/assets/69d2a27f-0f88-477a-a454-b3d5d70d7dcc)

![ASGresult](https://github.com/user-attachments/assets/6fce5e48-0eec-4951-88e9-16170855276c)

![BeforeDeployement](https://github.com/user-attachments/assets/795d4378-9948-43e7-9de8-2e8734e06d2b)

![releaseV2](https://github.com/user-attachments/assets/9fbc1919-d5e7-44b3-97ef-770a88dd2463)


