# Cloud-Computing

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
* Compute is the processing power of a macine

### Storage
* Storage enables you to **save data** within a data storage services.
* You can store data such as a video, music, documents, pictures etc.
* Data saved on a storage device will remain **permanently** untill you delete it
* To store data either temporarily or permanently on the cloud, you can use **cloud storage**.

### Database
* When you arrange your data or information in certain rows and columns, it is called **structured data**
* To store ahuge amount of data, you need a special type of storage device called databases.
* MySQL, Oracle, and SQL Server.
* To store structured data in cloud, you use a **database**

### Networking
* It is a service that provide **connectivity** among different services.

## Cloud Deployment Models
### Why do we need Cloud Deployment Models?
* Different organisations have different requirements, they want different levels of control on their cloud infrastructure.
* Each cloud deployment model offers a different of **management, security**, and **cost**.

### 3 Types of Cloud Deployment Models
#### 1.Public Cloud
* A public cloud is cloud computing infrastructure maintained and operated by a **cloud service provider**
* **Anyone** can use the public cloud.
* The cloud service providers are responsible for maintaining the physical infrastructure.

#### 2.Private Cloud
* A private cloud is a cloud computing infrastructure that is **specially provisioned** for a comapany.
* Cloud service are available to an **organisation** and its **users** only.
* The physical infrastructure can be maintained either **by the organisation** itself or **by third party** who is providing the cloud services.

#### 3.Private Cloud
* When a cloud computing infrastructure is available for a certain organistaion and to their internal people only, this is called Private Cloud.
* Private clouds are **more expensive** than public clouds.
* Private clouds are used by organisations that want to run their mission-critical applications due to **security reasons**.

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
#### History of Clloud Providers
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

## Availability Zones
* An Availability Zone (AZ) is one or more individually separate and distict data centers with redundant power, power, networking, and connectivity in an AWS region.
* An Availability zone is a group of data centres.
* An AWS region must have two Availability Zones (AZs).

### Why availability zones are important?
* Region consists of multiple availability zones.
* Availabilty zones are located somewhere between 50 to 100 km apart.

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

#### S3 Bucket Folder
* Folders are used to group and organise files.
* S3 doesn't use hierarchy to organize files.

#### S3 Object
* Object can be your file, document, image, video etc
* The maximum object size that you can upload to S3 is 5 terabytes.
* S3 object versioning: keeping multiple variants of a single object.
* S3 storage class.

