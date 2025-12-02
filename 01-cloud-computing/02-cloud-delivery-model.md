# Cloud Delivery Model


## 1. Infrastructure as a Service (IaaS)



### **Overview**

* Introduces IaaS along with PaaS and SaaS; covers architecture, pros/cons, SLA, and VPC.
  **Example:** A company shifting from physical servers to cloud infrastructure to reduce maintenance.



### **What is Infrastructure as a Service (IaaS)**

* Provides on-demand computing, storage, and networking; users manage software, provider manages hardware.
* Pay-as-you-go model.
  **Example:** Using Microsoft Azure Virtual Machines to host enterprise applications without buying servers.



### **IaaS Architecture**

* Provider manages servers, storage, networking, virtualization, and additional services like monitoring, security, and backups.
  **Example:** AWS offering EC2 instances with CloudWatch monitoring and automated backups.



### **Major IaaS Vendors and Products**

* Popular vendors: Amazon EC2, DigitalOcean, Azure VMs, MicroHost Cloud, Linode, Google Compute Engine.
  **Example:** A startup hosting its web app on DigitalOcean droplets for quick deployment.



### **Things to Consider While Choosing an IaaS Provider**

* **Security:** Strong security and disaster recovery.
* **Flexibility:** Easy scaling of resources.
* **Reliability:** Performance and low downtime.
  **Example:** A business choosing AWS for its proven uptime and global availability zones.



### **Service Level Agreements (SLA)**

* Defines expected performance, availability, and penalties.
* Essential for clarity and accountability between vendor and client.
  **Example:** An SLA guaranteeing 99.9% uptime for Azure Virtual Machines.



### **Virtual Private Cloud (VPC)**

* Private, isolated section of a public cloud with enhanced security.
* Supports storing data, running apps, hosting sites securely.
  **Example:** A bank using a VPC on Google Cloud to securely store financial transaction data.



### **Advantages of IaaS**

* Reduces physical infrastructure costs.
* Scalable and fast provisioning.
* Pay only for usage.
  **Example:** An e-commerce site scaling server capacity during festive sales and reducing it afterward.



### **Disadvantages of IaaS**

* Users must secure apps and data.
* May require complex integration.
* Costs can spike unexpectedly.
  **Example:** A company facing higher bills during unexpected traffic surges.



### **IaaS vs. SaaS vs. PaaS**

* **IaaS:** Raw computing resources.
* **PaaS:** Application development environment.
* **SaaS:** Ready-to-use cloud apps.
  **Example:**

  * IaaS → AWS EC2
  * PaaS → Google App Engine
  * SaaS → Salesforce



### **IaaS vs. Containers vs. Serverless**

* **Containers:** Lightweight, package app + dependencies.
* **Kubernetes:** Manages containerized workloads.
* **Serverless:** Provider handles scaling; no server management.
  **Example:** Deploying microservices using Docker containers and managing them with Kubernetes on GCP.



### **Conclusion**

* Recaps IaaS, related models, architecture, benefits, challenges, SLAs, and VPCs.
  **Example:** Organizations adopting IaaS to modernize their IT infrastructure while minimizing hardware overhead.




## 2. Product as a Services (PaaS)


### **Overview**

* PaaS lets users access cloud-based hardware and software to build applications without managing on-premise infrastructure.
  **Example:** A startup avoids buying servers by using a cloud platform to build apps.


### **What is Platform as a Service (PaaS)?**

* Cloud model where providers host the hardware/software needed for app development.
* Eliminates need for developers to set up their own infrastructure.
  **Example:** Using Google App Engine to deploy an app without installing servers.


### **PaaS Architecture**

* Functions as a workflow containing phases such as deployment, provisioning, lifecycle management, service management, and reporting.
  **Example:** Developers use automated deployment pipelines provided by a PaaS like Azure.


### **Characteristics of the PaaS Service Model**

* Integrates apps easily via web service interfaces.
* Provides browser-based development tools.
* Offers scalability and security features.
  **Example:** A team collaboratively edits app code through an online IDE provided by the PaaS.


### **How Does PaaS Work?**

* Delivered through a provider’s hosted infrastructure.
* Accessed mainly via a web browser.
* Supports Java development and app hosting on public, private, or hybrid clouds.
  **Example:** Using a browser to build and deploy Java apps on AWS Elastic Beanstalk.


### **Types of PaaS**

#### **Public PaaS**

* Hosted on public cloud; provider manages major IT components.
  **Example:** Deploying apps on Heroku.

#### **Private PaaS**

* Runs behind a company firewall for added security and control.
  **Example:** A bank uses a private PaaS hosted in its own data center.

#### **Hybrid PaaS**

* Combines benefits of both public and private PaaS.
  **Example:** A retail company keeps sensitive data in a private PaaS and scales apps in public PaaS.

#### **CPaaS**

* Enables real-time communication features like voice and video.
  **Example:** Adding video chat functionality using Twilio.

#### **mPaaS**

* Low-code tools for building mobile apps.
  **Example:** Building an app with no coding on an mPaaS like OutSystems.

#### **Open PaaS**

* Open-source collaboration tools (calendars, mail, etc.).
  **Example:** Using OpenPaas to build enterprise scheduling apps.

#### **iPaaS**

* Integrates different apps and workflows seamlessly.
  **Example:** Connecting Salesforce and SAP using an iPaaS.

#### **DBaaS**

* Cloud-hosted databases managed by the provider.
  **Example:** Using Amazon RDS for MySQL without managing the database manually.

#### **MWaaS**

* Provides middleware for connecting front-end and backend systems.
  **Example:** Using middleware to integrate mobile apps with internal APIs.

#### **Purpose-Built PaaS Types**

* **AIPaaS:** AI-focused development tools.
  **Example:** Using a platform to deploy ML models without managing GPUs.
* **cPaaS:** Communication APIs for apps.
  **Example:** Adding SMS verification using Twilio.
* **mPaaS:** Mobile development support.
  **Example:** Drag-and-drop mobile app building for e-commerce.


### **Popular PaaS Providers**

* Google Cloud, AWS, Microsoft Azure, IBM Cloud, Oracle Cloud Platform, Heroku, OpenStack, CloudStack, etc.
  **Example:** A company deploying microservices using Azure App Service.


### **What’s Included in a PaaS?**

* Infrastructure, OS, databases, dev tools, middleware, monitoring tools.
  **Example:** Developers using built-in compilers and debugging tools on a cloud IDE.



### **PaaS Examples**

#### **Microsoft Azure**

* Supports multiple programming languages and offers analytics + mobile services.
  **Example:** Hosting an ASP.NET app with auto-scaling.

#### **Heroku**

* Beginner-friendly platform with simple deployment from GitHub.
  **Example:** A student launches their first Python app using Heroku.

#### **AWS Lambda**

* Serverless functions, automated scaling, fully managed backend.
  **Example:** Triggering a Lambda function whenever a user uploads a file.

#### **Google App Engine**

* Highly scalable, serverless, supports many languages.
  **Example:** Auto-scaling a web app during high traffic.

#### **Dokku**

* Lightweight, docker-based, open-source PaaS.
  **Example:** A small team hosts apps on a low-cost private server using Dokku.

#### **Apprenda**

* Supports .NET and Java apps with automated governance.
  **Example:** Migrating an enterprise .NET application to a PaaS environment.

#### **Pivotal Cloud Foundry**

* Fast deployment, high scalability, strong app management.
  **Example:** A large enterprise deploys microservices with Cloud Foundry.


### **Things to Consider When Choosing a PaaS Provider**

* Identify business requirements beforehand.
* Evaluate provider strength, staffing, roadmap, and support.
  **Example:** A company checks Azure’s long-term roadmap before committing.


### **Advantages of PaaS**

* Easy to use, accessible from anywhere, includes development tools.
* Reduces capital costs with pay-as-you-go pricing.
  **Example:** A remote dev team collaborates on app development using a shared platform.


### **Disadvantages of PaaS**

* Vendor lock-in challenges.
* Service outages impact productivity.
* Platform changes may disrupt users.
  **Example:** Losing support for a programming language forces app migration.


### **Difference Between PaaS and iPaaS**

* **PaaS:** Provides tools + infrastructure for app development.
* **iPaaS:** Focuses on integrating different apps and data sources.
  **Example:** Using PaaS to build an app, and iPaaS to link it to CRM software.


### **Difference Between PaaS and Serverless Computing**

* PaaS offers more control over environment; scaling must be configured.
* Serverless scales automatically but gives less control.
  **Example:** Using PaaS for a customized environment and Serverless for event-based functions.


### **Conclusion**

* Summary of PaaS architecture, types, features, providers, pros/cons, and differences with iPaaS and serverless.
  **Example:** Businesses choose PaaS to speed up development while reducing infrastructure management.



---


## 3. Software as a Service (SaaS)


### **Overview**

* SaaS is a software delivery model where cloud providers host applications and make them available online.
* Common SaaS apps: Salesforce, Netflix, Zoom.
  **Example:** A company uses Zoom without installing anything locally—just logs in via a browser.



### **What is SaaS?**

* Cloud model where software is hosted by providers and accessed over the internet.
* Used by businesses, governments, professionals, and consumers.
* Marketed to both B2B and B2C users.
  **Example:** Netflix provides entertainment via the SaaS model to millions of users.



### **History and Future of SaaS**

* Originated in the 1960s with rented computing power by IBM.
* Evolved into modern cloud-hosted applications.
* SaaS continues to grow and hasn't reached its peak.
* Future uses include large-scale analytics, predictions, and automated business insights.
  **Example:** SaaS may help predict which customers might stop using a service.



### **SaaS Architecture**

* Uses a multi-tenant model where one application instance serves multiple clients.
* Each tenant’s data remains isolated and secure.
* Easy maintenance since updates apply to all users at once.
  **Example:** When a provider patches a security bug, all users receive the fix instantly.



### **Characteristics of SaaS**

* **Automated Provisioning:** Users get instant access; includes easy onboarding/offboarding.
  **Example:** A company adds new employees to a SaaS tool with a single click.
* **Multi-Tenancy:** One software instance serves many tenants with separate data.
  **Example:** Two companies using the same CRM but with isolated databases.
* **High Availability:** SaaS apps offer 24/7 access with health checks and strong SLAs.
  **Example:** A global team uses Salesforce at any time without downtime.
* **Subscription-Based Billing:** Pay monthly/annual fees instead of buying licenses.
  **Example:** Paying $12/user/month for a productivity tool.
* **Data Security:** Encryption, RBAC, CASB integration required.
  **Example:** Only authorized managers can access financial dashboards.
* **QoS:** Rate limiting ensures smooth performance for priority users.
  **Example:** A premium customer gets higher API limits.



### **How Does SaaS Work?**

* Providers host applications on their own or rented cloud infrastructure.
* Access happens via a browser—no installation required.
* Integrates with other tools via APIs.
  **Example:** A company connects its internal billing tool with a SaaS CRM through APIs.



### **SaaS Examples**

* **Salesforce:** Cloud CRM for managing leads and sales.
  **Example:** A sales team tracks all prospects in Salesforce.
* **Microsoft Office 365:** Cloud-based productivity suite.
  **Example:** Employees collaborate in real time on Word documents.
* **Google Workspace:** Includes Gmail, Docs, Sheets, Drive.
  **Example:** Teams co-edit spreadsheets in Google Sheets.
* **Netflix:** Subscription-based media streaming service.
  **Example:** Users watch shows on any device with an internet connection.
* **Zoom:** Video conferencing and webinar platform.
  **Example:** Companies host virtual meetings worldwide.
* **Slack:** Communication and collaboration app.
  **Example:** A team organizes discussions using multiple Slack channels.
* **Shopify:** SaaS e-commerce platform for online stores.
  **Example:** Small businesses build full online shops without coding.



### **Services Provided by SaaS Providers**

* **ERP:** Manages business operations like finance and supply chains.
  **Example:** A manufacturer tracks inventory and billing in an ERP SaaS.
* **Social Networking Services:** Manages large-scale user data.
  **Example:** Social apps store user profiles in cloud-based SaaS databases.
* **Customer Relationship Management (CRM):** Stores customer history and interactions.
  **Example:** A shop tracks repeat customers using a CRM.
* **Document Management & Mail Services:** Helps create, store, and send documents.
  **Example:** Using Zoho or Slack to manage shared files.



### **SaaS Pricing Models**

* **Flat Rate Pricing:** One product, one price.
  **Example:** A tool costs $30/month for all features.
* **Usage-Based Pricing:** Pay-as-you-go; cost rises with usage.
  **Example:** AWS charges based on data processed.
* **Tiered Pricing:** Different feature packages at different prices.
  **Example:** Basic, Pro, and Enterprise plans.
* **Per User Pricing:** Charge increases with number of users.
  **Example:** $10/user/month for each employee.
* **Per Active User Pricing:** Only pay for users who log in.
  **Example:** Only active staff accounts get billed.
* **Per Feature Pricing:** More features = higher cost.
  **Example:** Analytics and automation cost extra in higher tiers.



### **Advantages of SaaS**

* No need for local hardware or installations.
* Lower upfront and maintenance costs.
* Easy scalability for growing user bases.
* Integrates smoothly with other tools through APIs.
  **Example:** A startup adds 200 new users instantly without buying servers.



### **Disadvantages of SaaS**

* Limited control over features and functionality.
* Data security concerns due to cloud storage.
* Latency may occur when accessing remote resources.
  **Example:** Internet outage stops users from accessing the SaaS app.



### **Conclusion**

* Covered SaaS meaning, architecture, characteristics, services, pricing models, and pros/cons.
* SaaS remains a powerful cloud model for flexible, scalable, cost-effective software delivery.
  **Example:** Companies continue adopting SaaS to minimize IT overhead.


---

## 4. Function as a Service (FaaS)


### **Overview**

* FaaS (Function as a Service) allows developers to write and deploy functions without managing infrastructure.
* Part of serverless computing; triggers functions in response to events and auto-scales.
* Fast-growing market, expected to reach $24B by 2026.
  **Example:** A function runs only when a user uploads a file, then shuts down automatically.



### **Popular FaaS Platforms**

* IBM Cloud Functions
* AWS Lambda
* Google Cloud Functions
* Azure Functions
* OpenFaaS
  **Example:** AWS Lambda executes code whenever an API endpoint is called.



### **FaaS and Serverless**

* Serverless means infra and server management are hidden from the user.
* FaaS is a *subset* of serverless focused on event-driven function execution.
* You only pay when functions run—no cost during idle periods.
  **Example:** A button click triggers a function that validates a form; no server runs otherwise.



### **How FaaS Works**

* Based on microservices: an app is broken into small, independent functions.
* Server starts only when a function is triggered, executes code, then stops.
* Auto-scales and reuses resources efficiently.
  **Example:** A function runs only to process a login request, then shuts down instantly.



### **Dynamic Scaling with FaaS**

* Event-driven scaling: more incoming requests = more parallel function instances.
* Stateless: each function handles a single request.
* Cost-efficient—pay only for execution time.
  **Example:** A function scales from 1 to 1,000 instances during a flash sale automatically.



### **Benefits of FaaS**

* Focus only on writing code.
* Faster development and deployment.
* Auto-scaling handled by provider.
* Cost-efficient and lightweight.
* Supports multiple programming languages.
  **Example:** A developer deploys a Python function without configuring servers or VMs.



### **Principles and Best Practices**

* Write functions that perform a single action.
* Avoid calling other functions within a function.
* Use fewer libraries to reduce load time.
  **Example:** A function only sends a confirmation email—not processes payments too.



### **FaaS vs Serverless**

* Serverless covers databases, storage, DevOps, APIs, etc.
* FaaS focuses only on compute and executing code on demand.
* All FaaS is serverless, but not all serverless is FaaS.
  **Example:** Using a serverless database ≠ FaaS; but writing a function to update it = FaaS.



### **Use Cases of FaaS**

* **APIs:** Event-driven apps, REST APIs, user input validation.
  **Example:** A function verifies login credentials via API.
* **Multimedia/Data Processing:** Handles large inputs like images/videos.
  **Example:** A function resizes uploaded photos automatically.
* **IoT:** Devices send event triggers to execute logic.
  **Example:** A smart doorbell triggers a function to send phone alerts.



### **FaaS vs PaaS, Containers, and VMs**

* **Provisioning:** FaaS = milliseconds; others = minutes.
* **Administration:** FaaS requires no admin; VMs require full control.
* **Scalability:** FaaS scales instantly per request.
* **Availability:** Built-in high availability.
* **State:** FaaS functions are stateless.
* **Resource Use:** Allocated only on event trigger.
  **Example:** A VM must stay online all day, but a FaaS function runs only 50 ms per request.



### **Conclusion**

* FaaS lets developers focus on logic, not infra.
* Highly available, fault-tolerant, and auto-scaling.
* Supports any programming language.
* Useful in APIs, IoT, and data processing.
* Popular platforms include AWS Lambda, Azure Functions, Google Cloud Functions, etc.
  **Example:** A web app triggers FaaS functions for authentication, image processing, and notifications.



