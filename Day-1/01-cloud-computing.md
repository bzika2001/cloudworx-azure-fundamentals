# Cloud Concepts - Principles of cloud computing

## What is cloud computing?

Cloud computing is a technology that enables users to **access and use computing resources**, such as servers,storage, and applications, over the internet. Instead of owning and maintaining physical hardware, users can leverage remote servers hosted in **data centers** to store data, run applications, and perform various computing tasks.However, typically they include:

- **Compute power** - such as Linux servers or web applications
- **Storage** - such as files and databases
- **Networking** - such as secure connections between the cloud provider and your company
- **Analytics** - such as visualizing telemetry and performance data


**Data center**
: In the context of Microsoft Azure, data centers are geographically clustered, purpose-built facilities that house the critical infrastructure required to deliver Azure's cloud services.

Think of them as the physical homes for all the computers, storage, and networking equipment that make up Microsoft's Azure cloud services.

Imagine giant warehouses filled with super-powerful computers all connected together. These aren't just any computers; they're specifically designed to run cloud services, keep your data safe, and make sure everything works reliably.

**Here's a simple way to understand them:**

**Physical Buildings**: Azure data centers are actual buildings located around the world. Microsoft doesn't usually share the exact addresses for security reasons.  

**Packed with Hardware**: Inside, you'll find thousands upon thousands of servers, along with cooling systems, power supplies, and networks.  

**Foundation of Azure**: When you use an Azure service, like creating a virtual machine or storing a file, that's happening on the hardware inside one of these data centers.

## Why are they important?

**Global Reach**: Azure has data centers in many different regions around the world (including one right here in Johannesburg, South Africa!). This means you can choose to have your data and applications close to your users, making things faster. 

**Reliability**: Microsoft designs these data centers with lots of backup systems for power, cooling, and internet connections. This helps ensure your services stay online even if there's a problem.   

**Security**: Security is a big deal! Azure data centers have strict security measures to protect the physical hardware and your data. 

Think of it like this: if Azure was a giant city, the data centers would be the power plants, libraries, and office buildings that keep everything running smoothly!

## [Benefits of cloud computing](https://docs.microsoft.com/en-us/learn/modules/principles-cloud-computing/3-benefits-of-cloud-computing)

| Benefit | Description |
| -----------------------|:----------- |
| **It's cost-effective**| Pay-as-you-go or consumption-based pricing model|
| **It's scalable** |  You can scale up (increase resources) or scale out (add more instances) |
| **It's elastic**       | Dynamic scaling|
| **It's current**       | Maintained and upgraded by the cloud provider|
| **It's reliable**      | Fault tolerance                                                          |
| **It's global**        | Fully redundant datacenters located in various regions all over the globe|
| **It's secure**        | Broad set of policies, technologies, controls, and expert technical skills|

### Advantages of Azure
1. High Availability
2. Scalability
3. Agility
4. Global Reach
5. Elasticity
6. Fault Tolerance
7. Customer Latency
8. Predictive cost analysis
9. Security
    
### 1. High Availability
Azure ensures your applications are always up and running. It achieves this through Availability Zones, which are physically separate datacenters within an Azure region.

**Example**: If one datacenter experiences a power outage, your application continues to run on the other zone.

### 2. Scalability
Azure allows you to easily adjust your resources to meet demand. You can scale up (increase resources) or scale out (add more instances).

    - **Vertical scaling**, also known as "scaling up", is the process of adding resources to increase the power of an existing server.
    - **Horizontal scaling**, also known as "scaling out", is the process of adding more servers that function together as one unit.
    
**Example**: An e-commerce website can automatically add more servers during a flash sale.
Azure offers both Horizontal and Vertical scaling.

### 3. Agility
Azure enables you to deploy and manage applications quickly.

**Example**: A company can rapidly deploy a new version of its application to capture a market opportunity.
Azure supports DevOps practices for faster development cycles.

### 4. Global Reach
Azure has a vast network of datacenters around the world.

**Example**: You can deploy your application in multiple regions to serve users globally.
Azure ExpressRoute Global Reach allows you to create private networks between your on-premises networks.

### 5. Elasticity
Azure automatically adjusts resources based on demand, so you only pay for what you use.

**Example**: An application can automatically scale up during peak hours and scale down during off-peak hours.

### 6. Fault Tolerance
Azure is designed to withstand failures.

**Example**: If a server fails, Azure automatically fails over to another server.
Azure uses techniques like mirroring and parity to protect data.

### 7. Customer Latency
Azure offers features to minimize latency for your users.

**Example**: You can deploy your application in regions close to your users.
Azure provides tools to measure and monitor network latency.

### 8. Predictive Cost Analysis
Azure provides tools to help you understand and predict your cloud spending.

**Example**: Azure Cost Analysis allows you to visualize spending trends, allocate costs, and set budgets.

### 9. Security
Azure offers a comprehensive suite of security features.

**Example**: Azure Security Center helps you manage your security posture and protect against threats.
Azure includes features for identity and access management, network security, and data encryption.
