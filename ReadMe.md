# [Microsoft Azure Virtual Training - Fundamentals (AZ900)](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-cloud-concepts/)

## Table of Contents

- [Microsoft Azure Virtual Training - Fundamentals (AZ900)](#microsoft-azure-virtual-training---fundamentals-az900)
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
  - [Day 2](#day-2)
    - [Agenda](#agenda-1)
    - [Q&A](#qa-1)
    - [Module 4 Azure Security and network security](#module-4-azure-security-and-network-security)
      - [Outline](#outline-1)
      - [Azure Security Center](#azure-security-center)
        - [Azure Security Center capabilities](#azure-security-center-capabilities)
      - [Azure Sentinel](#azure-sentinel)
      - [Azure Key Vault](#azure-key-vault)
      - [Azure Dedicated Host](#azure-dedicated-host)
      - [Secure network connectivity](#secure-network-connectivity)
      - [Defense in depth](#defense-in-depth)
      - [Shared Security](#shared-security)
      - [Network security Groups (NSGs)](#network-security-groups-nsgs)
      - [Azure Firewall](#azure-firewall)
      - [Azure Distributed Denial of service (DDoS) protection](#azure-distributed-denial-of-service-ddos-protection)
      - [Defense in depth Reviewed](#defense-in-depth-reviewed)
    - [Module 5 Identity, governance, privacy and compliance](#module-5-identity-governance-privacy-and-compliance)
      - [outline](#outline-2)
      - [Compare Authentication and authorization](#compare-authentication-and-authorization)
      - [Azure Multi-Factor Authentication](#azure-multi-factor-authentication)
      - [Azure Active Directory](#azure-active-directory)
      - [Conditional Access](#conditional-access)
      - [Azure Governance Methodologies](#azure-governance-methodologies)
      - [Explore Role Based Access control (RBAC)](#explore-role-based-access-control-rbac)
      - [Resource Locks](#resource-locks)
      - [Tags](#tags)
      - [Azure Policy](#azure-policy)
      - [Azure Blueprints](#azure-blueprints)
      - [Cloud Adoption Framework](#cloud-adoption-framework)
      - [Privacy, Compliance and data protection standards](#privacy-compliance-and-data-protection-standards)
      - [Security, Privacy and compliance](#security-privacy-and-compliance)
      - [Compliance terms and requirements](#compliance-terms-and-requirements)
      - [Azure Compliance Documentation](#azure-compliance-documentation)
      - [Microsoft privacy statement](#microsoft-privacy-statement)
      - [Online Services Terms and Data Protection Addendum](#online-services-terms-and-data-protection-addendum)
      - [Trust Center](#trust-center)
      - [Azure Sovereign Regions (US Government services)](#azure-sovereign-regions-us-government-services)
      - [Azure Sovereign Regions (Azure China)](#azure-sovereign-regions-azure-china)
    - [Module 6 Azure Pricing and Lifestyle](#module-6-azure-pricing-and-lifestyle)
      - [Outline](#outline-3)
      - [Planning and Cost management](#planning-and-cost-management)
      - [Factors affecting costs](#factors-affecting-costs)
      - [Pricing Calculator](#pricing-calculator)
      - [Total Cost of ownership Calculator](#total-cost-of-ownership-calculator)
      - [Azure Cost Management](#azure-cost-management)
      - [Minimizing Costs](#minimizing-costs)
      - [Azure SLAs and service lifecycles](#azure-slas-and-service-lifecycles)
      - [Service Level Agreements](#service-level-agreements)
      - [SLA for azure products and services](#sla-for-azure-products-and-services)
      - [Actions that affects SLA](#actions-that-affects-sla)
      - [Azure Preview Program](#azure-preview-program)
      - [Monitoring services and feature updates](#monitoring-services-and-feature-updates)

## Day 1

### Agenda

- Time Session Content 
	- 10.00 – 10.03 Introduction 
	- 10.03 – 11.13  Azure Cloud Concepts Core Azure Services
	- 11.13 – 11.23 Break-10 minutes
	- 11.23 – 11.40 Azure Solutions and Management Tools 
	- 11.40 – 12.10 Closing Q&A

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


## Day 2

### Agenda

Agenda for today

- Time Session Content 
	- 10.00 – 10.03 Introduction 
	- 10.03 – 11.20 Azure Security and Network Security Identity, governance, privacy and compliance 
	- 11.20 – 11.30 Break-10 minutes 
	- 11.30 – 12.00 Azure Pricing and Lifestyle 
	- 12.00 – 12.30 Closing Q&A


### Q&A

**Good Morning!**

Hello everyone! Thank you for joining the Azure Fundamentals Part 2 Training day today. There is a list of resources available on your screen now. Please feel free to ask the speaker questions within this chat box. If you are having technical issues, please click the question mark, Help widget on your screen now. After the session ends, please make sure to fill out the survey as your feedback is much appreciated. Please do keep an eye on the Microsoft UK Training Days webpage for more events coming up [https://www.microsoft.com/en-gb/events/training-days](https://www.microsoft.com/en-gb/events/training-days)/ . Enjoy the session! – 'The Microsoft Training Days' Event Team


**Azure Fundamentals Fun Path**

Azure Fundamentals Path - [http://aka.ms/azfunpath](http://aka.ms/azfunpath)

**How you will receive your exam**

Once you have completed both Part 1 and Part 2 of this training you are eligible to take the Microsoft Azure Fundamentals certification exam at no cost. You will receive a 'Thank You' email in the next 5 working days with steps on how you can claim and schedule your exam, you will have one attempt to take the exam. Please ensure to check your junk mail box in case the email finds it way there. Thanks


### Module 4 Azure Security and network security

#### Outline

- Azure Security features
	- Security center and resource hygiene
	- key vault, sentinel and Dedicated hosts
- Azure network security
	- defense in depth
	- Network Security Groups and Firewalls
	- DDoS Protection


#### Azure Security Center

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Azure%20Security%20Center.png)

Azure Security Center is a monitoring service that provides threat protection across both azure and on-premises datacenter

- provides security recommendations
- detects and block malware
- analyze and identify attacks
- just in time access control for ports

##### Azure Security Center capabilities

- Policy Compliance
	- Run policies across management groups, subscripts or tenants
- Continuous Assessments
	- Assess new deployed resources to ensure that they are configure properly
- Tailored Recommendations
	- Recommendations based on existing workloads with instructions on how to implement them
- Threat Protection
	- Analyze attempted threats through alerts and impacted resource reports

#### Azure Sentinel

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Azure%20Sentinel.png)

Azure sentinel is a security information management (SIEM) and security automated response solutions that provides security analytic and threat intelligence across an enterprise

- Connector and Integration
	- O365
	- Azure AD
	- Azure Advanced threat protections
	- Microsoft cloud app security


#### Azure Key Vault

Azure Key Vault stores applications secretes in a centralized cloud locations in order to securely control access permissions and access logging

- Secrets management
- Key management
- certificate management
- storing secrets backed by hardware security modules (HSMs)

#### Azure Dedicated Host

Azure Dedicated host provides physical server that host one or more azure virtual machine that is dedicated to a single organization's workload

Virtual Scale Set are not supported.

- Benefits
	- Hardware isolation at the server level
	- Control over maintenance event timing
	- Aligned with Azure Hybrid Use Benefits


#### Secure network connectivity

#### Defense in depth

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Defense%20in%20depth.png)

- A layered approach to securing computer systems
- provides multiple levels of protection
- attacks against one layer are isolated from subsequent layers

#### Shared Security

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Shared%20Security.png)

- Migration from customer controlled to cloud based datacenter shifts the responsibility for security
- Security becomes a shared concern between cloud providers and customers


#### Network security Groups (NSGs)

Network security groups filter network traffic to and from azure resources on azure virtual networks

Default roles cannot be deleted, only overwrite.
lower the number, the higher the priority

- Set inbound and outbound rules to filter by source and destination IP addresses, port and protocols
- Add multiple rules as needed within subscription limits
- Azure applies default, baseline security rules to new NSGs
- Override default rules with new, higher priority rules



#### Azure Firewall
A stateful managed firewall as a service that grants/denies server access based on originating IP address in order to protect network resources

- Applied inbound and outbound traffic filtering rules
- build in high availability
- unrestricted cloud scalability
- uses azure monitoring logging

Azure Application gateway also provides a firewall, web application firewall (WAF). WAF provides centralized, inbound protection for your web applications

#### Azure Distributed Denial of service (DDoS) protection

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Azure%20Distributed%20Denial%20of%20service%20(DDoS)%20protection.png)

DDoS attacks overwhelm and exhaust network resources making apps slow or unresponsive

- sanitizes unwanted network traffic before it impacts service availability
- basic service tier is automatically enabled in azure
- standard service tiers adds mitigation capabilities that are tuned to protect azure virtual network resources

#### Defense in depth Reviewed

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Defense%20in%20depth.png)

Combining network security solutions
- **NSGs** with **Azure Firewall** to achieve defense in depth
- **Perimeter Layer** protects your network boundaries with Azure DDoS Protection and Azure Firewall
- **Network Layer** only permits traffic to pass between networked resources with Network Security Group (NSG) inbound and outbound rules


### Module 5 Identity, governance, privacy and compliance 

#### outline

- Azure identity services
	- Authentication versus authorization
	- Azure AD, MFA, SSO and conditional Access
- Azure governance features
	- RBAC
	- Resource locks and tags
	-Policy, blueprints and CAF
- Azure privacy and compliance
	- Privacy Statement and online services terms
	- Trust center and compliance documentation
	- Azure Sovereign regions

#### Compare Authentication and authorization

- Authentication
	- Identifies the person or service seeking access to a resource
	- requests legitimate access credentials
	- basis for creating securing identity and access control principles
- Authorization
	- Determine an authenticated persons or services level of access
	- defines which data the can access and what they can do with it


#### Azure Multi-Factor Authentication

Provides additional security for your identities by requiring two or more elements for full authentication. Azure currently only supports **something you know** and **something you possess**

- Something you know
	- password
	- security questions
- Something you possess
	- Auth apps,
	- OTP
	- keys
- Something you are
	- Biometrics

#### Azure Active Directory

Azure active directory is Microsoft azure cloud based identity and access management service

- Authentication (Employees sign-in to access resources)
- Single Sign on (SSO)
- Application management
- Business to Business (B2B)
- Business to customer (B2C) identity service
- Device management


#### Conditional Access

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Conditional%20Access.png)

Conditional Access is used by Azure Active Directory to bring signals together to make decisions and enforce organizational policies

Think of them like IF/THEN Statements

- user or group memberships
- IP Location
- Device
- Application
- Risk Detection

#### Azure Governance Methodologies

#### Explore Role Based Access control (RBAC)

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Explore%20Role%20Based%20Access%20control%20(RBAC).png)

- Fine grained access management
- Segregate duties within the team and grants only the amount of access to users that they need to perform their jobs
- Enables access to the azure portal and controlling access to resources

#### Resource Locks

- Protects your azure resources from accidental deletion or modification
- Manage locks at subscripts, resource groups, or individual levels within azure portal

| Lock Types   | Read    | update    | Delete |
| : --------:  | : ----: | : ------: | : ---: | 
| CanNotDelete | Yes     | Yes       | No     |
| ReadOnly     | Yes     | No        | No     |



#### Tags

can have up to 50 tags per Resource

- Provides metadata for your Azure resources
- Logically organizes resources into a taxonomy
- consists of a name-value pair
- Very useful for rolling up billing information

#### Azure Policy

Azure Policy helps to enforce organizational standards and to access compliance at scale. Provides governance and resource consistency with regulatory compliance, security, costs and management

- Evaluates and identifies Azure resources that do not comply with your policies
- Provides Build in Policy and initiative definitions under categories such as Storage, Networking

#### Azure Blueprints

**Azure Blueprints** makes it possible for development teams to rapidly build and stand up new environments. Development teams can quickly build trust through organizations compliance with a st of built in components (such as networking) in order to speed up development and delivery

- Role Assignments
- Policy Assignments
- Azure Resource Manager
- Templates
- Resource Groups

#### Cloud Adoption Framework

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Cloud%20Adoption%20Framework.png)

- The one Microsoft approach to cloud adoption in Azure
- best practices from Microsoft employees, Partners and customers
- Tools, guidance and narratives for strategies and outcomes


#### Privacy, Compliance and data protection standards

#### Security, Privacy and compliance

- Security
	- secure by design. with built in intelligent security, Microsoft helps to protect against known and unknown cyber threats, using automation and artificial intelligence
- Privacy
	- We are committed to ensure the privacy of organizations though our contractual agreements and by providing user control and transparency
- Compliance
	- We respect local laws and regulations and provide comprehensive coverage of compliance offerings


#### Compliance terms and requirements
Microsoft provides the most comprehensive set of compliance offers (including certifications and attestations) of ant cloud service provider. some compliance offerings include

- Criminal Justice Information services (CJIS) 
- Health Insurance Portability and Accountability Act (HIIPAA) 
- CSA STAR Certification
- ISO/IEC 27018
- Eu Model Clauses
- National Institute of Standards and Technology (NIST)


#### Azure Compliance Documentation

Microsoft offices a comprehensive set of compliance offering to help your organization comply with national, regional and industry specific requirements that govern the collection and use of data


#### Microsoft privacy statement

The Microsoft privacy statement provides openness and honesty about how Microsoft handles the user data collected from its products and services

The Microsoft privacy statement explains
- What data Microsoft processes
- How Microsoft processes it
- What purposes the data is used for


#### Online Services Terms and Data Protection Addendum

- Online services Terms
	- The licensing terms define the terms and conditions for the products and online services you purchase though microsoft volume licensing programs
- Data protection addendum
	- The DPA sets forth the obligations with respect to the processing and security of customer Data and Personal Data in connection with the online services


#### Trust Center

Learn about security, privacy, compliance, policies, features and practices across Microsoft cloud products

The Trust center website provides
- In-depth expert information
- curated lists of recommended resources arranged by topic
- role-specific information for business managers, administrators, engineers, risk assessors, privacy officers and legal teams

[https://www.microsoft.com/trustcenter](https://www.microsoft.com/trustcenter)


#### Azure Sovereign Regions (US Government services)

Meets the security and compliance needs of US federal agencies, state and local governments and their solutions provides

Azure Government
- Separate instance of azure
- Physically isolated from non-US government deployments
- Accessible only to screened, authorized personnel

Examples of compliant standards: FedRAMP, NIST 800.171 (DIB), ITAR, IRS 1075, DoD L2, L4 & L5 and CJIS

#### Azure Sovereign Regions (Azure China)

Microsoft is CHina's first foreign public cloud service provider in compliance with government regulations

Azure China features
- Physically separated instance of azure cloud services operated by 21Vianet
- All data stays within china to ensure compliance


### Module 6 Azure Pricing and Lifestyle


#### Outline

- Methods for managing costs
	- Factors affecting costs
	- Options to reduce and control costs
	- Azure costs management
- Service Level Agreements and lifecycles
	- Azure Service level agreement (SLA)]
	- Factors impacting SLAs
	- Azure Product and feature lifecycles

#### Planning and Cost management

#### Factors affecting costs

There are six primary factors affecting costs:

- Resource Types 
	-  Costs are Resource specific, so the usage that a meter tracks and the number of meters associated with a resource, depend on the resource types
- services
	- Azure usage rates and billing periods can differ between Enterprise, Web Direct and CSP Customers
-  Location 
	-  The Azure infrastructure is globally distributed and usage costs might vary between locations that offer Azure products services and resources
-  bandwidth
	-  Some inbound data transfers are free, such as data going into azure datacenter. For outbound data transfers such as data going out of the datacenter, pricing is based on zones
-  Reserved Instance
	-  With Azure Reservations, you commit to buying one year to three year plans for multiple products reservations can significantly reduce your resource costs up to 72% on pay as you go prices
-  Azure Hybrid Use Benefits
	-  For customers with software assurance, Azure hybrid benefit allows you to use your on-premises licenses on Azure at a reduced cost


#### Pricing Calculator

The Pricing calculator is a tool that helps you estimate the cost of azure products. The options that you can configure in the pricing calculator vary between products, but basic configurations options include

- Regions
- Tier
- Billing Options
- Support options

[https://azure.microsoft.com/en-gb/pricing/calculator/](https://azure.microsoft.com/en-gb/pricing/calculator/)


#### Total Cost of ownership Calculator

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Total%20Cost%20of%20ownership%20Calculator.png)

- A tool to estimate cost saving you can realize by migrating to azure
- A report compares the cost of on premises infrastructure with the costs of using Azure Products and services in the cloud


#### Azure Cost Management

- Reporting - Billing reports
- Data Enrichment
- Budgets  - set spend budget
- Alerting - when cost exceed limits
- Recommendation - cost recommendations



#### Minimizing Costs

![image](/images/Microsoft%20Azure%20Virtual%20Training%20-%20Fundamentals/Minimizing%20Costs.png)

#### Azure SLAs and service lifecycles

#### Service Level Agreements

Service level agreements describes Microsoft's commitments for uptime and connectivity

- SLA are based on individual products and services
- Detailed agreements on the service provided and any exceptions to the SLA
- Free and preview features/services do not offer SLAs


#### SLA for azure products and services

- Performance targets are expressed as uptime and connectivity guarantees
- Performance targets range from 99% to 99.999%
- if service fails to meet the guarantees a percentage for the monthly service fees can be credited


| SLA | Downtime per month |
| :--: | :-- | 
| 99% | 7h 18m 17s |
| 99.5% | 3h 39m 8s |
| 99.9% | 43m 49s |
| 99.95% | 21m 54s |
| 99.99% | 4m 22s |
| 99.999% | 26s |

#### Actions that affects SLA

- lower your SLA
	- Adding more services
	- choosing free or non-SLA services
- Raise your SLA
	- Availability Zones
	- Redundant systems

Many factors can raise or lower your SLA. Design decisions based on business goals will drive your SLA goals


#### Azure Preview Program

With Azure previews, users can test beta and other pre-release features, products, services, software and regions to provide feedback. Does not have any SLA.

- Public preview
	- All Azure customers can evaluate the new features
- Generally available (GA)
	- After public preview is complete all customers can use the feature and region availability will vary


#### Monitoring services and feature updates

- Azure updates provide information about the azure products services and features in addition to product road maps and availability
- View details about azure updates and their status
- Browse and search for updates
- Subscribe to Azure update notifications by RSS


