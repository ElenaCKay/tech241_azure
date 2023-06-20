# Azure Introduction
## Why use python?
Python is a widely used programming language that offers several advantages for working with Azure. It has a rich ecosystem of libraries and frameworks that support various Azure services and functionalities. Python provides simplicity, readability, and ease of use, making it a popular choice among developers.

## What is an API?
An API (Application Programming Interface) is a set of rules and protocols that allows different software applications to communicate with each other. In the context of Azure, APIs enable developers to interact with Azure services and access their functionalities programmatically.

## What is Azure and the cloud?
Azure is a cloud computing platform provided by Microsoft. The cloud refers to a network of servers that are delivered as a service over the internet, allowing users to access and utilize various computing resources and services on-demand. Azure provides a wide range of services, including virtual machines, databases, storage, and more, enabling users to build, deploy, and manage applications and services in the cloud.

## Multiple data centres within multiple regions
Azure operates multiple data centers across various regions globally. This distributed infrastructure ensures redundancy and high availability. In the event of a natural disaster or other disruptions, the impact is minimized as only a subset of data centers might be affected. Azure's data centers are designed with robust infrastructure, including their own cooling, water supply, power, generators, and other resources necessary for uninterrupted service delivery. This resilience helps maintain service continuity and data integrity.

## Advantages of using the cloud
There are several advantages to using the cloud, including:

- Scalability: The cloud allows users to scale their resources up or down based on demand, ensuring optimal performance and cost-efficiency.
Disaster recovery: Cloud providers like Azure offer built-in backup and recovery mechanisms, reducing the risk of data loss and enabling rapid recovery in case of failures.
- Accessibility: Cloud services can be accessed from anywhere with an internet connection, facilitating remote work and collaboration.
Automatic updates: Cloud providers regularly update their services with new features and security patches, relieving users from the burden of manual updates.
- Cost savings: By leveraging the cloud, organizations can reduce the need for on-premises infrastructure, maintenance, and staffing costs.
## Types of cloud services
Cloud services can be categorized into the following types:

- Software as a Service (SaaS): Users access and utilize software applications over the internet without the need for installation or management. Examples include Spotify and Dropbox.
- Infrastructure as a Service (IaaS): Users have more control and flexibility to run virtual machines and manage their computing resources in the cloud.
- Platform as a Service (PaaS): Developers can deploy and manage applications without worrying about the underlying infrastructure.
## Advantages and disadvantages of using the cloud
Advantages of using the cloud include:

- Enhanced security: Cloud providers implement robust security measures to protect data and infrastructure.
- Scalability: Resources can be easily scaled up or down based on demand.
- Disaster recovery: Cloud services often have built-in backup and recovery mechanisms.
- Accessibility: Cloud services can be accessed from anywhere with an internet connection.
- Automatic updates: Cloud providers handle regular updates and patches.
## Disadvantages of using the cloud include:

- Limited control: Users have less control over the underlying infrastructure and operations.
- Internet dependency: Cloud services require a reliable internet connection for access and usage.
- Latency: The speed of accessing and processing data in the cloud depends on internet connection quality.
- Dependability: Reliance on a third-party provider for service availability and performance.
- Data migration: Moving data between different cloud services or back to on-premises can be challenging.
- Cost: While cloud services can provide cost savings, they can also incur ongoing expenses.
## Disadvantages of hybrid cloud or multi-cloud
Using a hybrid cloud or multi-cloud approach can have the following disadvantages:

- Need for expertise across multiple cloud services: Managing and integrating multiple cloud services may require specialized knowledge and skills.
- Cost considerations: Maintaining a hybrid cloud or utilizing multiple cloud providers can increase overall expenses.
- Premises and cloud expenditure: Managing on-premises infrastructure alongside cloud services may involve additional costs.
- Limited control: The complexity of a hybrid or multi-cloud environment can reduce control and visibility.
## Cost comparison: On-premises vs. cloud for organizations
For organizations, the cloud often provides cost advantages compared to maintaining on-premises infrastructure. Some reasons include:

- Cloud pricing flexibility: Cloud services offer various pricing models, including pay-as-you-go, allowing organizations to optimize costs and scale resources based on usage.
- Reduced maintenance: With the cloud, organizations don't need to maintain physical infrastructure, upgrade hardware, or perform security maintenance tasks.
- Backup and disaster recovery: Cloud providers typically offer built-in backup and disaster recovery solutions, eliminating the need for separate investments and maintenance.
- Scalability and resource optimization: The cloud allows organizations to scale resources up or down based on demand, optimizing costs by paying only for what they need.
## Cloud providers: Choosing the best
Amazon Web Services (AWS) is often considered the largest cloud provider globally, offering a broad range of features, extensive certifications, and a dominant market presence. However, the choice of the best cloud provider depends on specific requirements, including the desired services, pricing, geographic availability, support, and integration capabilities.

## Azure organization structure
Azure provides an organizational structure to manage resources effectively:

!["Azure structure"](https://github.com/ElenaCKay/tech241_azure/blob/main/howIsAzureOrganised.png)

- Management groups: These help organize and manage access, policies, compliance, and permissions within an organization. They allow control over resource usage, such as specifying the size of virtual machines or managing costs for specific departments or teams.
- Subscriptions: Subscriptions act as payment accounts and help separate billing within Azure. Different types of subscriptions are available, including student subscriptions, pay-as-you-go, and free subscriptions.
- Resource groups: Resource groups act as containers for resources and are required in Azure. Resources must be placed within resource groups to provide logical grouping and manage access control and policies.
- Resources: Resources refer to various services and components available in Azure, such as virtual machines, databases, storage, and more. These resources are organized within resource groups.
## What can you do with the cloud?
The cloud offers a wide range of possibilities, including:

- Processing and managing data: Cloud services provide powerful data processing and management capabilities, allowing organizations to analyze, store, and retrieve data efficiently.
- Hosting applications: Applications can be deployed and hosted in the cloud, providing scalability, availability, and accessibility from anywhere.
- Computing: Cloud computing enables organizations to leverage computing power on-demand, allowing for efficient resource utilization and cost optimization.
- Virtual machines: Virtual machines can be provisioned in the cloud, providing flexibility and scalability for running applications and services.

## CapEx vs OpEx

Capital expenditure - Upfront payout.
Operative expenditure - Spread over the year.
The cloud is usually OpEx and on prem is usually both as you have to buy the inital stuff and then have to upkeep them.

## Tags

Subscription gives you a separate bill. You can tag a key pair such as team: Sales and these can be tagged to the resources so you know who has used what resource.

## Categories of Azure services 

- Storage
- Network
- Compute
- DevOps
- AI
- Big data
- IoT
- Web
- Database
- Mobile

## 4 ways to access Azure

ARM - Azure resource manager an API. All the methods go through this and it makes sure you are authenticated. Updates CLI and powershell first.

1. Portal - user interface
2. CLI - 
3. Powershell - 
4. Other services and tools

portal.azure.com -> how to access the azure portal

## What is a virtual network or subnetwork

A way of housing the virtual sytems to a network so they can work together. Consider the virtual network as your house so its like security. The subnets are breaking it up into rooms. They dont overlap. 

### Creating an Azure Virtual Network:

1. Log in to portal.azure.com
2. Create a virtual network (VNet)
3. Under Basics name it <group>-<first name>-<what is it for?>-vnet
4. Under Basics change the region to UK South
5. Under Tags create a tag with owner and your name
6. Otherwise use default settings
7. Review + Create 

## Virtualisation

### What is virtualisation?

It is the process of creating a virtual or simulated verion of a computer system or resources. It allows multiple resources in to a single environment.

### What is a virtual machine?

A virtual machine (VM) is a emulation of a physical computer system. It is created within a virtual environment so multiple machines can coexist on a single computer.

### Where can they be run?

- Desktop using virtualisation software.
- Servers - sevrver visualisation platforms
- Cloud infrastructure - Azure, AWS, GCP

### What determines how many can run?

- Physical hardware resources - CPU cores, memory, network bandwidth
- Virtualisation technology - They have varying capabilities, scalability and resource management.

### What does a virtual machine include?

1. Virtual hardware - there is virtual CPU, memory, disks, network interfaces.
2. Operating system - OS can be Windows, Linux and macOS.
3. Applications - Users can install and run software applications.
4. Virtualisation software - Virtual machine monitor (VMM) manages the virtual machine
5. Virtual machine configuration - Each virtual machine has its on configuration settings
6. Virtual machine files - Stores configuration, operating system image, disk data.

### What software is required to orchestrate / run the virtual machine?


### What is the importance of an image when creating a VM?

Image is base operating system 


## Random notes on virtual machines
when you create a virtual machine you have to make the virtual SSH key first. Within the .ssh file 
Remember to turn it off when finished!




