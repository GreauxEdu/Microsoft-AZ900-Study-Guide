# Describe Cloud Concepts (20-25%)
## Identify the benefits and considerations of using Cloud Services
### identify the benefits of cloud computing, such as High Availability, Scalability, Elasticity, Agility, and Disaster Recovery 
* **General Benefits:** Some general benefits for cloud computing include cost savings (both real and accounting), possibility of increased security, global reach (ability to deploy applications around the world which increases speed and performance for global users), range of on-demand services (VMs, AI, Machine Learning, Windows/Linux Servers, Databases, etc.), and a range of tools users have access to.

* **Cost Savings:** Generally speaking, Microsoft can buy, build, and maintain a server on a dollars-per-our basis at a cheaper basis. Users can take steps to reduce costs like turning off services when they aren't in use and adjusting service amounts based on demand.

* **High Availability:** the cloud in general has higher availability than the servers you're running. Availaibility is expressed as a percentage, it's the ability of a system to respond to users. Microsoft Azure has a 99.99% availability (four nines, 4 minutes per month of downtime).

* **Scalability:** is the ability to handle growth of users or demand. Allows end-users to add capacity for their resources.

* **Elasticity:** is the ability of a system to automatically grow and shrink based on application demand and automating it. 

* **Agility:** users have the ability to rapidly respond to market or environment needs in real time based on demand. Gives you the ability to detect when traffic is higher and then be able to grow the system. 

* **Disaster Recovery:** is the ability of a system to recover from failure within a period of time and how much data is lost. End-users are able to get a duplicate copy of their environment.

### identify the differences between Capital Expenditure (CapEx) and Operational Expenditure (OpEx) 
* **Capital Expenditure (CapEx):** is money invested in assets (like computers) that return investment overtime. This could lead to tax advantages and write-offs. Can be seen as the upfront money invested in typical on premises data servers.
* **Operational Expenditure (OpEx):** is money spent on every day operating expenses. 

### Describe the Consumption-Based Model 
* The **Consumption-Based Model** gives end-users the ability to pay by minute, hour, or execution. Cloud computing has a robust set of metrics that charge users based on what they are consiming instead of giving standard fixed-rate packages.


## Describe the Differences between categories of cloud services
### describe the shared responsibility model
![Shared Responsibility Model](/1-Cloud-Concepts\cloud-services.png)
* **shared responsibility model:**

### describe Infrastructure-as-a-Service (IaaS)
* **Infrastructure-as-a-Service (IaaS):**  allows organizations to purchase resources like networking, load balancers, VMs, firewalls and storage on-demand instead of having to buy costly hardware. IaaS is highly scalable and offers businesses more flexibility than on-premise solutions.

* IaaS can be seen as the basic layer in cloud computing. The virtualized components available through the internet are equivalent to the servers and hardware companies would traditionally store in their building.

* Organizations of all sizes can benefit from IaaS. Small companies who want to avoid purchasing hardware or don’t have the time, staff, or ability to host large data centers on-premise, as well as larger businesses who want to stay in control of their apps and only want to consume the resources they actually need. The scalability of IaaS is also great for companies that experience rapid growth.

* The IaaS provider is responsible for managing and maintaining servers, hard drives, storage, and virtualization tools. However, applications, runtime, OS, middleware, and data still need to be managed by the client. 

* **Benefits**: IaaS is more flexible than all the other cloud computing models. With IaaS, you can easily automate the deployment of servers, storage, and networking. IaaS lets you purchase resources on an as-needed basis, so you only pay for what you’re actually using. IaaS lets you retain complete control of your infrastructure. Since you’re only “renting” IT components, you can easily upscale or downscale your resources.

* **Disadvantages**: Before migrating to the cloud, legacy apps might have to be enhanced for the new type of infrastructure. Staff might have to undergo additional training to effectively manage and monitor IaaS. While you are in control over your apps, data, middleware, and the OS platform, you are also responsible for mitigating new security threats.

### describe Platform-as-a-Service (PaaS)
* **Platform-as-a-Service (PaaS):** provides developers with a framework and tools to build apps and software that are tailored to the organization’s individual needs. PaaS can be seen as a scaled-down version of IaaS. Just like IaaS, the customers have access to servers and data centers which are maintained and managed by the third-party provider. However, they mainly use PaaS for building custom SaaS applications.

* There are several situations when a PaaS would be a good idea. For example, if organizations have several developers working on the same development project, PaaS is a great way to streamline workflows. Organizations can even include other vendors and stay flexible during the entire process. PaaS is also the way to go if your organization requires customized applications that need to be developed and deployed in a short amount of time.

* PaaS delivery can be compared to the way SaaS is delivered. The only difference is that customers don’t access online software, but an online platform for the creation of software. And since tools and environment are ready-to-use, software engineers and developers can concentrate on building applications without having to worry about other components like operation systems, storage, and infrastructure.

* **Benefits**: PaaS is a simple, cost-effective way to quickly develop and deploy new apps. PaaS service models can easily be adjusted to a developer’s needs. With PaaS, it’s easy to migrate to a hybrid cloud model. Your developer teams have to do a lot less coding than before. PaaS frees up time as developers can customize apps without having to maintain the software.

* **Disadvantages**: Using third-party vendor-controlled servers means that there are various security risks to look out for. Some PaaS solutions are not optimized for the language or framework that your development teams are used to. You might encounter some challenges with integrating new applications as not every component of your legacy IT system is built for the cloud. Customized cloud operations tend to have automated workflows that might not be compatible with PaaS solutions, thus limiting operational capabilities for your end-user.

### describe Software-as-a-Service (SaaS)
* **describe Software-as-a-Service (SaaS):** These entire cloud application services are the most common form of cloud computing. They are ready-to-use and often run directly through the client’s web browser, meaning there is no need for installations or downloads like it with on-prem solutions. SaaS is hosted on remote servers and fully managed, updated, and maintained by a third-party vendor. This results in less responsibility but also less control for the end-user.

* SaaS is ideal for small companies or startups that don’t have the capacity to develop their own software applications. From e-commerce to short-term projects, SaaS is the quickest and easiest solution if you don’t need highly customized applications. SaaS is also a great option for applications that are not used very often, e.g. tax software.

* SaaS is delivered as a fully functional service and can be accessed remotely via any web browser, allowing clients to work from anywhere. The users connect to the app through a dashboard or API and rely on the SaaS provider when it comes to bug fixes, middleware, support, and any potential technical issues.

* **Benefits**: SaaS usually resides in a shared or multi-tenant environment. When managed correctly, the license costs are lower compared to traditional models. SaaS solutions are easy to scale up or down based on your specific needs. Many SaaS solutions have integrations with other SaaS offerings, so you don’t have to buy another server or software. With SaaS, you instantly benefit from new software releases and upgrades. Without installation or download, SaaS is easy to use and comes with baked-in best practices.

* **Disadvantages**: Since large volumes of sensitive data are being exchanged with off-premise servers, security and compliance might be compromised. SaaS only allows for minimal customization when it comes to features and capabilities. It might be difficult to integrate SaaS with existing apps and services due to dependencies. Users have very little control over functionalities, performance, downtime, or how their data is governed. With the ease of use and scalability SaaS provides, an organization's SaaS stack includes many overlapping, underutilized, or unused apps. The value of SaaS apps in the organization can drop without automated SaaS Management or SaaS optimization processes in place. Employees often purchase or sign up for new SaaS without the knowledge of IT. Unmanaged SaaS apps could have potential security gaps.

### describe serverless computing
* **serverless computing:**

### identify a service type based on a use case
* **service type based on a use case:**



## Describe the Differences between types of Cloud Computing
### define cloud computing
**Cloud Computing:** the process of using a network of remote servers hosted on the Internet to store, manage, and process data rather than a local server or a personal computer.

### describe public cloud 
**Public Cloud:** Everything is built on the Cloud Provider aka “Cloud Native
**Benefits:** it’s the most cost-effective. There are security Controls by default but it might not meet security requirements. The Level of Configuration is limited based on what the cloud service provider exposes to you. You don’t need in-depth knowledge of underlying infrastructure 

#### describe private cloud 
**Private Cloud:**  Everything built on company’s data centers aka On-Premise
**Benefits:** The cloud could be OpenStack. It is the most expensive type of cloud computing. There is no guarantee its secure however it can meet any security compliance requirement if you put in the work. You can configure the infrastructure however you like. You need to know in-depth knowledge and how to configure all levels of your infrastructure 

#### describe hybrid cloud 
**Hybrid Cloud:** is using both On-Premise services and a Cloud Service** Provider. 
**Benefits:** It could be more cost-effective based on what you offload to the cloud. You have to secure your connection to the cloud which gives you the ability to meet all security requirements. You need to have in-depth knowledge and know how to configure all levels of your infrastructure and know the CSPs services.

#### compare and contrast the three types of cloud computing

### [Return to Table of Contents](README.md)
### [Cloud Concepts Resources](1-Cloud-Concepts\1-resources.md)