# [Microsoft Azure Virtual Training - Fundamentals](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-cloud-concepts/)

## Table of Contents

- [Microsoft Azure Virtual Training - Fundamentals](#microsoft-azure-virtual-training---fundamentals)
	- [Table of Contents](#table-of-contents)
	- [Day 1](#day-1)
		- [Agenda](#agenda)
		- [Q&A](#qa)
		- [Introduction](#introduction)
		- [Module 1 Azure Cloud Concepts Core Azure Services](#module-1-azure-cloud-concepts-core-azure-services)
			- [Clouds](#clouds)
			- [Cloud Benefits](#cloud-benefits)
			- [Cloud Services - Objective domain](#cloud-services---objective-domain)
			- [On Premises](#on-premises)
			- [IaaS](#iaas)
			- [PaaS](#paas)
			- [SaaS](#saas)
		- [Module 2 Core Azure Resources](#module-2-core-azure-resources)
			- [Outline](#outline)
			- [Regions](#regions)
			- [Region Pairs](#region-pairs)
			- [Availability zones](#availability-zones)
			- [Availability options](#availability-options)
			- [Azure Resources](#azure-resources)
			- [Resource groups](#resource-groups)
			- [Azure resource manager - ARM](#azure-resource-manager---arm)
			- [Azure subscriptions](#azure-subscriptions)
			- [Azure Compute serves](#azure-compute-serves)
			- [Azure Virtual Machines](#azure-virtual-machines)
				- [Demo](#demo)
			- [Azure App Services](#azure-app-services)
			- [Serverless Computing](#serverless-computing)
			- [Azure Container Servers](#azure-container-servers)
				- [Demo](#demo-1)
			- [Windows Virtual Desktop](#windows-virtual-desktop)
			- [Azure network service](#azure-network-service)
				- [Demo](#demo-2)
			- [Azure Database services](#azure-database-services)
			- [Azure SQL managed instance](#azure-sql-managed-instance)
			- [Azure Marketplace](#azure-marketplace)
		- [Modal 3 Azure solutions and management tools](#modal-3-azure-solutions-and-management-tools)
			- [Azure Internet of things](#azure-internet-of-things)
			- [Big Data and analytic](#big-data-and-analytic)
			- [Artificial Intelligence & machine learning](#artificial-intelligence--machine-learning)
			- [Develop your apps with DevOps and GitHub](#develop-your-apps-with-devops-and-github)
			- [Azure management tools](#azure-management-tools)
			- [Azure resource manager templates](#azure-resource-manager-templates)
				- [Demo](#demo-3)
					- [Commands](#commands)
					- [Advisor](#advisor)
			- [Azure Monitor](#azure-monitor)


## Day 1

### Agenda

- Time Session Content 10.00 – 10.03
- Introduction 10.03 – 11.13  
- Azure Cloud Concepts Core Azure Services 11.13 – 11.23
- Break-10 minutes 11.23 – 11.40
- Azure Solutions and Management Tools 11.40 – 12.10
- Closing Q&A 12.10

### Q&A

**Good Morning**

Hello everyone! Thank you for joining the Azure Fundamentals Training day part 1 today. There is a list of resources available on your screen now. Please feel free to ask the speaker questions within this chat box. If you are having technical issues, please click the question mark, Help widget on your screen now. Please do keep an eye on the Microsoft UK Training Days webpage for more events coming up [https://www.microsoft.com/en-gb/events/training-days](https://www.microsoft.com/en-gb/events/training-days)/ . Enjoy the session! – 'The Microsoft Training Days' Event Team

**Do you get a voucher to take the certification at the end of this course please?**

Yes, once you have completed both Part 1 and Part 2 of this training you are eligible to take the Microsoft Azure Fundamentals certification exam at no cost. You will receive a 'Thank You' email in the next 5 working days with steps on how you can claim and schedule your exam and you will have one attempt to take the exam.

**how can we enter our attendance for today and tomorrow?**

Your attendance is automatically tracked through the link you received in the email.

**Is the recording available?**

Unfortunately, there isn't on-demand content available for this event. Please do check / bookmark the resources available on your screen now. Please also refer to the Azure Fundamentals Path - [http://aka.ms/azfunpath](http://aka.ms/azfunpath) which mirrors today's class. Thanks

**Thank you!**

Thank you all for joining us today, hope you all enjoyed today’s webinar. Please do submit questions you may have from today’s session and we will do our best to answer them during this Q&A. See you tomorrow for Part 2!

### Introduction

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Course_Agenda.png)

### Module 1 Azure Cloud Concepts Core Azure Services

#### Clouds

- Public Cloud
  - owned by cloud services
  - accessible to pubic
  - no capital expenditure to sale up
  - pay for what you want
- Private cloud
  - organizations need to get the Infrastructure
- Hybrid Cloud
  - Combines both public and private
  - organizations can choose what is public and what is private

#### Cloud Benefits

- High availability
- Scalability
- Global reach
- agility
- fault tolerance
- elasticity
- customer latency capabilities
- predictive cost considerations

#### Cloud Services - Objective domain

- IaaS Infrastructure-as a-service
- PaaS Platform-as a-service
- SaaS Software-as a-service

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Shared%20Responsibility%20model.png)

#### On Premises

You do everything with your own hardware

#### IaaS

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/IaaS.png)

Build Pay as you go IT infrastructure by renting serves,  virtual machines, storage, network and operating system from a cloud provider

The most flexible cloud services, You configure and manage the hardware and applications

#### PaaS

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Paas.png)

Provider sets up the infrastructure

Focused on app development
Management is handled by the cloud provider

#### SaaS

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/SaaS.png)

Pay-as-you-go pricing model
Users pay for the software tehy use on a subscript model
Users connect to cloud based apps - I.E O365, emails and calendars

### Module 2 Core Azure Resources

#### Outline

- Azure Architectural components
  - Regions and availability Zones
  - Subscriptions and resource groups
- Core Azure Resources
  - Compute
  - Networking
  - Storage
  - Databases

#### Regions

Azure offers more global regions then any other cloud provider with 60+ regions over 140 countries

regions are mad up of one ore more datacenter in close proximity
Provides flexibility and scale to reduce customer latency
Preserve data residency with a comprehensive compliance offering

#### Region Pairs

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Region%20Pairs.png)

- At least 300 mines of separation between region pairs
- Automatic Replication of some services
- provides region recover in the event of an outage
- updates are rollout sequentially to minimize downtime

[https://aka.ms/PairedRegions](https://aka.ms/PairedRegions)

#### Availability zones

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Availability%20zones.png)

Provides protection against downtime due to datacenter failure
physical separate datacenter within the same region
independent power cooling and network
Connected through private fiber-optic network

#### Availability options

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Availability%20options.png)

- VM SLA - 99.9% with premium storage
  - Single VM
- VM SLA 99.99%
  - 1 VM around all the availability zones
- Multi Region DR
  - Regional protection with data residency boundaries

#### Azure Resources

Azure resources are components like storage, virtual machines and networks that are available to build cloud solutions

- VM
- Storage Accounts
- Virtual network
- App services
- SQL databases
- Functions

#### Resource groups

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Resource%20groups.png)

A Resource group is a container to manage and aggregate resources in a single unit

- Resources can exist in only one resource group
- Resources can exist in different regions
- Resources can be moved to different resource groups
- Applications can utilize multiple resource groups

#### Azure resource manager - ARM

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Azure%20resource%20manager.png)

Provides a management layer that enables you to create and delete resources in your Azure subscriptions.
Managed using Portal, powershell, CLI or REST API

#### Azure subscriptions

- Billing boundary
  - generates separate billing reports and invoice for each subscriptions
- Access control  boundary
  - manages and control access to the resources an account can have multiple subscriptions

#### Azure Compute serves

Azure compute is an on-demand service that provides computing resource such as disks, processors, memory, networking and operating systems

- Virtual Machines
- App Services
- Container Instances
- Azure Kubernetes Services (AKS)
- Windows virtual machines

#### Azure Virtual Machines

Azure Virtual Machines (VM) are software emulations of Physical computers

- Includes Virtual processor memory storage and networking
- IAAS offering that provides total control and customization

##### Demo

All services  > compute > VM > Add > Virtual machines > Basics tab > Select Subscripts > create Resource groups > Name it > VM Name - something reverent > Select closest Region > Choose your availability > Select the image of the VM > create admin Account > Set Inbound Ports so you can access it > Disks Tab > Select OS Disk Type > networking Tab > Check all the network settings are correct and Ports are open > Management Tab > You can set up different settings such as auto shutdown or connecting to Azure AD > Review Create > Create

you can download the template for VM Creation automation

in the details of the VM you can see all the options,
can connect to the VM by downloading the RDP files then connecting it

#### Azure App Services

Azure App Services is a fully manages platform to build, deploy and scale web apps and APIs quickly

- Works with .NET, .NET Core, Node.js, Java, Python, or PHP
- PaaS offering with enterprise-grade performance, security and compliance requirements

#### Serverless Computing

Azure Functions
 Event  based code running your service and not the underlying infrastructure
Azure logic apps
 Automate and orchestrate tasks. business processes and workflows to integrate apps

#### Azure Container Servers

Azure containers are a light weight, virtualised environment that does not require operating system management and can respond to changes on demand

- Azure container Instance
  - a PaaS offers that runs as a container without managing the VM or addition servers
- Azure Kubernetes service
  - an orchestration service for containers with distributed architecture and large volumes of containers

##### Demo

All services  > compute > container instance > Add > Basics tab > Select Subscripts > create Resource groups > Name it > Select closest Region > Choose your availability > Select the image source > If you want it public or private > the image name > OS type > size > Networking tab > Give it a DNS name > check ports > Review and create > Create

you can download the template for container Creation automation

You can open the container from the resource tab and see the details on it
you can connect to the container from the FQDN

#### Windows Virtual Desktop

Windows Virtual Desktop is a desktop and app virtualization that runs in the cloud

- Creates a full desktop virtualised environment without having to run additions gateway servers
- Publish unlimited host pools to accommodate diverse workloads
- Reduce costs with pooled, multi-session resources

#### Azure network service

- Azure Virtual networking (VNet)
  - Enables Azure resources to communicate with each other, the internet and on-premises networks
- Virtual private network gateway
  - is used to send encrypted traffic between an azure virtual network and an on-premises location over the public internet
- Azure Express Route
  - extends on-premises networks into azure over a private connection that is facilitated by a connectivity provider

##### Demo

All services  > network > create virtual network > create the resource group > name the network > choose the closes region to you > Review and create > create

can download template for automated network creation

you can then put multiple virtual machines on the same virtual network so that they can talk to each other

#### Azure Database services

- Azure cosmos DB
  - a globally distributed database service that elastically and independently scales throughput and storage
  - NOSQL
- Azure SQL Database
  - a Relational Database as a service (DaaS) based on the latest stable version of Microsoft SQL Server database engine
- Azure Database for MySQL
  - a fully-managed MYSQL database services for app developers
- Azure Database for PostgreSQL
  - a relational database service based on the open-sources Postgres database engine

#### Azure SQL managed instance

Azure SQL Managed instance allows existing SQL server customers to lift and shift their on-premises applications to the cloud with minimal application and database changes

- Fully managed and evergreen platform as a service
- Preserves all Paas capabilities (Automatic patching and version updates, automated backups and high availability)
- Exchange existing licenses for discounted rates on SQL managed instance using the azure hybrid benefit

#### Azure Marketplace

Azure marketplace allows customers to find, try, purchase and provision applications and services from hundreds of leading services providers which are all certified to run on Azure.

- Open source container platforms
- Virtual machine and database images
- Application build and deployment software
- Developer tools

### Modal 3 Azure solutions and management tools

#### Azure Internet of things

Internet of THings is the ability for devices to garner and then relay information for data analysis

- Azure IoT Central
  - is a fully managed global IoT SaaS solutions that makes it easy to connect, monitor and managed IoT assets to scale
- Azure IoT Hub
  - is a managed service hosted in the cloud that acts as a central message hub for bi-directional communication between IoT applications and the devices it manages
- Azure Sphere
  - is a secured, high-level application platform with build-in communication and security features for internet connected devices

#### Big Data and analytic

Azure synapse analytic
 a cloud based enterprise data warehouse
Azure HDInsight
 A fully managed open source analytic services for enterprise
Azure Databricks
 Apache Spark based analytic services

#### Artificial Intelligence & machine learning

- Azure machine learning
  - cloud-based to develop, train and deploy machine learning models
- Cognitive services
  - quickly enable apps to see, hear ,speak, understand and interpret a users needs
- Azure bot services
  - Develop intelligent enterprise grade bots

#### Develop your apps with DevOps and GitHub

- Azure DevOps
  - Development collaboration tools including pipelines, kanban boards and automated cloud-based load testing
- GitHub
  - software development hosting with version control, source code management and bug/task management
- GitHub Actions for Azure
  - automate software workflows to build, test and deploy from within GitHub
- Azure DevTest Labs
  - Quickly create environments in Azure while minimizing waste and controlling cost

#### Azure management tools

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Azure%20management%20tools.png)

- Azure resource manager
  - Azure portal
  - Azure Powershell
  - Mobile app
  - CLI
  - Azure REST API
  - Azure Cloud Shell

#### Azure resource manager templates

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Azure%20resource%20manager%20templates.png)

Azure Resource Manager (ARM) templates are JavaScript Object Notation (JSON) files that can be used to create and deploy Azure infrastructure without having to write programming commands

- Declarative Syntax
- Repeatable Results
- orchestration
- Modular Files
- Build-in Validation
- Exportable code

##### Demo

###### Commands

- Create a new Resource Group
  - `New-AzResourceGroup -Name myRGPS -Location EastUS`
- Get all Resource Groups
  - `Get-AzResourceGroup | Format-Table`
- Get VM's
  - `Get-AzVM -name myVMPS -status | format-Table -autosize`
- Stop VM's
  - `Stop-AzVM -ResouirceGroupName myRGPS - Name myVMPS`

###### Advisor

Makes recommendations for the deployed resources and makes suggestions on best practices and reliability

#### Azure Monitor

Azure Monitor maximizes the availability and performance of applications and services by collecting, analyzing and acting on telemetry from cloud and on-premises environments

- application insight
- log analytic
- smart alerts
- automation actions
- customizes dashboards
