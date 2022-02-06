# Describe Core Azure Services (15-20%)
## Describe the core Azure architectural components
### describe the benefits and usage of Regions and Region Pairs 
-Regions are the physical geographical location in which Azure servers exist.
-Azure has over 60 regions available (but all regions aren't accessible by everyone).
-Government Services, a version of private cloud, is not available for public consumption.
-In addition, certain regions have specifc use restrictions (China for example). 
-Each region has another region that's treated as it's "pair". The regions are typicaly in the same geographical location due to data storage laws. The data conenction between region pairs has the highest speed available. Software rollouts are deployed to one region of a pair and the other ism't touched. If multiple regions go down, one region in each pair is treated as a priority.

### describe the benefits and usage of Resource Groups 
-Azure Resources Groups are logical collections of virtual machines, storage accounts, virtual networks, web apps, databases, and/or database servers.
-Users will group related resources for an application, divided into groups for production and non-production

![Azure Resource Group Image](/IMG/azure-resource-groups.png)

-The Azure Resource Group Management Model provides four levels, or "scopes" of management to help you organize your resources:
**Management Groups**: containes that help you manage access, policy, and compliance for multiple subsciptions. All subscriptions in a management group automatically inherits the conditions applied to the management group. These are often used for grouping subscriptions by internal department or geographical location.
**Subscriptions**: associates user accounts nad resources that were created by those user acounts. Each subscription has limits or quotas on the amount of resources you can create and use. Organizations use subscriptions to manage costs and the resources that are created by users, teams, or projects. A subscription can be seen as a billing unit.
**Recource Groups**: a logical container where Azure resources are deployed. 
**Resources**: Instances of services that you create (virtutal machines, storage, SQL databased, etc.)

**NOTE**: a management group cannot include an Azure Resource, it can only include other management groups or subscriptions. Also, there is no structure for a “nested” resource group in Azure – to “nest” groups for permissions, you will need to use a combination of permissions at the different levels listed above.

### describe the benefits and usage of Availability Zones 
-Azure availability zones are physically and logically separated datacenters with their own independent power source, network, and cooling. Connected with an extremely low-latency network, they become a building block to delivering high availability applications.
-Azure availability zones are tolerant to local failures. Failures can range from software and hardware failures to events such as earthquakes, floods, and fires. Tolerance to failures is achieved because of redundancy and logical isolation of Azure services. To ensure resiliency, a minimum of three separate availability zones are present in all availability zone-enabled regions.

### describe the benefits and usage of Subscriptions 
Azure Subscriptions are the highest level Azure resource. A subscription is a billing unit. 
-All other resources are created inside subscriptions. 
-Each subscription has an unique subscription ID that identifies it. 
-Each subscription has limits/quotas associated with it.

### describe the benefits and usage of Management Groups 

-
-Management groups can be nested.

### describe the benefits and usage of Azure Resource Manager 
Gives users the ability to manage resource groups. Serves as the management layer for your resources. Benefits include:
-ability to manage your infrastructure through declarative templates rather than through scripts
-tagging management
-deployment templates
-dependency mapping
-simpliefied role-based access control
-clarified cost management

You can create an Azure Resource Group using the Azure Portal, Azure PowerShell scripts, Azure CLI, and an ARM Template.


### explain Azure resources 
Azure resources are an instance of a service that you create and use. (Virtual machines, databases, Active Directory, etc.)

## Describe core resources available in Azure
### describe the benefits and usage of Virtual Machines, Azure App Services, Azure Container Instances (ACI), Azure Kubernetes Service (AKS), and Azure Virtual Desktop 


### describe the benefits and usage of Virtual Networks, VPN Gateway, Virtual Network peering, and ExpressRoute 


### describe the benefits and usage of Container (Blob) Storage, Disk Storage, File Storage,and storage tiers 


### describe the benefits and usage of Cosmos DB, Azure SQL Database, Azure Database for MySQL, Azure Database for PostgreSQL, and SQL Managed Instance 


### describe the benefits and usage of Azure Marketplace 

### [Return to Table of Contents](/README.md)
### [Azure Services Resources](/2-Azure-Services/2-resources.md)