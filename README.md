# AWS-VPC-Setup
AWS Virtual Private Network + Load Balancer

# Amazon AWS Cloud Practitioner Certification Challenges 

![AWS VPC](https://img.shields.io/badge/AWS-UnderConstruction-orange)

:wave: :wave: :wave: :wave: :wave:

#AWS Certified Cloud Practitioner Foundational

:star: :star: :star:

My Personal AWS VPC from scratch connecting subnets, creating Internet Gateway, Route Tables, Subnet Associations and ssh into the server.

## Intro for project

Steps Involved:

- ✅ Create 1 VPC in AWS Console
- ✅ Create 2 subnets then attatch them to the VPC created
- ✅ Give the subnets IPv4 CIDRs 
- ✅ Create internet gateway so we have internet
- ✅ Attatch internet gateway to VPC 
- ✅ Go to VPC's main route table and edit the routes
- ✅ give the destination the universal IP address and target the internet Gateway and save changes
- ✅ go to subnet associations and add the 2 subnets created and save associations
- ✅ now go to the EC2 (Virtual servers in the cloud) dashboard and create an Instance (launch instance)
- ✅ name the server and choose a distrubution
- ✅ create new key pair (if one isnt already available) if so select it
- ✅ under networking settings edit and select the VPC and subnet created
- ✅ enable auto-assign public IP address
- ✅ ssh protocol should be TCP port 22
- ✅ launch instance and repeat for 2nd instance
- ✅ for windows it will be RDP instead of ssh and the port will be 3389 
- ✅ go to the instance you want to run and select connect
- ✅ for the ssh client open a terminal on Apple (different for windows will document later)
- ✅ cd into the folder the key pair is in and run the commands
- ✅ run chmod 400 + name of key pair (to ensure key is not publicly visible)
- ✅ run ssh -i "key pair name" ec2-user@ + IP given
- ✅ select yes on the dialog prompt
- ✅ you should see Amazon Linux 2 AMI logo if done correctly
- ✅ run logout to close connection and get back to your shell
- ✅ for windows server select instance and go to RDP client 
- ✅ select password and upload private key to decrypt
- ✅ decrypt password 
- ✅ copy password
- ✅ download remote desktop file
- ✅ open download remote desktop file
- ✅ paste password to launch instance
- ✅ select yes to continue on pop up dialouge box
- ✅ you should see your instance live


- [x] Figure how to ping from one server to another
- [x] Write a Blog Post on Hashnode about the experience.

[My version of the code found Below](https://github.com/BenjaminBurton/AWS-VPC-Setup/blob/main/README.md)

```js
https://github.com/BenjaminBurton/AWS-VPC-Setup/blob/main/README.md

```

## Load Balancer / Jump Server Setup

- ✅ create load balancer using classic load balancer
- ✅ name load balancer
- ✅ attatch VPC inside create LB inside dropdown
- ✅ add the subnets by selecting the plus icons next to them under available subnets Actions
- ✅ next assign security groups
- ✅ create a new security group (type http)
- ✅ next configure security settings
- ✅ next configure health check (ignore warning on page)
- ✅ next add EC2 instance
- ✅ select both instances created
- ✅ next add tags
- ✅ review and create
- ✅ create


## Infrastructure As Code (IaC)

- ❌

## Blog Post

- ❌ Write about experience in Blog post on HashNode

## Issues Encountered

- ❌ Actively Finding resolution to Issue with pinging back and forth

- ❌ Under Construction
