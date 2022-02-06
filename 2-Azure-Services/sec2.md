# Describe Core Azure Services (15-20%)
## Describe the core Azure architectural components
### describe the benefits and usage of Regions and Region Pairs 
-Regions are the physical geographical location in which Azure servers exist.
-Azure has over 60 regions available (but all regions aren't accessible by everyone).
-Government Services, a version of private cloud, is not available for public consumption.
-In addition, certain regions have specifc use restrictions (China for example). 
-Each region has another region that's treated as it's "pair". The regions are typicaly in the same geographical location due to data storage laws. The data conenction between region pairs has the highest speed available. Software rollouts are deployed to one region of a pair and the other ism't touched. If multiple regions go down, one region in each pair is treated as a priority.

### describe the benefits and usage of Availability Zones 
-Azure availability zones are physically and logically separated datacenters with their own independent power source, network, and cooling. Connected with an extremely low-latency network, they become a building block to delivering high availability applications.
-Azure availability zones are tolerant to local failures. Failures can range from software and hardware failures to events such as earthquakes, floods, and fires. Tolerance to failures is achieved because of redundancy and logical isolation of Azure services. To ensure resiliency, a minimum of three separate availability zones are present in all availability zone-enabled regions.

### describe the benefits and usage of Resource Groups 
-Azure Resources Groups are logical collections of virtual machines, storage accounts, virtual networks, web apps, databases, and/or database servers.
-Users will group related resources for an application, divided into groups for production and non-production

![Azure Resource Group Image](/IMG/azure-resource-groups.png)

### describe the benefits and usage of Subscriptions 


### describe the benefits and usage of Management Groups 


### describe the benefits and usage of Azure Resource Manager 


### explain Azure resources 


## Describe core resources available in Azure
### describe the benefits and usage of Virtual Machines, Azure App Services, Azure Container Instances (ACI), Azure Kubernetes Service (AKS), and Azure Virtual Desktop 


### describe the benefits and usage of Virtual Networks, VPN Gateway, Virtual Network peering, and ExpressRoute 


### describe the benefits and usage of Container (Blob) Storage, Disk Storage, File Storage,and storage tiers 


### describe the benefits and usage of Cosmos DB, Azure SQL Database, Azure Database for MySQL, Azure Database for PostgreSQL, and SQL Managed Instance 


### describe the benefits and usage of Azure Marketplace 

### [Return to Table of Contents](/README.md)
### [Azure Services Resources](/2-Azure-Services/2-resources.md)