![Exam AZ-900](../images/az900.png "Exam AZ-900")
## Shared Responsibility Model in Azure

The shared responsibility model in **cloud computing** is a framework that outlines the division of **security responsibilities** between **service provider (CSP) and its customers**. It's a collaborative effort to ensure the overall security of the cloud environment.
![Shared Responsibility Model Exam AZ-900](../images/shared-responsibility.svg )

### When using a cloud provider, you’ll always be responsible for:

- The information and data stored in the cloud
- Devices that are allowed to connect to your cloud (cell phones, computers, and so on)
- The accounts and identities of the people, services, and devices within your organization
### The cloud provider is always responsible for:

- The physical datacenter
- The physical network
- The physical hosts
### Your service model will determine responsibility for things like:

- Operating systems
- Network controls
- Applications
- Identity and infrastructure

Brainstormer
Okay, let's brainstorm another analogy for the Shared Responsibility Model in Azure! Ho w about thinking aboutrenting an apartment? 🏢

Imagine you've just moved into a new apartment:

- **The Landlord (Microsoft Azure)**: The landlord owns the building and is responsible for the security of the building.  This includes:  
     - **Physical Security**: They make sure the building has secure doors, locks on the main entrances, and maybe even security cameras. They're responsible for the foundation and structure.
     - **Utilities**: They provide the basic infrastructure like electricity, water, and maybe internet access up to a certain point.
     - **Common Areas**: They maintain the security and upkeep of hallways, elevators, and other shared spaces.
       
- **You (the Customer)**: As the renter, you are responsible for the security in your apartment. This includes:

     - **Your Belongings**: Keeping your valuables safe inside your unit.
     - **Your Locks**: Making sure your apartment door is locked.
     - **Your Guests**: Being responsible for who you let into your space.
     - **How You Use Utilities**: Not doing anything inside that might compromise the building's systems.
- Just like with Azure, the level of your responsibility can change:

    - **Renting an Empty Apartment (IaaS - Virtual Machines)**: You have more control and responsibility. You need to furnish it, set up your own security inside, and manage most things within your walls.
     - **Renting a Furnished Apartment (PaaS - App Service)**: The landlord provides more – furniture, appliances. You still need to keep your belongings safe and use everything responsibly.
   - **Staying in a Hotel (SaaS - Microsoft 365)**: The hotel provides almost everything. You're mainly responsible for your personal safety and how you use the provided services.
   - 
Why does this analogy work?

It highlights that even though you're using a service provided by someone else, you still have a significant role in maintaining security and using the resources responsibly. The landlord (Azure) provides a secure foundation, but you (the customer) need to secure what you put inside and how you operate within that space.
