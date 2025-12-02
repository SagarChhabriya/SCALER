# Module 1: Fundamentals of Cloud Computing


## 1. Introduction to Cloud Computing
  - distribution of computing resources as a service
  - cloud providers like GCP, AWS, Azure, and so on

### History

  - Client-Server: one of the initial models: the server-side houses all of the client's data and control. If a single user wants to access some data, they must first connect to the server before being granted access.
  - Distributed computing model: multiple computers were connected with the help of networking, making it possible for the users to share resources as needed.
	
But both these models had one or the other disadvantage associated with them. All these factors gave rise to what we know as the cloud computing model, which covers a lot of constraints that were present in the previous models. Below are the names of some cloud providers:

  - AWS: 2002, launched EC2 in 2006
  - GCP: 2009, 
  - Azure: 2009
  - Others: Alibaba, IBM, Oracle, and HP

### Characteristics of Cloud Computing

  - Acquiring resources as you go
  - High scalability
  - Statistics Generation
  - Resource Pooling


### Types of Cloud Computing

  - Public Cloud
  - Private Cloud
  - Hybrid Cloud
  - Community Cloud


#### Public Cloud

  - Less expensive compared to private and hybrid.
  - No worries about maintenance 
  - Integration is Simple
  - no cap on the number of users because it is open to everyone
  - Due to the internet-based nature of public cloud services, they are location agnostic.
  - security might be a concern since resources are shared publicly on public clouds, making them less secure.
  - The performance also depends on factors like the speed of the internet connection.
  - Ex: Google App Engine, AWS EC2, etc

#### Private Cloud

  - also known as internal or corporate clouds
  - Organizations use private clouds to operate their own data centers, either internally or through a third party.	
  - The National Institute of Standards and Technology (NIST) divides private clouds into the following categories based on location and management: On-premise private cloud and Outsourced private cloud.
  - The users benefit from a high level of security and privacy thanks to private clouds.
	

#### Community Cloud

  - To share information between an organization and a particular community
  - the community cloud is economical
  - It is more secure than a public cloud.
  - Community clouds are not an appropriate choice if there is no teamwork involved.
  - In terms of data storage and bandwidth, there always exists an upper cap as all community members share a set of resources.

#### Hybrid Cloud

  - Hybrid clouds are a combination of public and private clouds.
  - only users within the business can access services running on a private cloud, while anyone can access those running on a public cloud.
  - Ex: Office 365, Google Application Suite, Amazon Web Services
  - Hybrid clouds are beneficial for organizations that need more security than public clouds. 

#### Multi Cloud
Multi-cloud is a cloud computing paradigm where an organization uses a combination of clouds to distribute applications and services. These clouds can be two or more public clouds, two or more private clouds, or a combination of public, private, and edge clouds.


### Types of Cloud Services

  - IaaS (Infrastructure as a Service)
  - PaaS (Platform as a Service)
  - SaaS (Software as a Service)
  - Serverless
  - XaaS (Anything as a Service): refers to a broad class of cloud computing and remote access services
  

### Pros and Cons of Cloud Computing

  - fast and easier to retrieve saved information from anywhere at any time.
  - It is easier to obtain a backup when using cloud computing.
  - good internet connection and dominance of the cloud operator

### Risks Costs and Ethics in Cloud Computing

  - Security
  - Costs
  - Data Persistence





## 2. Virtualization in Cloud Computing and Types

Virtualization in cloud computing involves creating virtual versions of computing resources such as servers, storage, and networks, allowing multiple virtual instances to run on a single physical infrastructure.

This enables efficient resource utilization, scalability, and flexibility in deploying and managing applications in the cloud. Virtualization plays a pivotal role in optimizing hardware usage and enhancing the overall performance and cost-effectiveness of cloud services. In this article we will also see types of virtualization in cloud computing.

- Host Machine: The machine on which the virtual machine is going to be built is known as Host Machine.
- Guest Machine: The virtual machine is referred to as a Guest Machine.



### Benefits of Virtualization
- We can gain better performance and use resources more efficiently in existing computational resources using CPU utilization.
- Since virtual machines are logically separated from the host system and from each other, an attack on one won’t bring down the others. This lets us boost security and availability of VMs.
- We can run many VMs over the same host hardware. This lets us reduce the costs for operation and maintenance of hardware and software
- VMs provide better reliability and disaster recovery than traditional systems, hence letting us rest easy in terms of operation capabilities.
- Virtualization is also environment friendly, as lesser physical resources need to be consumed than a traditional network of a similar scale.

### Drawback of Virtualization

- Significant Initial Investment, Learning Curve for New Infrastructure, Data Security Concerns


### Characteristics of Virtualization

<img width="816" height="595" alt="image" src="https://github.com/user-attachments/assets/44f23915-bc30-4c65-91ff-5a3bbe4fd4db" />


- Managed Execution: Controls how programs run across different computer environments.
- Sharing: Lets multiple systems use the same host to save hardware and power.
- Aggregation: Combines several hosts to act as one single system.
- Emulation: Imitates another system so its programs can run on the host.
- Isolation: Virtualization keeps the VM separate from the host using a hypervisor (Virtual Machine Manager), preventing either from affecting or harming the other.
- Portability: Allows virtual machines to move and run on different hosts easily.

> Interview Point: Emulation vs Simulation

<img width="817" height="756" alt="image" src="https://github.com/user-attachments/assets/53a40b82-4586-41d3-9226-e615dac6a928" />


### Types of Virtualization

Six types of virtualization in cloud computing

#### **1. Application Virtualization**

Application virtualization allows users to access and use an application remotely from a central server.  
Instead of installing the software on a local computer, the application runs on a server, and the user interacts with it via the internet.

All the application data and configurations remain on the server, simplifying updates, security, and management.

**Example:**  
Microsoft Office 365 or Google Docs — you don’t install them locally; you use them online while the cloud server does the processing.

<img width="816" height="660" alt="image" src="https://github.com/user-attachments/assets/d48c0e67-9181-472e-9283-797fa7fd3a47" />



#### **2. Network Virtualization**

Network virtualization combines various network resources by dividing the available bandwidth into independent channels.  
Each virtual network can be assigned to different devices or applications, allowing multiple virtual networks to run simultaneously on one physical infrastructure.

This setup increases efficiency, flexibility, and network security.

**Example:**  
In an organization, the HR, Finance, and IT departments can each have their own virtual network, even though they share the same physical infrastructure.

<img width="816" height="1054" alt="image" src="https://github.com/user-attachments/assets/a9a8e1c2-eed6-4397-8950-dc004c86554b" />


Clients don’t see the complex physical network layout — to them, it appears as one large, unified network.


#### **3. Desktop Virtualization**

Desktop virtualization allows a user’s operating system (OS) to be hosted on a remote server and accessed from anywhere via the internet.  
This means users don’t need to store their OS or data locally and can access it from any device.

It also enables multiple operating systems to run on one device without rebooting.

**Example:**  
Using **Virtual Desktop Infrastructure (VDI)**, an employee can access their Windows desktop from a Mac, tablet, or thin client, all connecting to the same centralized server.

<img width="816" height="753" alt="image" src="https://github.com/user-attachments/assets/b58ad3c5-7f88-4859-b5f3-b9efc069b4ce" />

As shown above, the client interacts with a virtual desktop hosted on a remote server, enabling secure and flexible access.


#### **4. Storage Virtualization**

Storage virtualization combines multiple physical storage devices into a single, unified storage system.  
This allows users to store and retrieve data as if it were in one place, even though it may be distributed across multiple servers.

It simplifies management, improves performance, and increases storage efficiency.

**Example:**  
Cloud services like **Amazon S3** or **Google Drive** use storage virtualization to manage data across several servers while presenting it as one unified storage space.

<img width="816" height="928" alt="image" src="https://github.com/user-attachments/assets/a826acc0-ddeb-452a-880e-d97359ca55cb" />

The image shows data stored across multiple physical servers but appearing as one storage system to the user.


#### **5. Server Virtualization**

Server virtualization divides a single physical server into multiple smaller virtual servers.  
Each virtual server runs independently with its own operating system and resources.

This improves performance, reduces costs, and increases availability, as one virtual server failure doesn’t affect others.

**Example:**  
A single physical server can host several virtual machines — one running Windows for accounting, another Linux for web development, and another for hosting applications.

<img width="817" height="1088" alt="image" src="https://github.com/user-attachments/assets/c380668c-4b2a-4a28-b1cc-e0c91e584065" />


As seen above, multiple virtual servers process user requests, but it appears to the user as if one central server is handling everything.

#### **6. Data Virtualization**

Data virtualization provides a unified, virtual view of data from multiple sources.  
It allows users to access and analyze data without knowing where or how it is stored or processed.

This approach improves data accessibility, flexibility, and security.

**Example:**  
A company might have customer data in CRM, sales data in databases, and social data in analytics tools. Data virtualization lets analysts see all of this in one view without moving data physically.

<img width="816" height="1146" alt="image" src="https://github.com/user-attachments/assets/58da26e3-9167-4957-8714-f791733d0050" />

As shown, data producers (sources) and consumers (users) are separated — consumers can access data securely without knowing its origin.


- **Summary:**

| Type | Description | Example |
|------|--------------|----------|
| Application Virtualization | Run applications remotely on servers | Google Docs |
| Network Virtualization | Combine bandwidth into virtual networks | VLANs |
| Desktop Virtualization | Access desktop OS remotely | Virtual Desktop Infrastructure (VDI) |
| Storage Virtualization | Combine physical storage into one system | Amazon S3 |
| Server Virtualization | Split one physical server into multiple virtual servers | VMware, Hyper-V |
| Data Virtualization | Access data from multiple sources virtually | Denodo, TIBCO |



### Uses of Virtualization
- Efficient use of hardware resources
- Reduced IT costs
- Easy system backup and recovery
- Faster software testing and deployment
- Enhanced security through isolation
- Remote access and management
- Scalability and flexibility in cloud environments



## 3. Types of Cloud Computing Models
Four different types of cloud deployment models exist. These deployment models vary depending on how they are implemented, how they are hosted, and who has access to them. Although all cloud deployment options are based on the same virtualization idea (the separation of resources from bare metal infrastructure), they vary in terms of location, storage capacity, accessibility, and other factors. One should evaluate the various levels of security that Public, Private, Hybrid, and Community Clouds offer and the level of management necessary depending on the type of data you are working with.

<img width="3400" height="1742" alt="image" src="https://github.com/user-attachments/assets/5813b73a-6a9c-4b40-b715-e71bd1652ecd" />


### **Types of Cloud Computing Models**

Cloud computing provides computing resources like storage and servers over the internet. There are several types of cloud deployment models, each with its own purpose and benefits.

#### **1. Public Cloud**

* Managed by third-party providers (like AWS, Google Cloud, Azure).
* Shared by many users.
* Low cost, easy to use, but less secure.

#### **2. Private Cloud**

* Used by one organization only.
* Offers high security, control, and privacy.
* More expensive and needs skilled management.

#### **3. Hybrid Cloud**

* Combines public and private clouds.
* Offers flexibility, scalability, and better security.
* Useful for handling variable workloads.

#### **4. Community Cloud**

* Shared by organizations with common goals (like government or research).
* More secure than public clouds but less than private ones.
* Cost is shared among members.

#### **5. Multi-Cloud**

* Uses multiple cloud providers or platforms.
* Prevents vendor lock-in and improves flexibility.
* Common in large businesses.


### **Comparison**

| Feature     | Public   | Private         | Community       | Hybrid          |
| ----------- | -------- | --------------- | --------------- | --------------- |
| Security    | Low      | High            | Higher          | High            |
| Cost        | Cheapest | Expensive       | Shared          | Moderate        |
| Control     | Low      | High            | High            | High            |
| Ease of Use | Easy     | Needs expertise | Needs expertise | Needs expertise |


### **Choosing the Right Cloud**

When selecting a cloud provider, consider:

* **Certifications:** Check for security standards like ISO 27001.
* **Security:** Ensure encryption and data privacy.
* **Compatibility:** Provider should support your existing systems.
* **SLA:** Review uptime guarantees and support policies.
* **Exit Strategy:** Avoid vendor lock-in and ensure data portability.


### **Conclusion**

Cloud computing offers flexibility and scalability through different models—Public, Private, Hybrid, Community, and Multi-Cloud. Choosing the right one depends on your business size, budget, and security needs.
