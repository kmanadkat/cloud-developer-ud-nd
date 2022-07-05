## Cloud Computing

Cloud Computing is the delivery of IT resources over the Internet. The cloud is like a virtual data center accessible via the Internet that allows you to manage:

- Storage services like databases
- Servers, compute power, networking
- Analytics, artificial intelligence, augmented reality
- Security services for data and applications



### Characteristics of Cloud Computing

**Pay as you go**
You pay only for what you use and only when your code runs.

**Autoscaling**
The number of active servers can grow or shrink based on demand.

**Serverless**
Allows you to write and deploy code without having to worry about the underlying infrastructure.



### Types of Cloud Computing

**Infrastructure-as-a-Service (IaaS)** 

- You rent infrastructure where you choose the amount of memory, CPU, disk size, OS, ...
- You setup the runtime environment will full choice from NodeJs, Redis or LAMP stack or any flavor you can think of.
- You are responsible for configuring the rented infrastructure for high availability and scaling out
- More freedom but more configuration (devops)
- Pay for what you allocate (You setup your machines and choose your infrastructure beforehand)
- examples: AWS, GCP, Azure, Digital Ocean

**Platform-as-a-Service (PaaS)**

- You don't care about the underlying hardware or OS.
- You only care about your code, the platform takes care of the rest
- Scaling is done for you
- You have to adhere to some restrictions imposed by the platform
- Pay for what you use (more traffick, storage used -> higher bill)
- examples: Heroku, Firebase, Godaddy

**Software-as-a-Service (SaaS)**

- A software application that runs over the Internet and is managed by the service provider.
- SaaS products are oriented towards non-technical end users.
- examples: Apple iCloud, Google Drive, Gmail, Google Docs



### Cloud Deployment Models

**Public Cloud**

- A public cloud makes resources available over the Internet to the general public.
- AWS is the largest Public Cloud provider

**Private Cloud**

- It is a propreitary network or an internal data centre that supplies services to a limited number of people.
- It is internal to a specific company

**Hybrid Cloud**

- A hybrid model contains a combination of both a public and a private cloud.

> *The hybrid model is a growing trend in the industry for those organizations that have been slow to adopt the cloud due to being in a heavily regulated industry or have compliance restrictions. The hybrid model gives organizations the flexibility to slowly migrate to the cloud.*



### Benefits

There are several benefits to the cloud.

- Stop guessing about capacity.
- Avoid huge capital investments up front.
- Pay for only what you use.
- Scale globally in minutes.
- Deliver faster.



### Cloud-Based Products

Amazon Web Services offers a broad set of global cloud-based products.

**Analytics**

- Quick Sight
- Athena
- Redshift

**Application integration**

- Simple Queue Service (SQS)

- Simple Notification Service (SNS)

**Cost management**

- AWS Budgets

**Compute services**

- Elastic Cloud Compute (EC2)
- Lambda
- Elastic Beanstalk

**Database management services**

- MySQL
- Oracle
- SQLServer
- DynamoDB
- MongoDB

**Developer tools**

- Cloud 9
- Code Pipeline

**Security services**

- Key Management Service (KMS)
- Shield
- Identity and Access Management (IAM)

**Additional Services**

- Blockchain
- Machine Learning
- Computer Vision
- Internet of Things (IoT)
- AR/VR



| Functionality          | AWS Service                       |
| ---------------------- | --------------------------------- |
| Notification           | Simple Notification Service (SNS) |
| Data Warehouse         | Redshift                          |
| Continuous Integration | Code Pipeline                     |
| Data Encryption        | Key Management Service            |
| Development Tool       | Cloud 9                           |



### Global Infrastructure

**Region**

A region is considered a geographic location or an area on a map.

**Availability Zone**

An availability zone is an isolated location within a geographic region and is a physical data center within a specific region.

**Edge Location**

An edge location is as a mini-data center used solely to cache large data files closer to a user's location.

**Additional Information**

- There are more Availability Zones (AZs) than there are Regions.
- There should be at least two AZs per Region.
- Each region is located in a separate geographic area.
- AZs are distinct locations that are engineered to be isolated from failures.



| Topic             | Definition/Feature  |
| ----------------- | ------------------- |
| Region            | Geographic Location |
| Edge Location     | Used to Cache Files |
| Availability Zone | Data Center         |



### Shared Responsibility Model

AWS is responsible for security **OF** the cloud, we are responsible for security **IN** the cloud.

**AWS is responsible for:**

- Securing edge locations
- Monitoring physical device security
- Providing physical access control to hardware/software
- Database patching
- Discarding physical storage devices

**You are responsible for:**

- Managing AWS Identity and Access Management (IAM)
- Encrypting data
- Preventing or detecting when an AWS account has been compromised
- Restricting access to AWS services to only those users who need it