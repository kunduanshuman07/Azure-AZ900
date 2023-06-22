# Azure-AZ900

#Instructions to follow before you step into the Repo files:

1. Check the order , github lags highly in sorting the files based on numerals so check the file number and go from say file(1) - file(10) otherwise you will miss the understanding of the topics and get confused.

2. Open the Notes at last because the notes is more of a summary of the particular episode.

3. The best way to utilize the content is to download the repo ZIP and open the downloaded content in a text editor preferably VS code.

4. Read the course overview file for the understanding of the weightage of the certification examination.

5. Complete Summary below:

Microsoft Azure Fundamentals (AZ-900) Certification Exam Notes

Table of Contents:

Introduction to Cloud Computing
Introduction to Microsoft Azure
Azure Services and Solutions
Azure Management Tools and Azure Portal
Azure Compute Services
Azure Storage Services
Azure Networking Services
Azure Identity and Access Management
Azure Security and Compliance
Azure Pricing and Support
Conclusion
1. Introduction to Cloud Computing
What is Cloud Computing?
Cloud computing refers to the delivery of computing services (servers, storage, databases, networking, software, analytics, etc.) over the internet ("the cloud") on a pay-as-you-go basis.
It eliminates the need to own and manage physical infrastructure, reducing costs and improving scalability and flexibility.
Cloud Deployment Models
Public Cloud:

Services are provided by third-party cloud providers, accessible to the public over the internet.
Examples: Microsoft Azure, Amazon Web Services (AWS), Google Cloud Platform (GCP).
Private Cloud:

Services are dedicated to a single organization.
Infrastructure is managed by the organization itself or a third party.
Offers more control and security but requires higher upfront costs.
Hybrid Cloud:

Combination of public and private clouds, allowing data and applications to be shared between them.
Provides flexibility and allows organizations to leverage the benefits of both models.
Cloud Service Models
Infrastructure as a Service (IaaS):

Provides virtualized computing resources (servers, storage, networks) on-demand.
Customers have control over the operating systems, applications, and network configurations.
Examples: Azure Virtual Machines (VMs), AWS EC2.
Platform as a Service (PaaS):

Provides a platform to develop, test, and deploy applications without worrying about infrastructure management.
Customers focus on building applications while the cloud provider manages the underlying infrastructure.
Examples: Azure App Service, AWS Elastic Beanstalk.
Software as a Service (SaaS):

Provides ready-to-use applications accessible over the internet.
Customers do not manage or control the underlying infrastructure, only use the software.
Examples: Office 365, Salesforce, Dropbox.
Benefits of Cloud Computing
Cost-Effective: Pay only for what you use, no upfront costs for hardware.
Scalability: Easily scale resources up or down based on demand.
Reliability: High availability and fault tolerance provided by cloud providers.
Security: Cloud providers offer advanced security measures and compliance certifications.
Flexibility: Access cloud services from anywhere using an internet connection.
Disaster Recovery: Data is backed up and can be quickly restored in case of failures.
2. Introduction to Microsoft Azure
What is Microsoft Azure?
Microsoft Azure is a cloud computing platform and service provided by Microsoft.
It offers a wide range of cloud services, including computing power, storage, databases, networking, and more.
Key Features of Azure
Global Presence:

Azure has a vast network of data centers worldwide, enabling global reach and low-latency connections.
Azure Resource Manager (ARM):

ARM is the management layer that allows you to deploy, manage, and organize Azure resources.
Azure Marketplace:

A marketplace for third-party applications, services, and solutions that can be deployed on Azure.
Azure Active Directory (Azure AD):

A cloud-based identity and access management service that enables secure sign-on and access control.
Azure DevOps:

A set of development tools, services, and features for building, testing, and deploying applications on Azure.
Integration with On-Premises:

Azure provides various tools and services for integrating on-premises infrastructure with the cloud.
Azure Subscriptions and Management Groups
Azure Subscription: A logical container for Azure resources. All resources are associated with a subscription.
Management Group: A container that helps organize and manage subscriptions in a hierarchical structure.
Azure Regions and Availability Zones
Azure Region: A geographical area containing multiple data centers that are in close proximity to each other.
Availability Zone: A physically separate data center within an Azure region, providing redundancy and fault tolerance.
3. Azure Services and Solutions
Compute Services
Azure Virtual Machines (VMs):

Provides virtualized computing resources with various configurations and operating systems.
Azure App Service:

A platform for building and hosting web applications, mobile app backends, and RESTful APIs.
Azure Functions:

Serverless computing service for executing code in response to events or triggers.
Storage Services
Azure Blob Storage:

Storage service for storing large amounts of unstructured data, such as files and media.
Azure File Storage:

Fully managed file share service accessible over SMB protocol.
Azure Table Storage:

NoSQL key-value store for storing structured data.
Database Services
Azure SQL Database:

Fully managed relational database service based on Microsoft SQL Server.
Azure Cosmos DB:

Globally distributed, multi-model database service for NoSQL data.
Azure Database for MySQL/PostgreSQL:

Fully managed database services for MySQL and PostgreSQL.
Networking Services
Azure Virtual Network (VNet):

Isolated virtual network in Azure to securely connect and isolate Azure resources.
Azure Load Balancer:

Distributes incoming traffic across multiple resources to improve availability and scalability.
Azure VPN Gateway:

Enables secure connections between Azure VNets and on-premises networks.
AI and Machine Learning Services
Azure Cognitive Services:

Pre-built AI models and APIs for adding vision, speech, language, and search capabilities to applications.
Azure Machine Learning:

Service for building, deploying, and managing machine learning models.
Internet of Things (IoT) Services
Azure IoT Hub:

Centralized hub for bi-directional communication with IoT devices at scale.
Azure IoT Central:

Fully managed SaaS offering for easily creating and managing IoT solutions.
Developer Tools
Azure DevOps:

Set of development tools for source control, CI/CD, project management, and more.
Azure Functions:

Serverless computing service for executing code in various programming languages.
Analytics and Monitoring Services
Azure Monitor:

Monitoring service that provides insights into the performance and health of applications and resources.
Azure Log Analytics:

Collects and analyzes log and telemetry data from various sources.
Azure Application Insights:

Application performance monitoring (APM) service for monitoring live applications.
Integration Services
Azure Logic Apps:

Visual workflow service for integrating applications, data, and systems.
Azure Service Bus:

Messaging service for connecting distributed systems.
4. Azure Management Tools and Azure Portal
Azure Portal
Web-based interface for managing and monitoring Azure resources.
Provides a graphical representation of resources and allows performing administrative tasks.
Azure PowerShell
Command-line interface (CLI) for managing Azure resources using PowerShell scripting.
Azure CLI
Cross-platform CLI for managing Azure resources using command-line commands.
Azure Cloud Shell
Interactive shell environment accessible from Azure Portal, Azure CLI, or Azure PowerShell.
Provides a browser-based command-line experience with pre-configured tools and Azure resources.
Azure Advisor
Service that provides recommendations to optimize Azure resources for performance, security, and cost.
Azure Resource Manager (ARM)
Management layer that allows you to deploy, manage, and organize Azure resources.
Enables the use of Azure Resource Manager templates for declarative deployment.
5. Azure Compute Services
Azure Virtual Machines (VMs)
Virtualized computing resources that provide flexibility and scalability for running applications.
Can be configured with various sizes, operating systems, and extensions.
Azure App Service
Fully managed platform for building, deploying, and scaling web and mobile applications.
Supports various programming languages and frameworks.
Azure Kubernetes Service (AKS)
Managed container orchestration service that simplifies the deployment and management of containerized applications.
Azure Functions
Serverless computing service that allows you to run code without provisioning or managing servers.
Executes code in response to events or triggers.
6. Azure Storage Services
Azure Blob Storage
Storage service for storing large amounts of unstructured data, such as files, images, and videos.
Provides durability, availability, and scalability.
Azure Files
Managed file share service that can be accessed over the Server Message Block (SMB) protocol.
Enables file sharing across multiple VMs.
Azure Queue Storage
Service for storing and retrieving large numbers of messages in a queue.
Used for building scalable and decoupled applications.
Azure Table Storage
NoSQL key-value store for storing structured data.
Suitable for applications that require fast and non-relational data access.
7. Azure Networking Services
Azure Virtual Network (VNet)
Isolated network environment in Azure that provides secure communication between Azure resources.
Can be connected to on-premises networks using VPN gateways.
Azure Load Balancer
Distributes incoming network traffic across multiple resources to improve availability and scalability.
Supports inbound and outbound scenarios.
Azure Application Gateway
Web traffic load balancer that provides application-level routing and load balancing.
Offers SSL termination, URL-based routing, and session persistence.
Azure VPN Gateway
Service that enables secure connections between Azure VNets and on-premises networks.
Provides site-to-site and point-to-site connectivity options.
8. Azure Identity and Access Management
Azure Active Directory (Azure AD)
Cloud-based identity and access management service that provides authentication and authorization capabilities.
Enables single sign-on (SSO) to various applications and services.
Azure AD B2B
Azure AD feature that allows you to invite external users to collaborate securely with your organization's resources.
Azure AD B2C
Azure AD feature for managing customer identities in consumer-facing applications.
Provides identity and access management for external users.
Role-Based Access Control (RBAC)
Azure feature that enables fine-grained access control to Azure resources based on user roles and permissions.
Azure Multi-Factor Authentication (MFA)
Authentication method that requires users to provide additional verification factors, such as a phone call, text message, or mobile app notification.
