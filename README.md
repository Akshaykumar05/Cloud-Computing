# About
This repo contain all about Cloud Computing and I tried to document my learnings of "Cloud computing with AWS" training which I did with Inernshala. First I will cover some theory part and at last I will make a project using AWS VPCs, EC2, RDS and database. Here is my [certificate](https://trainings.internshala.com/s/v/2915835/150696ef) of this training.

## Cloud Engineer
For becoming a Cloud Engineer, one should have the knowledge of following
1. Linux
2. Networking
3. Programming language: Python/Golang
4. Cloud service: AWS/Azure/GCP
5. Docker
6. IaaC
7. CI/CD
5. Database

## Roles in Cloud domain
* Cloud Support Technician
* Cloud Trouble shooter
* Cloud Engineer
* Cloud Solution Architect


## Project:- 
* Deploy a Highly Availabile Wordpress Application
* Host a static website on AWS and CICD pipeline 

### Pre-requisites:
1. An AWS account with privileges to create IAM roles, AWS VPCs, EC2 instances, and RDS 
databases.
2. The next is Access to the AWS console with Administrator permission.
* I will made this project in the end after covering cloud computing and AWS basics.

# Cloud-Computing
![image](https://user-images.githubusercontent.com/114390890/230864927-fb4f1d6d-142b-4c0b-b62a-30fc57446c6f.png)

## What is Cloud Computing?
* Cloud Computing is an **on-demand delivery** of compute, storage, database, networking, and many more services over the internet.
* On-demand delivery means **you get it** when you need it.
* It comes with **pay-as-you-go** pricing.

## What are the different cloud computing services?
* Compute
* Storage
* Database
* Networking

### Compute
* Compute is the processing power of a machine.

### Storage
* Storage enables you to **save data** within a data storage services.
* You can store data such as a video, music, documents, pictures etc.
* Data saved on a storage device will remain **permanently** untill you delete it
* To store data either temporarily or permanently on the cloud, you can use **cloud storage**.

### Database
* When you arrange your data or information in certain rows and columns, it is called **structured data**
* To store a huge amount of data, you need a special type of storage device called databases.
* MySQL, Oracle, and SQL Server.
* To store structured data in cloud, you use a **database**

### Networking
* It is a service that provide **connectivity** among different services.

## Cloud Deployment Models
### Why do we need Cloud Deployment Models?
* Different organisations have different requirements, they want different levels of control on their cloud infrastructure.
* Each cloud deployment model offers a different of **management, security**, and **cost**.

### 3 Types of Cloud Deployment Models
![](https://kinsta.com/wp-content/uploads/2020/04/cloud-deployment-models.png)
#### 1.Public Cloud
* A public cloud is cloud computing infrastructure maintained and operated by a **cloud service provider**
* **Anyone** can use the public cloud.
* The cloud service providers are responsible for maintaining the physical infrastructure.

#### 2.Private Cloud
* A private cloud is a cloud computing infrastructure that is **specially provisioned** for a comapany.
* Cloud service are available to an **organisation** and its **users** only.
* The physical infrastructure can be maintained either **by the organisation** itself or **by third party** who is providing the cloud services.
* When a cloud computing infrastructure is available for a certain organistaion and to their internal people only, this is called Private Cloud.
* Private clouds are **more expensive** than public clouds.
* Private clouds are used by organisations that want to run their mission-critical applications due to **security reasons**.

#### 3. Hybrid Cloud
* Hybrid means the **combination of two or more**.
* A hybrid cloud is a cloud computing infrastructure that benefits from both **public** and **private** models and enables organizations to use both.
* Hybrid cloud combine a public cloud and private cloud to allow a data and applications to be shared betwen them.


## Key Concepts of Cloud
1. Scalability (vertical and Horizontal scaling)
2. Elasticity
3. Agility
4. High Availability
5. Fault Tolerance 

**Scalability**
* Scalability is the ability of system to scale, in this case scaling is the process of increasing or decreasing the compute power.

**Elasticity**
* If the system can scale automatically, it is known as**Automatic Scaling**.
* Elasticity is the ability of the system to scale dynamically.

**Agility**
* The ability of system to **react quickly**

**High Availability**
* It is the ability of a system to **operate continuously without failure** for a designated period.

**Fault Tolerance**
* Tolerance means the ability of a virtual machine to **remain up** and service failures.
* A fault-tolerance system takes care of any failure, repairs it, and keeps the application running.
* Fault tolerance refers to the ability of a system (computer, network, storage etc) to **continue operating without interruption** whwn one or more of its componets fail.

## Benefits of Cloud Computing
### Trade fixed expense for variable expense
**CAPEX**
* The upfront investment in acquiring the physical space, hardware,and staff to set up a data centre is called CAPEX, capital expense or fixed expense.

**OPEX**
* The upfront investment in a technical team to keep the data centre running is known as OPEX, Operational expense pr variable expense

![image](https://user-images.githubusercontent.com/114390890/230884709-c0d03cea-52b9-48b3-b9de-3272b9782f52.png)


#### Benefits 
1. Trade fixed expense for variable expense
* It does not matter whether you use the full capacity  of the data centre or not, you have already invested the CAPEX amount and will have an ongoing OPEX.
* With cloud computing, you only have to **pay monthly** based on the resources you consume.  
2. Benefits from massive economies of scale.
3. Stop guessing capacity.
4. Increased speed and agility
5. Stop spending money running and maintaining data centres.
6. Go global in minutes.
Benefits [Details](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html)

### Different Cloud Providers
#### History of Cloud Providers
* 2002: Amazon- Amazon Web Services- for itself
* 2006: Amazon- Amazon Web Services- for general purpose (first time cloud came in general public)
* 2009: Google, Microsoft Azure, Oracle & HP

## How to open AWS free account
* For that user need:
1. Unique gmail id
2. Debit/Credit card
3. Contact number

* Purpose- To get hands-on experience before using actual services of cloud

### What is AWS Free tier?
The Free Tier lets you try certain AWS services for a definite period without paying anything. 

### What is multifactor Authentication (MFA)?
Multi-Factor Authentication is an **aunthentication method** that requires any user to provide at least **two verification types** (known as factors) to get access to an account, resource, or service.
* It is an authentication method to **validate** the user's identity.
* The user needs to provide two or more pieces of evidence of their identity to gain access.

#### AWS Access & Secret Key
Other than AWS Management Console, CLI and SDK are the two more methods to access AWS.

#### What are the different methods to interect with AWS.
* AWS Management Console
* AWS CLI (Command Line Interface)
* AWS SDK (Software Development Kit)

#### Advantage of AWS Management Console
* Excellent for beginners
* Easy to interact with AWS services.
* Provides a step-by-step user interface.
* Great for performing administrative tasks.

#### AWS CLI
* The AWS Command Line Interface (CLI) is a unified tool to manage your AWS servises.

#### Advantage AWS CLI
* It is a great way to interact with AWS through a computer terminal.
* Easy to automate tasks and achieve **Infrastructure as a Code**

#### AWS SDK
* Its stands for **software development kit** or **devkit** in short.
* It is a set of software tools and programs used by developers to create application.
* It supports: C++, Go, Java, Javascript, NET, Node.js, PHP, Python and Ruby language.

#### Advantage of SDK
* It provides a way to interact with AWS through the **application code**

### AWS Management Console

### Using the AWS CLI

## AWS Region
* An AWS region is nothing but the geographic locations worldwide where different Data Centres are clustered.
* Each data centre should have redundant electricity, cooling, heating, networking, and connectivity.
* All these regions are connected through the AWS backbone network.
* Some examples: 
1. Mumbai: ap-south-1
2. Singapore: ap-southeast-1
3. Sidney: ap-southeast-2
4. Cape Town:af-south-1

* Currently AWS has 26 regions and 84 Availability zones. (check new update)
![image](https://user-images.githubusercontent.com/114390890/230857764-c8118f39-ab81-4cac-bf84-724a54946315.png)


## Availability Zones
* An Availability Zone (AZ) is one or more individually separate and distict data centers with redundant power, power, networking, and connectivity in an AWS region.
* An Availability zone is a group of data centres.
* An AWS region must have two Availability Zones (AZs).

### Why availability zones are important?
* Region consists of multiple availability zones.
* Availabilty zones are located somewhere between 50 to 100 km apart.

![image](https://user-images.githubusercontent.com/114390890/230860638-ddbf9f20-5657-424c-918e-43f01dfba3fa.png)

### Why do we need so many regions today?
* Latency
* Compliance
* Disaster recovery
* Global applications
* Cost
* Reduced blast radius

#### Caching
* Catching is the process of storing a copy of data in a temporary or cache storage location so it can be accessed more quickly.

#### Content Delivery Network (CDN)
* Catching a copy of data in a data centre closer to customers.
* A Content Delivery Network or CDN, **caches content in proxy servers** that are located closer to end-users than origin servers.

#### What is the difference between Region & Edge Locations
* Edge locations are smaller data centres that are available across all big cities in the world.
* Edge locations are located at other locations from Regions.
* AWS Edge Location hosts a special service to deliver the content faster is called **Amazon CloudFront**

### AWS global infrastructure
* Regions are geographically **isolated location**, where you can access AWS services requires to run your application.
* Regions contain Availability zones that are **physically separated buildings** with their  own power, heating, cooling, and network.
* AWS Edge locations run **Amazon CloudFront** to bring the content closer to your customers, no matter where they are in the world. 

### What is Identity & Access Management?
![](https://k21academy.com/wp-content/uploads/2020/08/AWSIAM_BlogImage.png)
* Identity And Access Management is a **framework** to ensure  that the **right person** in your organisation can access the **right service or resources** as per their job.

#### AWS Identity & Access Management

* Identity and Access Management or IAM is a service in AWS that makes sure that the right person has access to the right service or resources.
* IAM provides you the access control of all the AWS servises and resources.
* IAM is an AWS servise that helps an organization to **manage access** of their AWS account and Services for their **organisational people**
* It provides **Fine-grained** access control across all the AWS services.

| Identification                                    | Authentification                                           | Authoriztion                                       |
| :------------------------------------------------ | :--------------------------------------------------------- | :--------------------------------------------------
| Identifiaction is the ability to identify a unique user | Authentification is the process of recognizing a user's identity | Authorization is the process of giving someone the permission to access something.

### IAM User
* A new IAM user doesn't have any default permission to access your AWS resources.
* IAM policy defines the permissions that are given yo any user accessing an AWS account.
* IAM user doesn't have to be an actual persion.

### IAM Group
* An IAM group is a collection of users and permissions assigned to those users.

### IAM Role
* An IAM role is like an IAM user attached with an IAM policy that determines what a Role can and cannot do in AWS.
 
| Identity-based Policy                                                       | Resource-based Policy                                       
| :-------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------
| * Identity-based policies are **attached to an identity** that are IAM user, group, and role. | * These policies are **attached to an AWS resource** such as an Amazon EC2 Instance, S3 bucket, etc.
| These policies control the **actions an Identity can perform**, on which resources, and under what conditions. | These policies control what **actions aspecified AWS Service or Identity can perform** on other resources and under what conditions.

| AWS Managed Policy                                                          | Customer Managed Policy                                       
| :-------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------
| Managed policies are policies that are **created and managed by AWS**. | Customer-managed policies are **creted and managed by the customers**. As a customer, you can create and manage these policies.
| AWS-managed policies cannot be cganged, and AWS will manage and update the policies, as necessary. | You can attach these policies to multiple entities within your account, making it much easier to scale.

#### Inline Policies
* Inline Policies are directly attached to the user or group. They maintain a strict one-to-one relationship with the Policy and Identity.
* Give permission to temporary User or Group.

## Core AWS Services
1. Storage
2. Compute
3. Database
4. Networking 

### Overview of Amazon S3
#### What is Amazon S3
* S3 Stands for **Simple Storage Service**.
* It allows you to **store, retrieve, access, and back up** any amount of data at any time from anywhere over the internet.
* We can access S3 from AWS Management Console, AWS CLI, and AWS SDK.

![image](https://user-images.githubusercontent.com/114390890/230877137-569a76ea-c82a-49f9-8008-81cc8716d132.png)

#### S3 Bucket Folder
* Folders are used to group and organise files.
* S3 doesn't use hierarchy to organize files.

#### S3 Object
* Object can be your file, document, image, video etc
* The maximum object size that you can upload to S3 is 5 terabytes.
* S3 object versioning: keeping multiple variants of a single object.
* S3 storage class.

### S3 Availability, Durability and Data Reolication
#### Availability
* It refers to the system uptime.
* How long the system is operational and able to deliver data upon request.

#### Durability
* It refers to **long-term data protection**.
* Data should not be lost or corrupted in the long run.

#### S3 Data Replication
* S3 is designed to provide 99.99999999% durability and 99.99% availabilty of your objects over a given year.

### Storage Classess
#### S3 Standard 
* It is a general-purpose storage class used for **frequently accessed** data.
* It offers **high durability, availabilty, and performance**.
* S3 standard is designed for 99.99% availability and 99.99999999% durability.
* It gives you low latency and high throughout.

#### S3 Standard use case
* Cloud application
* Dynamic websites
* Content distribution
* Mobile & gaming application
* Big data analytics

#### S3 Standard Infrequent Access
* This is a **low-cost** and **high-perforamnce** storage class, ideal for long term storage, backups, and disaster recovery.
* Our data is also **resilient against** any events of an entire availability zone failure.

#### One Zone-Infrequent Access (S3 One Zone-AI)
* Data is stored in a **single availability**
* We still have **low latency** and **high throughout** performance.
* As the data is stored in one availability zone, it is **20% cheaper** than Infrequent Access.

#### Amazon S3 Intelligent-Tiering (S3 Intelligent-Tiering)

#### Glacier
* Amazon S3 Glacier is the **cheapest** storage class in S3 and supports **long-term** retention and digital preservation for data accessed only once or twice per year.
* It is helpful for customers, particularly those in **highly-regulated** industries.
* It is designed for 11 nine (99.999999999%) durability of objects across multiple Availability Zones.

## Virtual Private Cloud (VPC)
* It is a virtual network dedicated to your AWS account. It is logically isolated from other virtual network in the AWS Cloud in which you can launch your AWS resources, such as AWS EC2 instance.

![image](https://user-images.githubusercontent.com/114390890/230878068-1380252e-9b50-49e8-b4fb-912a6e3c7f16.png)

### Subnet
| Public Subnet                                                               | Private Subnet                                       
| :-------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------
| It is a Subnet that **interacts** with the **internet** and **can be accessed** through the internet. | It is a subnet that **can not** be reached from the **internet**.
| We will deploy our **load balancer** or **internet-facing** applications in the Public Subnet. | We can creates the AWS resources which **are only used Inside** the VPC for internal purposes.

### Internet Gateway
* It is an AWS-managed component that is **attached** to your VPC.
* It acts **as a gateway** between your VPC and the internet, basically the outside world.

## Security Groups & NACL
### Why do we need Security Groups & NACL
* Security groups and NACLs both act as **virtual firewalls**.
* It controls traffic to and from resources in a VPC with **inbound** and **outbound** rules.

### What is Inbound & Outbound?
* Inbound or Outbound is the **direction of traffic** between **networks, relative** to the **reference network**.
* **Inbound** traffic refers to information coming-in to a network.
* **Outbound** traffic refers to information going-out of the network.

### What is Security Group?
* A Security group is an **AWS firewall solution** that performs one primary function: to **filter incoming** and **outgoing** traffic from an EC2 instance.
* It represents instance-level security.
* Both inbound and outbound rules work independently.
* We can apply a security group to**one** or **two** instances. Similarly, an instance can also be **associated** with one or more security groups.

### NACL
* It stands for **Network Access Control List** which **controls the traffic** to or form a **subnet** according to the defined rules.
* NACLs work at the subnet level of a VPC.
* WE can apply a NACL to one or more subnets. However, each subnet must be associated with one and only one NACL.

| Security Group                                                              | NACL                                      
| :-------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------
| Operates at the instance level | Operates at the subnet level
| Supports allow rules only | Supports allow rules and deny rules
| Is stateful | Is stateless
| Can't delete a default security group | Can't delete default NACL

## Elastic Compute Cloud (EC2)

![image](https://user-images.githubusercontent.com/114390890/230882646-0f99c15e-5f3b-4939-a8e2-13f25e8535e8.png)

### What is AWS Compute?
* AWS compute is an **on-demand computing service** for running cloud-based applications.
* A cloud-based application means an application that can be deployed on a remote server and accessed over the internet.
* AWS provides computing resources like **instances** (Virtual Machines) and **containers**.
* AWS also provides **serverless computing** to run applications where you do not require infrastructure setup or configuration.
* AWS Compute resources are available **on-demand** and can be created with just a few clicks of a mouse.
* You will only **pay for the resources you use** and only for as long as you are using them.

### AWS Compute Services: (3 types)
1. Instance (virtual machines)
2. Container
3. Serverless Computing

### What is Virtual Machine?
* A virtual machine is a **virtual environment** that works like a computer within a computer.
* The virtual machine is commonly known as **VM**
* It has a **CPU, memory, disks** to store your files and a **network** to connect to the internet.

### Virtual Machine benefits
* Cost saving
* Agility and speed
* Lowered downtime
* Scalability

### EC2
* EC2 stands for Elastic Compute Cloud.
* Amazon Elastic Compute Cloud (Amazon EC2) provides **scalable computing capacity** in the Amazon Web Services (AWS) Cloud.
* You can completely **avoid setting up the hardware** to run your application and can develop and deploy applications fatter.
* It is designed to make web-scale cloud computing **easier for developers**.
* You can use Amazon EC2 to launch **as many** or **as few** virtual machines as you need.
* Amazon EC2 enables you to **scale up** or **down** the virtual machines to handle unexpected loads.
* It provides you with **complete control** of your computing resources and lets you run on Amazon's proven computing environment.
* It supports macOS.

## Components of Amazon EC2

![image](https://user-images.githubusercontent.com/114390890/229060556-c5d49b6f-a109-4e2f-9132-d7ebbf342f33.png)

### Instance
* Amazon EC2 is a **virtual machine** in AWS
* Instance is an **EC2 virtual Machine**

### AMI
* AMI stands for **Amazon Machine Image**
* An Amazon Machine Image (AMI) template contains an **operating system** and **additional software** needed to launch AWS EC2 instances.

### Key Pair
* A key pair consistes of a **public key** and a **private key**. It is a set of security credentials that you use to prove your identity when connecting to an Amazon EC2 instance.

### Security Group
* Security Groups lets you control **who can access your EC2 instances**.
* A security group as a **virtual firewall** for your EC2 instances to **control inbound** and **outbound** traffic.
* Inbound means you can configure who can connect to your EC2 instance from outside, and Outbound means what EC2 instance can connect with.

### EC2 Tags
* A tag is a **label** of your **AWS resources**.
* Each tag consists of a **key** and a **value**.
* You can use tags to organize the resources in your account.
* It could be environment, cost centre, owners, and each resources, and each tag key can have **only one value**.

### EC2 Instance Naming Conventiom
* For example: **M6g.2xLarge**
* this is made up of 4 component.
1. Instance Family e.i. M
2. Instance Generation e.i. 6
3. Additional Capacity e.i. g
4. Instance size e.i. 2xLarge
 
### What is an EC2 instance type?
* It is a combination of **CPU, memory, storage** & **networking** capacity.
* Different combinations help while choosing the appropriate mix for your aoolications.

### What best fit for your application means?
Amazon EC2 instance types are grouped into families to meet different use cases.
* General-purpose Instance
* Compute-optimized Instance
* Memory-optimized Instance
* Storage-optimized Instance

1. **General-purposr Instance**
* It provide a balance of **compute, memory, & networking** resources.
* It is best suitable for **web servers, catching fleets,& distributed data store** applications.
* It is a;so suitable for **development, test & demo** environment applications.

2. **Compute-optimized Instance**
* It is ideal for **compute-bound** applications that benefit from **high performance processors**
* This is the best for the applications that need **higher compute power**.
* It is well suited for batch processing, media transcoding, high-performance web servers, high performance computing(HPC), scientific modeling, dedicated gaming servers, ad server engines, machine learning interference, and other computing-intensive applications.

3. **Memory-optimized Instance**
* Memory-optimized Instances are desighned to deliver fast performance for workload that require **huge memory to process large data sets**.
* These are used in applications such as **open-source databases, in memory catches,& real-time big data analytics.

4. **Storage-optimized Instance**
* Storage-optimized Instance aredesigned for workloads that require high, **sequential read & write access** to massive data sets on local storage.
* It is optimized to deliver tens of thousands of **low-latency, random input-output (I/P)** operations per second (IOPS) to applications.
* The application has medium-size data sets that need **high compute performance** and **high network thoughout**.
* These include relational database including MySQL, MariaDB, and PostgeSQL, and NoSQL databases including keyDB, ScyllaDB, and Cassandra.


## Launch Congiguration & Launch Template
### Introduction
* The launch configuration and launch template defines the charecterstics of EC2 instances.
* AWS introduced launch configuration in 2014.
* Launch template has extra features and capabilities.

### Launch Configuration
* It is the instance configuration template in which we defines configurations of our EC2 instance.
* It consists of AMI, Instance type, Security group, Block device, Key pair, User data and IAM role.
* Launch configuration are not editable.

### Launch Configuration
* It is similar to launch configuraion.
* Launch teplates can also be used to launch EC2 instances or Fleet of the EC2 instances directly from AWS Management console or AWS CLI (Command Line Tool).
* You can create multiple version of launch templates.
* We can specify multiple instance types.
* It has the capability to use both on-demand and spot instances.
* It also covers T2/T3 unlimited features.
* It support other features like Placement groups, Capacity reservation, elastic graphics, dedicated host, Volume tagging and Elastic interface.

## Elastic Load Balancer (ELB)
* This is an AWS load balancer service.
* It is designed to address the undifferntiated heavy lifting of load balancing.
* The ELB **routes incoming** application traffic across instance **automatically**.

![image](https://user-images.githubusercontent.com/114390890/230879751-f0fe480a-1eb1-4f57-81dc-54ab26de5511.png)

## 8. Database

### Elastic Block Storage (EBS)
* Amazon EBS provides **persistent block storage** for Amazon EC2 instances.
* Block storage is the technology that **chops data into blocks** and store them in a separate piece.
* EBS volume is **network-attached drive**.
  
### Private IP Address Vs Public IP Adress
* A private IP address, such as a home or office network, is assigned to a device on a local network and is used to identify the device within that network.
* On the other hand, a public IP address is assigned to a device directly connected to the internet and is used to identify the device on the internet.

## AWS Security and Manaegement

## AWS Billing and Pricing

## Final Project- Deploy a Highly Available WordPress Application

