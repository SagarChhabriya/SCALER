# Cloud Computing Platforms and Migration

## 1. Cloud Computing Platforms and Technologies


### **Overview**

* Cloud computing delivers computing resources (storage, servers, databases, software) as a service.
* Includes multiple cloud types such as public, private, and hybrid.
  **Example:** A company uses cloud storage instead of running its own data center.



### **Introduction to Cloud Computing Platforms**

* Cloud platforms are remote, internet-based systems that provide hardware + OS to run apps.
* Reduce need for physical data centers; businesses pay only for what they use.
  **Example:** A startup uses Google Cloud to host its database instead of buying servers.



### **Evaluating Cloud Platforms**

* Choosing the right cloud provider is essential due to a wide range of options.
* Key factors: Certifications, privacy, SLAs, performance, migration support, and roadmap.
  **Example:** A hospital checks HIPAA compliance before choosing a cloud provider.



### **SaaS-Based Platforms**

* SaaS delivers software over the internet; users access a single shared (multi-tenant) instance.
* Easy for providers to update and maintain all users at once.
  **Example:** Netflix provides the same version of its app to all users globally.



### **PaaS-Based Platforms**

* PaaS offers hardware + software tools for developing applications without managing infrastructure.
* Involves phases like deployment, provisioning, lifecycle management, and reporting.
  **Example:** Developers use Heroku (PaaS) to deploy a web app without configuring servers.



### **IaaS-Based Platforms**

* IaaS provides computing, storage, and networking resources on demand.
* Users manage OS and apps; provider manages hardware and virtualization.
  **Example:** A company spins up an Azure VM to run a custom Linux application.




### **Cloud Platforms by Proprietorship**

Clouds classified into Public, Private, and Hybrid based on ownership.

#### **Public Cloud**

* Accessible to everyone; operates on pay-per-use.
* Highly scalable and easy to integrate but may have security concerns.
  **Example:** A small business uses AWS EC2 to host its website.

#### **Private Cloud**

* Used exclusively by one organization; offers high security and control.
* Requires skilled staff and is costlier to operate.
  **Example:** A bank uses OpenStack to run a private cloud for secure financial data.

#### **Hybrid Cloud**

* Combines public + private clouds; balances flexibility and security.
* More complex to manage and depends on provider reliability.
  **Example:** A company stores sensitive data on a private cloud but uses Google Drive for general files.



### **Cloud Platform Technologies**

#### **AWS**

* Offers flexible, scalable IaaS services (e.g., EC2, S3).
* EC2 provides customizable virtual machines; S3 offers reliable storage.
  **Example:** A company stores backups in S3 and runs apps on EC2 instances.

#### **Microsoft Azure**

* Provides cloud OS and development platform with broad service options.
* Supports networking, caching, content delivery, and storage.
  **Example:** A business deploys its .NET application using Azure App Services.

#### **Google Cloud & Google AppEngine**

* User-friendly and security-focused; provides IaaS and PaaS solutions.
* AppEngine auto-scales apps based on demand.
  **Example:** An app automatically scales to handle traffic during a product launch.

#### **Hadoop**

* Open-source framework for processing massive data using the MapReduce model.
* Used heavily by companies like Yahoo.
  **Example:** A research lab uses Hadoop clusters to analyze large datasets.

#### **Salesforce / Force.com**

* Cloud-based platform for building enterprise applications.
* Offers ready-to-use components for business workflows.
  **Example:** A company builds a custom CRM module using Force.com.

#### **CloudLinux**

* A Linux-based OS for building private internal cloud infrastructure.
* Offers high control, customization, and security.
  **Example:** A hosting provider uses CloudLinux to isolate user accounts securely.

#### **IBM Cloud**

* Offers SaaS, PaaS, and IaaS with flexible, cost-effective pricing.
* Provides easy API-driven deployment.
  **Example:** An enterprise uses IBM Cloud’s AI tools for internal automation.


### **Conclusion**

* Cloud platforms provide access to resources like servers, storage, and networking.
* Choosing the right provider is crucial for scalability and reliability.
* Cloud service models include SaaS, PaaS, and IaaS.
* Cloud ownership models include Public, Private, and Hybrid.
  **Example:** An organization combines SaaS (email), IaaS (VMs), and a hybrid cloud strategy for efficiency.



## 2. Cloud Migration





### **Overview**

* Cloud migration = moving data, workloads, apps, or IT resources to cloud infrastructure.
* Requires careful planning and reliable tools for error-free migration.
  **Example:** A company moves its finance application from on-prem servers to AWS.



### **What is Cloud Migration?**

* Moving assets from on-premises or outdated infrastructure to the cloud (or between clouds).
* May involve moving all or selected components.
  **Example:** Migrating only customer data to the cloud while keeping internal tools on-prem.



### **Seven-Step Model of Cloud Migration**

#### **1. Assessment**

* Evaluate challenges across application code, architecture, configuration, and pricing.
  **Example:** Running a POC to check if an app works on Azure before committing.

#### **2. Isolating**

* Identify all system and environment dependencies.
  **Example:** Listing libraries an app relies on before moving it.

#### **3. Mapping**

* Decide which components stay on-prem and which move to cloud.
  **Example:** Keeping databases locally but shifting the frontend to the cloud.

#### **4. Re-Architect**

* Redesign parts of the application for cloud compatibility.
  **Example:** Converting a monolithic service into microservices.

#### **5. Augment**

* Add cloud-native capabilities to enhance the app.
  **Example:** Integrating auto-scaling capability once in the cloud.

#### **6. Validate**

* Test and validate cloud components with a full test suite.
  **Example:** Running load tests on migrated APIs.

#### **7. Optimization**

* Iterate and re-optimize based on test results.
  **Example:** Tuning cloud VM sizes after performance testing.



### **Cloud Migration Planning**

#### **Why to Migrate**

* Define purpose, goals, and KPIs for cloud adoption.
  **Example:** Migrating to reduce infrastructure costs by 40%.

#### **What to Migrate**

* Identify interdependencies, migration order, ROI, and rewrite requirements.
  **Example:** Migrating the CRM first because it has fewer dependencies.

#### **Migrating to the Cloud**

* Start with simple, low-risk workloads; test thoroughly before shutdown.
  **Example:** First moving an internal intranet app to gain confidence.

---

### **Cloud Migration Strategies**

#### **Lift and Shift (Rehosting)**

* Move applications with minimal changes; fast but not cloud-optimized.
  **Example:** Moving existing VMs directly to AWS EC2.

#### **Move and Improve (Replatforming)**

* Adds some cloud-native features without rewriting entire apps.
  **Example:** Migrating to cloud and enabling auto-scaling without code changes.

#### **Rip and Replace (Refactoring)**

* Rebuild the workload to be fully cloud-native; high effort but high reward.
  **Example:** Rewriting a legacy app into a serverless architecture.

---

### **Cloud Migration Tools and Services**

#### **AWS Migration Tools**

* Supports quick and continuous database migration with minimal downtime.
  **Example:** Using AWS DMS to replicate a production database to the cloud.

#### **Corent SurPaaS**

* Helps package apps for SaaS and manage tenants.
  **Example:** A vendor converts its desktop app into a SaaS product.

#### **Carbonite Migrate**

* Reduces migration risks with repeatable processes and near-zero downtime.
  **Example:** Migrating critical workloads between data centers safely.

#### **Turbonomic**

* Automates hybrid-cloud workload optimization.
  **Example:** Detecting resource hotspots via visual mapping.

#### **Velostrata**

* Offers real-time migration and rollback capabilities.
  **Example:** Rolling back an app to on-prem after failed migration tests.

#### **Cloudscape**

* Helps plan cloud migration by analyzing data distribution and costs.
  **Example:** Identifying which apps would save the most money on cloud.

#### **VMware**

* Uses analytics to align infrastructure with business goals.
  **Example:** Applying policies to ensure optimized cloud performance.

---

### **Cloud Migration Trends**

#### **Alignment of Human Interests and Technology**

* Human factors + tech needs accelerate cloud adoption.
  **Example:** Remote work during COVID pushing businesses to cloud solutions.

#### **Migration Inspires Modernization**

* Lift-and-shift alone isn’t enough; modernization is needed to unlock value.
  **Example:** Refactoring apps after migration to use microservices.

#### **Data Migration for Analytics**

* Companies move data to use BI and advanced analytics cloud tools.
  **Example:** Migrating sales data to BigQuery for real-time dashboards.

#### **Distributed Computing**

* Modern apps leverage multi-cloud and edge computing.
  **Example:** Deploying workloads across AWS + Azure for best-of-breed services.

---

### **Pre and Post Challenges of Cloud Migration**

#### **Lack of Proper Strategy**

* Missing planning leads to failures.
  **Example:** Migrating apps without checking dependencies.

#### **Downtime**

* Network outages can cause data loss during migration.
  **Example:** A failed sync leading to corrupted files.

#### **Skills Gap**

* IT teams may lack cloud skills or certifications.
  **Example:** Security misconfigurations due to inexperienced staff.

#### **Bandwidth Issues**

* Poor bandwidth planning causes latency and slow user experience.
  **Example:** A SaaS app slowing down due to low cloud bandwidth allocation.

---

### **Benefits of Cloud Migration**

#### **Elasticity & Scalability**

* Scale resources automatically as demand changes.
  **Example:** Traffic spikes on an e-commerce site handled by autoscaling.

#### **Cost Cutting**

* Pay only for what you use; no spending on hardware or maintenance.
  **Example:** Eliminating physical server purchase cycles.

#### **Agility & Flexibility**

* Rapid deployment, remote access, and multi-location operations.
  **Example:** Launching a new service in hours instead of weeks.

#### **OpEx over CapEx**

* Shifts spending to operational expenses; improves cash flow.
  **Example:** Paying monthly for cloud servers instead of buying hardware.

#### **Security & Compliance**

* Cloud providers offer advanced security controls and compliance options.
  **Example:** Using built-in encryption to protect sensitive data.

#### **Reliability & Performance**

* High uptime, disaster recovery, global networks.
  **Example:** Automatic failover during outages.

#### **Low Maintenance**

* Cloud provider handles hardware and system updates.
  **Example:** No need to maintain server rooms or cooling systems.


### **Conclusion**

* Cloud migration involves moving digital assets to the cloud for scalability, performance, and efficiency.
* Success requires proper planning, talent, and strategy.
* Strategies include rehosting, replatforming, and refactoring.
* Cloud boosts accessibility, performance, and modernization capabilities.


