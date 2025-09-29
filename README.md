# Mini Project

## Step 1

I created a stack named **“SampleNetworkCrossStack”** with the network template from https://dpaste.com/BLP6X5DE3


<img width="957" height="653" alt="1" src="https://github.com/user-attachments/assets/9087e92a-c31f-43a4-b772-f275553de341" />


## Step 2

I drafted a YAML template named **“CF-MiniProject-Step2”** 

I provided parameters from the template I created
- InstanceType - t2.micro
- KeyName - Ebube-Key (my ssh key for us-west-2 region)
- NetworkStackName - SampleNetworkCrossStack


<img width="1468" height="705" alt="2" src="https://github.com/user-attachments/assets/32d284dc-fea9-46f8-abed-6a973c780db2" />


## Step 3

I created a stack with the same name **“CF-MiniProject-Step2”**

The stack (MiniProject-Step2) output showing the EC2 Instance
- Elastic IP
- Private IP
- PublicDNS

<img width="805" height="699" alt="3" src="https://github.com/user-attachments/assets/c835eed0-9017-4394-ba36-f14f8baa8a7e" />

## Step 4

I checked the EC2 instance details to crosscheck with the CloudFormation stack.

The stack (MiniProject-Step2) output showing the 
Elastic IP
Private IP
PublicDNS


<img width="1207" height="687" alt="4" src="https://github.com/user-attachments/assets/99d79d94-ba0e-42ee-929c-715feb5f4fca" />

## Reference to the parameters used


<img width="1179" height="659" alt="5" src="https://github.com/user-attachments/assets/7ec34e50-f692-4d67-8ad3-d403c1aec1b5" />

### The EC2 Instance automatically created from the CloudFormation stack


<img width="1527" height="787" alt="6" src="https://github.com/user-attachments/assets/2c360534-49a9-4333-b3d7-1f97b7434d16" />


### Checking the Elastic IP (http://44.238.230.113/) for the apache installed 

<img width="771" height="312" alt="7" src="https://github.com/user-attachments/assets/9a647c1b-4329-478b-b594-4c18deca9524" />


