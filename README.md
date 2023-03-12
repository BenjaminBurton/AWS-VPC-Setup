# AWS-VPC-Setup
AWS Virtual Private Network

# Amazon AWS Cloud Practitioner 

![AWS VPC](https://img.shields.io/badge/AWS-UnderConstruction-orange)

:wave: :wave: :wave: :wave: :wave:

#AWS Certified Cloud Practitioner Foundational

:star: :star: :star:

My Personal AWS VPC from scratch connecting subnets, creating Internet Gateway, Route Tables, Subnet Associations and ssh into the server.

## Intro for project

Steps Involved:

- ✅ Create VPC in AWS Console
- ✅ Create subnets to link to the VPC
- ✅ Create Internet Gateway after IG is created attach the VPC
- ✅ Create Route Tables and attach to the VPC
- ✅ Edit the route and apply the universal IP 0.0.0.0/0
- ✅ Attach the Internet Gateway (IG)
- ✅ Go to the Route Tables and edit the subnet associations to the route tables and save the associations
- ✅ Once the connections are made Go to the EC2 Dashboard and select Instances in the resources and Launch an Instance
- ✅ Name the Instance and and choose an application i.e. Amazon Linux AWS. (Use Free Tier for AMI & Instance type)
- ✅ Create a new key Pair for login and name the key pair (you can use same key for multiple Instances)
- ✅ Select key pair RSA for ssh and .pem for Private key file format (Allow SSH traffic from anywhere for this lesson)
- ✅ In Network Settings select the correct VPC & the associated Subnet.
- ✅ Under the Inbound security group rules the type should be ssh with protocol TCP with port range 22
- ✅ To launch the instance now that it is connected, select the instance and connect
- ✅ Under connect to Instance choose ssh
- ✅ Open an SSH client, Locate your private key file. The key used is a .pem file
- ✅ Run this command, if necessary, to ensure your key is not publicly viewable. chmod 400 + the .pem key file name
- ✅ then Connect to your instance using its Private IP
- [x] Figure how to ping from one server to another
- [x] Write a Blog Post on Hashnode about the experience.

[My version of the code found Below](https://github.com/BenjaminBurton/AWS-VPC-Setup/blob/main/README.md)

```js
(https://github.com/BenjaminBurton/AWS-VPC-Setup/blob/main/README.md)

```

## AWS Account

- ✅ Create AWS Account

## GitHub Repo

- ✅ Create Github Repo An connect to laptop (git init)

## AWS Account

- ✅

## Database

- ✅

## Infrastructure As Code (IaC)

- ❌

## Source Control

- ❌

## Blog Post

- ❌ Write about experience in Blog post on HashNode

## Issues Encountered

- ❌ Actively Finding resolution to Issue with pinging back and forth
