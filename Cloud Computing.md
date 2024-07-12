
# CLOUD COMPUTING ECOSYSTEM

- Comsumers of Services
- Provider of Services
- Designer of Services

# UNDERSTANDING COMPUTING AND CLIENTS



# Cloud Service Component

- CSP data center, its role is to host cloud services
- Client, means of access to cloud services for consumer
- Network, path between cloud services and client services

# Cloud Computing Models

- Deployment model
- Service model


# Deployment Model 

- Public Cloud
- Hybrid Cloud
- Private Cloud

# Service Model

- Infrastructure as a Service (IaaS)
- Platform as a Service (PaaS)
- Software as a Service (SaaS)

# Primary Considerations for Hybrid Model

- Latency and Performance
- Security: Planning in Context
- Governance: Getting the right balance
- Reliability in the Context of Change

# MANAGING A HYBRID AND MULTICLOUD ENVIRONMENT


# Managing SaaS Applications


**SaaS** applications can be used by anyone with access to a browser and can sign up for a license and start using it. All **SaaS** applications are not equal. Well-designed applications provide value to the business along with governance to the business along with governance and audibility for administrators.
It is worth noting that organization do not manage external **SaaS** applications as they're maintained by the companies that developed them.


# Managing External Cloud Resources

Businesses use various types of external or public cloud resources that require management. Cloud services are the main core to creating applications. The infrastructure services are designed as a layer below **SaaS** applications and therefore are the responsibility of software developers. It is important to understand who is using cloud services, and that is something management should focus on.

# Service Level Agreement(SLA)

Cloud resources come with a contractual agreement, and it is know as Service Level Agreement(SLA). The SLA outlines what the provider is delivering, along with the customer's responsibilities. The agreement should outline characteristics like availability, accuracy, response time, throughput, and security.


# MICROSOFT AZURE


# Core Architecture and Resource Management Concepts

When it comes to resource management, an organization may need its administrators to properly set up the core structure in Microsoft Azure.

Here are 4 level for organizing organization's resource in Microsoft Azure: 
- Management groups
- Subscriptions
- Resource groups
- Resources

Azure management groups is the the top level of the core structure of managing cloud resources.
Management groups are where Azure administartors manage everything about user access, compliance, and policies for subscriptions.
 
- **Azure subscriptions** - are like a container for every user account and the resources the have accessed or used within the subscriptions.
- **Azure Resource Groups** - act as a container where resources like servers, web applications, databases, storage, monitoring etc. are deployed, managed and stored.
- **Azure Resources** - is the combination of services you create on the Azure platform, they consist mainly of web applications, databases, servers and virtual machines. These resources or services must be added into a resource group.
- **Azure Resource Manager** - is the management and deployment service providing users the capability to add, edit and delete resources in Azure. With the uses of ARM, the organization can manage user access control and organize resources securely even after deployement.


# Azure Roles

To control access ti resources in Azure, there to need to be a set up and enforcement of user permissions by using Azure Roles.

Role assignment elements: 

**Security Principal** - is an object representing a security identity that can be authenticated and authorized to access resources. They are used to grant or deny permissions.
**Role Definition** - is a set of permissions for Azure users or service principals to utilize Azure resources. Defines permissions for security principals to access resources. May allow reading, writing and deleting Azure subscription resources.
**Scope** - determines the level at which the role assignment applies. Defines a set of resources the role assignment applies to and can be set at various levels in the  Azure resource hierarchy, including the management group, subscription, resource group, and indivisual resource levels.












































































































































