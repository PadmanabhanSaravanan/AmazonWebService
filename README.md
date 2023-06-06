# AmazonWebService

![image aws](image/aws-logo.png)

## **TABLE OF CONTENT** 

* [**INTRODUCTION**](#introduction)<!-- style="font-size:20px" -->
* [**SECURITY**](#security) <!-- style="font-size:20px" -->
* [**COMPUTE I**](#tagging-importance) <!-- style="font-size:20px" -->
* **COMPUTE II**<!-- style="font-size:20px" -->
* **STORAGE AND DELIVERY**<!-- style="font-size:20px" -->
* **NETWORKING**<!-- style="font-size:20px" -->

## **INTRODUCTION** 

* AWS stands for Amazon Web Services.
* The AWS service is provided by the Amazon that uses distributed IT infrastructure to provide different IT resources available on demand. It provides different services such as infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS).
* Amazon launched AWS, a cloud computing platform to allow the different organizations to take advantage of reliable IT infrastructure.

[**What is Cloud Computing**](#what-is-cloud-computing)

[**Introduction to AWS**](#introduction-to-aws)

[**AWS Global Infrastructure**](#aws-global-infrastructure)

[**Create an AWS Account**](#create-an-aws-account)

### **What is Cloud Computing**

Cloud computing is a model for delivering computing resources, including servers, storage, applications, and services over the internet. It enables users to access a pool of shared computing resources, rather than owning and maintaining their own infrastructure.

Cloud computing can be categorized into three main types of services: 

1. Infrastructure as a Service (IaaS): provides virtualized computing resources, such as servers, storage, and networking, on a pay-per-use basis. 

2. Platform as a Service (PaaS): offers a complete development and deployment environment for applications, including tools, libraries, and frameworks. 

3. Software as a Service (SaaS): delivers applications over the internet on a subscription basis, eliminating the need to install and maintain software locally.

Cloud computing offers several benefits, including scalability, flexibility, cost savings, and ease of use. It allows organizations to quickly provision and deprovision resources, scale up or down based on demand, and pay only for what they use.

### **Introduction to AWS**

Amazon Web Services (AWS) is a comprehensive cloud computing platform provided by Amazon that offers a wide range of services and tools for building and deploying scalable and reliable applications. AWS provides a vast collection of cloud-based services that include computing, storage, databases, analytics, machine learning, and much more.

AWS provides a pay-as-you-go model, where customers are charged based on their usage of each service. The platform is designed to provide scalable, reliable, and secure infrastructure, enabling businesses to quickly and easily deploy their applications and services on a global scale.

AWS offers several benefits, including:

**Scalability**: AWS can automatically scale resources up or down based on application demand, enabling businesses to easily accommodate sudden spikes in traffic or usage.

**Reliability**: AWS provides multiple availability zones and redundancy options, ensuring high availability and uptime for applications and services.

**Security**: AWS offers a comprehensive set of security tools and features, including encryption, identity and access management, and network security, ensuring the safety of data and applications.

**Flexibility**: AWS offers a vast array of services and tools, allowing businesses to choose the ones that best meet their needs and easily integrate with their existing systems.

Overall, AWS is a powerful cloud computing platform that provides businesses with the tools and services they need to build, deploy, and manage their applications and services on a global scale.

### **AWS Global Infrastructure**

* AWS is a cloud computing platform which is globally available.
* Global infrastructure is a region around the world in which AWS is based. Global infrastructure is a bunch of high-level IT services which is shown below:
* AWS is available in 19 regions, and 57 availability zones in December 2018 and 5 more regions 15 more availability zones for 2019.

The following are the components that make up the AWS infrastructure:

* [**Availability Zones**](#availability-zone-as-a-data-center)
* [**Region**](#region)
* [**Edge locations**](#edge-locations)
* [**Regional Edge Caches**](#regional-edge-cache)

![image aws](image/aws-global-infrastructure.png)

#### **Availability zone as a Data Center**

* An availability zone is a facility that can be somewhere in a country or in a city. Inside this facility, i.e., Data Centre, we can have multiple servers, switches, load balancing, firewalls. The things which interact with the cloud sits inside the data centers.
* An availability zone can be a several data centers, but if they are close together, they are counted as 1 availability zone.

#### **Region**

* A region is a geographical area. Each region consists of 2 more availability zones.
* A region is a collection of data centers which are completely isolated from other regions.
* A region consists of more than two availability zones connected to each other through links.

![image aws](image/aws-global-infrastructure2.png)

* Availability zones are connected through redundant and isolated metro fibers.

#### **Edge Locations**

* Edge locations are the endpoints for AWS used for caching content.
* Edge locations consist of CloudFront, Amazon's Content Delivery Network (CDN).
* Edge locations are more than regions. Currently, there are over 150 edge locations.
* Edge location is not a region but a small location that AWS have. It is used for caching the content.
* Edge locations are mainly located in most of the major cities to distribute the content to end users with reduced latency.
* For example, some user accesses your website from Singapore; then this request would be redirected to the edge location closest to Singapore where cached data can be read.

#### **Regional Edge Cache**

* AWS announced a new type of edge location in November 2016, known as a Regional Edge Cache.
* Regional Edge cache lies between CloudFront Origin servers and the edge locations.
* A regional edge cache has a large cache than an individual edge location.
* Data is removed from the cache at the edge location while the data is retained at the Regional Edge Caches.
* When the user requests the data, then data is no longer available at the edge location. Therefore, the edge location retrieves the cached data from the Regional edge cache instead of the Origin servers that have high latency.

### **Create an AWS Account**

1. First Open your web browser and navigate to [AWS Free Tier Page](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all)

2. On middle click of Create a Free Account

![image aws](image/aws-account.png)

3.  Issue the details which you want to use to log in to your AWS account and click on Continue

* Email address: Provide the mail id which hasn’t been registered yet with Amazon AWS.
* Password: Type your password.
* Confirm password: Authenticate the password.
* AWS Account name: Choose a name for your account. You can change this name in your account settings after you sign up.

![image aws](image/aws-account2.png)

4.  Contact Information

Select your AWS type (Profesional/ Personal) Fill in the correct information to validate your account if you’re going to create personal use then click on “Personal Account” else use “Company Account”, Accepts the Terms and condition and then click on Create Account and Continue

![image aws](image/aws-account3.png)

**Note**: Make sure to provide proper contact details and mobile number to get the Verification code from AWS.

5. Payment and PAN information: In this step, you must fill in your credit card /Debit Card info and billing address and click on Secure Submit.

![image aws](image/aws-account4.png)

6.  In this step, it will take you to the payment gateway to validate your payment information and for your credit card verification, Amazon will charge the minimum price based on Country. Here I have provided India, so Amazon charged 2 INR.

![image aws](image/aws-account5.png)

7. Phone verification: Here you will be taken to an identity verification page that will already have your phone number, so you just have to select either “Text message or Voice call” Provide a valid phone number, Solve the captcha, and then click on Send SMS or Call Me Now(depending upon your selection).

![image aws](image/aws-account6.png)

8. After clicking on Send SMS or Call me Now, you will immediately receive a call or SMS from Amazon, for verification code, Enter your code then click on Verify Code.

![image aws](image/aws-account7.png)

9. Support plan: AWS support offers a selection of plans to meet your business needs.
Select your suitable plan then click continue.

![image aws](image/aws-account8.png)

10.  Registration Confirmation page.
Once you completed all the above steps and processes. You’ll get the confirmation page as below. Now your account will be processed for activation. It may take somewhere between 30 minutes to 1 hour for you to receive an email confirmation that your Amazon Cloud Services account has been activated.

![image aws](image/aws-account9.png)

## **SECURITY**

* [**Shared responsibility model**](#shared-responsibility-model)  <!-- style="font-size:18px" -->
* [**Security services overview**](#security-services-overview)  <!-- style="font-size:18px" -->
* [**Identity & Access Management (IAM)**](#identity-and-access-management) <!-- style="font-size:18px" -->
* [**MFA**](#mfa)  <!-- style="font-size:18px" -->
* [**Users, Groups and Roles**](#users-groups-and-roles)  <!-- style="font-size:18px" -->
* [**Permission management**](#permission-management)  <!-- style="font-size:18px" -->
* [**Password policy**](#password-policy)  <!-- style="font-size:18px" -->

### **Shared responsibility model**

The AWS shared responsibility model is a concept of dividing responsibilities between AWS and a Customer.

AWS's responsibilities are the security of the cloud.

Customer responsibilities are security in the cloud.

![image security](image/Shared_Responsibility_Model.jpg)

**Responsibility of AWS** <!-- style="font-size:18px" -->

AWS's responsibility is the security of the cloud.

AWS manages all infrastructure layers.

Some of the infrastructure layers are:

* Data centers
* Hardware and software
* Virtualization
* Networking

**Responsibility of a Customer** <!-- style="font-size:18px" -->

Customers' responsibility is the security of everything they make in AWS Cloud.

Customers (you) have complete control over your content.

Customer manages AWS services, software, and access to the data.

### **Security services overview**

AWS Security is responsible for protecting the global infrastructure that runs all the Amazon Web Services cloud services and the cloud itself. This infrastructure includes the hardware, software, and networks. Amazon Web Services has its priority in protecting this network.

**Benefits of Security Services** <!-- style="font-size:18px" -->

* **Keeps Data Safe**: Infrastructure incorporates strong safeguards to help protect privacy. All data is processed in highly protected data centers.
* **Meets Compliance Requirements**: Manages dozens of compliance programs in its infrastructure. Organizations meet compliance effortlessly
* **Saves Operational Cost**: Operational cost reduces as organizations don't have to maintain on-premise facilities. 
* **Scales Quickly**: Security scales with the organization's usage of Amazon Web Services Cloud. The architecture is built to keep data secure, no matter the size of the enterprise.

Here are some of the most commonly used security services in AWS:

* **IAM (Identity and Access Management)**: This service allows you to manage user access to AWS resources by creating and managing users, groups, and roles. IAM helps you control who can access your resources and what actions they can perform.

* **AWS WAF (Web Application Firewall)**: This service helps protect your web applications from common web exploits such as SQL injection and cross-site scripting (XSS) attacks. You can configure AWS WAF to block or allow traffic based on rules that you define.

* **AWS Shield**: This service provides DDoS (Distributed Denial of Service) protection for your applications running on AWS. AWS Shield helps you mitigate the impact of DDoS attacks by automatically detecting and blocking them.

* **AWS Key Management Service (KMS)**: This service allows you to create and manage encryption keys used to encrypt your data in AWS. You can use AWS KMS to encrypt data at rest and in transit, and to control access to your encryption keys.

* **Amazon GuardDuty**: This service is a threat detection service that continuously monitors your AWS environment for malicious activity. GuardDuty can detect activity such as compromised credentials, reconnaissance, and unauthorized access, and provides alerts for you to take action.

* **Amazon Inspector**: This service helps you assess the security and compliance of your applications and infrastructure on AWS. Inspector analyzes your applications and infrastructure against security best practices and industry standards, and provides a detailed report of findings.

### **Identity and Access Management**

IAM (Identity and Access Management) is a service offered by AWS that allows you to manage access to AWS resources. IAM provides a way to create and manage users, groups, and roles, and assign permissions to them to control access to AWS resources.

![image IAM](image/iam.png)

**Features of IAM** <!-- style="font-size:18px" -->

* **Centralized user management**: IAM provides a central location for managing users and their access to AWS resources. This makes it easy to add, remove, or modify user access across multiple AWS services.

* **Fine-grained access control**: IAM allows you to grant permissions at a granular level, specifying which actions a user can perform on specific resources. This gives you precise control over access to resources and helps minimize the risk of accidental or unauthorized access.

* **Multi-factor authentication (MFA)**: IAM supports MFA, which requires users to provide two forms of authentication (such as a password and a code sent to a mobile device) in order to access AWS resources. This helps prevent unauthorized access even if a user's password is compromised.

* **Role-based access control**: IAM allows you to create roles that define a set of permissions that can be assumed by trusted entities such as AWS services, applications, or users. Roles enable you to grant temporary permissions to an entity without requiring long-term access keys.

* **Audit trails**: IAM provides detailed logs that allow you to track who accessed which resources and when. This helps you monitor and detect any unauthorized access attempts or unusual activity.

* **Integration with other AWS services**: IAM integrates with other AWS services such as Amazon S3, EC2, and RDS, allowing you to control access to these resources using IAM policies.

### **MFA**

**MFA (Multi-Factor Authentication)** is a security feature that adds an extra layer of protection to your AWS account. With MFA, a user is required to provide two or more forms of authentication before being granted access to their AWS resources. This helps protect against unauthorized access even if a user's password is compromised.

There are several types of MFA supported by AWS, including:

* **Virtual MFA**: This type of MFA uses a smartphone app, such as Google Authenticator or Authy, to generate a unique, time-based code that is required in addition to the user's password to access an AWS resource.

* **Hardware MFA**: This type of MFA uses a physical device, such as a YubiKey, to generate a unique code that is required in addition to the user's password to access an AWS resource.

* **SMS MFA**: This type of MFA sends a unique code to the user's mobile phone via SMS that is required in addition to the user's password to access an AWS resource.

MFA is an important security feature that helps protect your AWS resources against unauthorized access. By requiring users to provide an additional form of authentication in addition to their password, MFA can help prevent attackers from gaining access to your account, even if they have obtained your password through phishing or other means. It is recommended that MFA is enabled for all users in your AWS account.

### **Users Groups and Roles**

In AWS Identity and Access Management (IAM), users, groups, and roles are three fundamental entities used to manage access to AWS resources.

* [**Users**](#users): An IAM user is an entity that represents a person or application that interacts with AWS resources. You can create IAM users and assign them unique security credentials such as access keys, passwords, or multi-factor authentication (MFA) devices. You can also grant permissions to users by attaching policies to them.

* [**Groups**](#groups): An IAM group is a collection of IAM users. You can use groups to organize users and apply permissions to multiple users at once. By assigning policies to a group, you can ensure that all members of the group have the same level of access to AWS resources.

* [**Roles**](#roles): An IAM role is an entity that defines a set of permissions that can be assumed by AWS resources. You can use roles to grant permissions to an AWS service or resource so that it can access other AWS resources. For example, you can create a role that allows an Amazon EC2 instance to access an Amazon S3 bucket.

Roles are also used for cross-account access, where you can define a role in one account and allow users or resources in another account to assume that role and access resources in the first account. This is a common scenario for organizations that use multiple AWS accounts to isolate and manage their resources.

Overall, users, groups, and roles are used to manage access to AWS resources and ensure that only authorized users and services can interact with them. By assigning appropriate permissions and following the principle of least privilege, you can minimize the risk of unauthorized access and protect the security of your AWS resources.

#### **Users**

To create an IAM user in AWS, you can follow these steps:

* Sign in to the AWS Management Console and open the IAM console.
* In the navigation pane, choose "Users".
* Choose "Add user".
* Enter a name for the new user in the "User name" field.
* If you want to allow programmatic access to the AWS API, select the "Programmatic access" checkbox. If you want to allow the user to sign in to the AWS Management Console, select the "AWS Management Console access" checkbox.
* Depending on whether you selected "Programmatic access" or "AWS Management Console access" (or both), you may need to specify additional options such as a password or permissions.
* If you want to add the user to a group, choose "Add user to group" and select an existing group or create a new one.
* Review the user's settings and choose "Create user".

![image users](image/iam-createuser.PNG)

Once the user is created, you can view their security credentials, including their access key and secret access key, which can be used for programmatic access to AWS resources. You can also assign permissions to the user by creating IAM policies and attaching them to the user or the group to which the user belongs.

Note that when creating an IAM user, it is important to follow the principle of least privilege, which means granting the user only the permissions that are necessary to perform their job duties and no more. This helps minimize the risk of accidental or malicious actions that could compromise the security of your AWS resources.

#### **Groups**

To create an IAM group in AWS, you can follow these steps:

* Sign in to the AWS Management Console and open the IAM console.
* In the navigation pane, choose "Groups".
* Choose "Create New Group".
* Enter a name for the group in the "Group Name" field.
* Choose the policy you want to attach to the group by selecting "Attach Policy" and then selecting a policy from the list. You can also create a custom policy by selecting "Create Policy".
* Choose "Create Group" to create the group and attach the policy.

![image groups](image/groups.PNG)

Once you have created the group, you can add IAM users to the group by selecting the group in the IAM console, choosing the "Users" tab, and then choosing "Add Users to Group". You can then select the users you want to add to the group and choose "Add Users".

You can also manage the policies attached to the group by selecting the group in the IAM console, choosing the "Permissions" tab, and then choosing "Attach Policy" or "Create Policy".

#### **Roles**

To create an IAM role in AWS, you can follow these steps:

* Sign in to the AWS Management Console and open the IAM console.
* In the navigation pane, choose "Roles".
* Choose "Create role".
* Select the type of trusted entity that you want to use to assume the role. You can choose from AWS service, another AWS account, or web identity provider.
* Depending on the trusted entity you selected, you may need to specify additional details such as the service or account ID.
* Choose the permissions you want to grant to the role by selecting one or more policies. You can choose from managed policies, customer managed policies, or inline policies.
* Enter a name for the role in the "Role name" field.
* Review the role's settings and choose "Create role".

![image roles](image/roles.PNG)

Once the role is created, you can assign it to an IAM user or an AWS resource such as an EC2 instance. When the user or resource assumes the role, they inherit the permissions granted to the role.

### **Permission management**

In AWS, permission management is the process of controlling who has access to your resources and what actions they can perform on those resources. AWS Identity and Access Management (IAM) is the service that provides the necessary tools for managing permissions in your AWS environment.

There are three main components to permission management in AWS:

* **Policies**: Policies are documents that define permissions for a specific resource or set of resources. They specify which actions are allowed or denied, and who has access to the resources. Policies can be attached to IAM users, groups, or roles.

* **Roles**: IAM roles are used to grant permissions to AWS resources or services. They can be assigned to EC2 instances, Lambda functions, or other resources, and provide access to other resources in your AWS account or other accounts.

* **Access control lists (ACLs)**: ACLs are used to manage permissions for S3 buckets and objects. They define which AWS accounts or users have permission to access the resources and what actions they can perform.

IAM provides several tools for managing permissions, including the ability to create custom policies, grant temporary permissions using IAM roles, and implement multi-factor authentication (MFA) for additional security. By using these tools and following best practices for permission management, you can help ensure the security and integrity of your AWS resources.

### **Password policy**

In AWS, password policies are used to enforce rules for creating and managing user passwords. Password policies help improve the security of your AWS environment by ensuring that user passwords are strong and regularly updated.

AWS Identity and Access Management (IAM) provides a default password policy that includes the following rules:

1. Passwords must be at least 8 characters long
2. Passwords must contain at least one uppercase letter, one lowercase letter, one number, and one non-alphanumeric character
3. Passwords cannot contain the user's username or any variation of their username
4. Users must change their passwords at least every 90 days
5. Users cannot reuse any of their previous passwords

![image password-policy](image/passwordpolicy1.PNG)

You can customize the default password policy by changing the values of the above rules or by adding additional rules. To customize the password policy, you can follow these steps:

1. Sign in to the AWS Management Console and open the IAM console.
2. In the navigation pane, choose "Account settings".
3. Scroll down to the "Password Policy" section and choose "Edit".
4. Update the password policy rules as needed.
5. Choose "Save changes" to apply the new policy.

![image password-policy](image/passwordpolicy2.PNG)

By setting and enforcing a strong password policy, you can help ensure the security of your AWS resources and prevent unauthorized access to your account. It is also important to educate your users on the importance of strong passwords and encourage them to use unique, complex passwords for their accounts.

## **COMPUTE I**

* [**Elastic Cloud Compute (EC2)**](#elastic-cloud-compute) <!-- style="font-size:18px" -->
* [**Types of VMs**](#types-of-vms) <!-- style="font-size:18px" -->
* [**Instance type pricing**](#instance-type-pricing) <!-- style="font-size:18px" -->
* [**Boot volume & EBS association**](#boot-volume-and-ebs-association) <!-- style="font-size:18px" -->
* [**Boot volume types**](#boot-volume-types) <!-- style="font-size:18px" -->
* [**Encryption options**](#encryption-options) <!-- style="font-size:18px" -->
* [**Tagging importance**](#tagging-importance) <!-- style="font-size:18px" -->
* [**Security Groups**](#security-groups) <!-- style="font-size:18px" -->
* **Status check types** <!-- style="font-size:18px" -->
* **Placement Groups** <!-- style="font-size:18px" -->
* **SSH and manage instance** <!-- style="font-size:18px" -->
* **Multi AZ EC2 setup** <!-- style="font-size:18px" -->
* **Load balancing (App & Network)** <!-- style="font-size:18px" -->
* **Health checks** <!-- style="font-size:18px" -->
* **Path based TG routing** <!-- style="font-size:18px" -->
* **Lambda TG (with intro to lambda)** <!-- style="font-size:18px" -->

### **Elastic Cloud Compute**

Amazon Elastic Compute Cloud (EC2) is a web service that provides resizable compute capacity in the cloud. It is one of the core services in Amazon Web Services (AWS) and enables users to easily provision and manage virtual machines (VMs), also known as instances, on the AWS cloud.

EC2 offers a variety of instance types, each with different CPU, memory, storage, and network capacity configurations to meet the needs of different workloads. Users can launch instances on-demand, reserve them for a fixed period of time, or use spot instances to bid on spare compute capacity and reduce costs.

Here are some of the key features of EC2:

* **Scalability**: EC2 enables users to quickly and easily scale compute capacity up or down to meet changing demand, without the need for upfront investments in hardware.

* **Flexibility**: EC2 offers a wide range of instance types, operating systems, and software configurations, giving users the flexibility to choose the configuration that best fits their needs.

* **Security**: EC2 provides several security features to help protect instances and data, including network firewalls, encryption, and security groups.

* **Integration**: EC2 integrates with other AWS services such as Amazon S3, Amazon RDS, and AWS Identity and Access Management (IAM), making it easy to build and deploy complex, multi-tier applications on the AWS cloud.

* **Monitoring**: EC2 provides detailed monitoring and logging capabilities to help users track and troubleshoot performance issues, security incidents, and other events.

### **Types of VMs**

Amazon Elastic Compute Cloud (EC2) offers a wide variety of virtual machine (VM) instance types to meet the needs of different workloads and use cases. Here are some of the most commonly used EC2 instance types:

![image instance](image/instancetypes.jpg)

* [**Micro Instances**](#micro-instances)
* [**General Purpose**](#general-purpose)
* [**Compute Optimized**](#compute-optimized)
* [**Memory Optimized**](#memory-optimized)
* [**Storage Optimized**](#storage-optimized)
* [**GPU Instances**](#gpu-instances)
* [**FPGA Instances**](#fpga-instances)

#### **Micro Instances**

The EC2 micro instance type is a type of general purpose instance that provides a low-cost option for running lightweight workloads and small applications. It is designed for low traffic websites, small development and test workloads, and other low intensity applications.

![image instance](image/microInstance.png)

#### **General Purpose**

General purpose instances are ideal for a wide range of workloads, including web servers, small databases, and development environments. They offer a balance of compute, memory, and network resources.

![image instance](image/generalPurpose.png)

#### **Compute Optimized**

Compute optimized instances are designed for CPU-intensive workloads, such as high-performance computing (HPC), media encoding, and gaming servers. They offer high CPU-to-memory ratios and fast network performance.

![image instance](image/computeOptimized.png)

#### **Memory Optimized**

Memory optimized instances are designed for memory-intensive workloads, such as large databases, in-memory analytics, and real-time big data processing. They offer high memory-to-CPU ratios and fast network performance.

![image instance](image/memoryOptimized.png)

#### **Storage Optimized**

Storage optimized instances are designed for storage-intensive workloads, such as NoSQL databases, data warehousing, and Elasticsearch. They offer high disk throughput and low latency, and are often used for applications that require large amounts of sequential read and write operations.

![image instance](image/storageOptimized.png)

#### **GPU Instances**

GPU instances are designed for workloads that require high-performance graphics processing, such as machine learning, video encoding, and gaming. They offer access to powerful NVIDIA GPUs and are optimized for high-performance computing.

![image instance](image/GPUInstances.png)

#### **FPGA Instances**

FPGA instances are designed for workloads that require custom hardware acceleration, such as genomics, financial modeling, and encryption. They offer access to field programmable gate arrays (FPGAs) that can be programmed to accelerate specific workloads.

![image instance](image/FGPAInstances.png)

### **Instance type pricing**

There are several pricing options available for EC2 instances:

* [**On-Demand Instances**](#on-demand-instances)
* [**Reserved Instances**](#reserved-instances)
* [**Scheduled Instances**](#scheduled-instances)
* [**Spot Instances**](#spot-instances)
* [**On Demand Capacity Reservations**](#on-demand-capacity-reservations)

#### **On Demand Instances**

![image instance](image/onDemand.PNG)

#### **Reserved Instances**

![image instance](image/reserved.PNG)

#### **Scheduled Instances**

![image instance](image/scheduled.PNG)

#### **Spot Instances**

![image instance](image/spot.PNG)

#### **On Demand Capacity Reservations**

![image instance](image/ondemadReservations.PNG)

### **Boot volume and EBS association**

When launching an Amazon EC2 instance, the boot volume refers to the primary storage device that contains the operating system and boot files for the instance. By default, the boot volume is an Amazon Elastic Block Store (EBS) volume.

Here are the key points about boot volumes and EBS association:

* Amazon EBS: Amazon Elastic Block Store (EBS) provides block-level storage volumes that can be attached to EC2 instances. EBS volumes are network-attached and can persist independently of the running instance.

* Boot Volume: The boot volume is the primary storage device from which the EC2 instance starts up and runs. It contains the operating system, applications, and data. The boot volume is typically an EBS volume but can also be an instance store volume for certain instance types.

* EBS-Backed Instances: Most EC2 instances are EBS-backed, which means they use an EBS volume as the boot volume. EBS-backed instances allow for data persistence even if the instance is stopped or terminated.

* EBS Volume Association: When launching an EC2 instance, you can specify the EBS volume to be used as the boot volume. You can either create a new EBS volume or select an existing one. The instance will be associated with the specified EBS volume as its boot volume.

* Elasticity and Management: By using EBS-backed instances, you can easily manage and scale your EC2 instances. You can take snapshots of EBS volumes for backups, resize volumes, and detach and reattach volumes to other instances.

* Instance Store Volumes: Some EC2 instance types offer instance store volumes as the boot volume. Instance store volumes are physically attached to the host computer and provide temporary block-level storage that is lost if the instance is stopped or terminated.

### **Boot volume types**

When launching an Amazon EC2 instance, you have different options for selecting the type of boot volume. The boot volume type determines the characteristics and performance of the storage device used as the primary storage for the instance's operating system and boot files. The available boot volume types include:

Amazon EBS (Elastic Block Store) Boot Volumes:

* General Purpose SSD (gp2): This is the default boot volume type for most EC2 instances. It offers a balance of price and performance, suitable for a wide range of workloads.
* Provisioned IOPS SSD (io2): This boot volume type is optimized for high-performance applications that require low-latency and consistent I/O performance. It offers configurable IOPS (Input/Output Operations Per Second) to meet specific application requirements.
* Throughput Optimized HDD (st1): This boot volume type is designed for frequently accessed, throughput-intensive workloads, such as big data processing or log processing.
* Cold HDD (sc1): This boot volume type is designed for less frequently accessed workloads, providing low-cost storage for large volumes of data.

Instance Store Boot Volumes:

Instance store volumes are temporary block-level storage that is physically attached to the host computer where the EC2 instance is running. The data stored on instance store volumes is lost if the instance is stopped or terminated. The performance characteristics and capacity of instance store volumes vary depending on the EC2 instance type.
It's important to note that the availability of boot volume types may vary depending on the EC2 instance type and region. You can choose the appropriate boot volume type based on your workload requirements for performance, durability, and cost.

### **Encryption options**

the encryption options available for data security in Amazon EC2:

* EBS Encryption: Amazon Elastic Block Store (EBS) provides the option to encrypt EBS volumes at rest. EBS encryption uses AWS Key Management Service (KMS) to manage the encryption keys. By enabling EBS encryption, data stored on the EBS volumes is automatically encrypted, providing protection against unauthorized access.

* S3 Server-Side Encryption: If your EC2 instances interact with Amazon S3 for storage, you can enable server-side encryption for S3 objects. This ensures that any data uploaded to S3 is encrypted at rest. S3 supports multiple server-side encryption options, including Amazon S3 Managed Keys (SSE-S3), AWS Key Management Service (SSE-KMS), and Server-Side Encryption with Customer-Provided Keys (SSE-C).

* RDS Encryption: If your EC2 instances utilize Amazon RDS for managing databases, you can enable encryption for RDS database instances. RDS provides the option to encrypt data at rest, ensuring the privacy and security of your database content. RDS encryption supports both AWS Key Management Service (KMS) and Oracle Wallet Manager for managing encryption keys.

* Transit Encryption: To protect data while it is in transit between EC2 instances and other services or clients, you can use encryption protocols such as SSL/TLS. Implementing SSL/TLS encryption secures network communications and prevents eavesdropping or tampering with data in transit.

* Client-Side Encryption: If you have sensitive data that needs to be encrypted before being sent to an EC2 instance, you can implement client-side encryption. This involves encrypting the data on the client side before it is transmitted to the EC2 instance. The encrypted data can then be securely stored or processed on the instance.

### **Tagging importance**

Tagging is an important practice in AWS, including EC2 instances, as it provides numerous benefits for organization, management, and cost allocation. Here are some reasons why tagging is important:

* Resource Organization: Tags allow you to categorize and group your EC2 instances based on different criteria, such as application, environment (development, testing, production), project, or department. This helps in organizing and locating resources efficiently, especially in large-scale deployments.

* Cost Allocation and Budgeting: By assigning tags to EC2 instances, you can track and allocate costs based on specific tags. This enables you to gain visibility into resource usage and allocate expenses accurately across teams, projects, or cost centers. Tags can also help in setting up budget alerts and monitoring costs at a granular level.

* Resource Management and Automation: Tags play a crucial role in resource management and automation. You can use tags to control and manage EC2 instances through AWS services like AWS Identity and Access Management (IAM), AWS Config, and AWS Systems Manager. For example, you can define IAM policies based on tags to grant or restrict access to specific instances.

* Operational and Security Compliance: Tags assist in managing operational and security compliance requirements. You can use tags to identify instances with specific security requirements, compliance standards, or patch levels. This helps in monitoring and enforcing security controls, managing vulnerability assessments, or tracking compliance status.

* Automation and Resource Lifecycle: Tags can be used to automate resource lifecycle management tasks. For instance, you can use tags to define lifecycle policies for EC2 instances, such as automatically stopping or terminating instances after a specific period of inactivity. Tags can also be utilized in resource scheduling and auto-scaling configurations.

* Monitoring and Troubleshooting: Tags can be used for filtering and grouping instances in monitoring and troubleshooting scenarios. For example, you can use tags to create specific Amazon CloudWatch dashboards, aggregate logs, or set up alarms based on tags to track performance or identify issues across specific subsets of instances.

### **Security Groups**

* A security group is a virtual firewall which is controlling the traffic to your EC2 instances.
* When you first launch an EC2 instance, you can associate it with one or more security groups.
* A Security group is the first defence against hackers.

**Some important points to remember:**

* All inbound traffic is blocked by Default, i.e., you need to add the traffic such as HTTP, HTTPs, etc.
* All outbound traffic is allowed automatically.
* You can have any number of EC2 instances within a security group.
* You can have multiple security groups attached to EC2 instance./li>
* Security groups are stateful, i.e., if you create an inbound rule allowing traffic in, that traffic is automatically allowed back out again.

![image security-group](image/security-group.png)