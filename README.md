# Mini Project

## Step 1

I created a stack named **“SampleNetworkCrossStack”** with the network template from https://dpaste.com/BLP6X5DE3

## Step 2

I drafted a YAML template named **“CF-MiniProject-Step2”** 

I provided parameters from the template I created
- InstanceType - t2.micro
- KeyName - Ebube-Key (my ssh key for us-west-2 region)
- NetworkStackName - SampleNetworkCrossStack

## Step 2

I created a stack with the same name **“CF-MiniProject-Step2”**

The stack (MiniProject-Step2) output showing the EC2 Instance
- Elastic IP
- Private IP
- PublicDNS


## Step 3

I checked the EC2 instance details to crosscheck with the CloudFormation stack.
