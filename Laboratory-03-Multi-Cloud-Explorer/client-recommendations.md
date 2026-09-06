# Cloud Platform Recommendation Challenge

## Checkpoint 4: Client Scenario Analysis

### Client A – Startup Company
* **Recommended Cloud Platform:** Google Cloud Platform (GCP)
* **Justification:** I would choose Google Cloud Platform for this startup because it fits their limited budget perfectly with its per-second billing system and generous free tier options. As the mobile application grows, GCP will allow the team to scale up resources automatically without needing massive upfront investments. The platform is also very developer-friendly, meaning a small startup team can launch their app backend quickly and focus on code instead of complex server management.
* **Three (3) Recommended Services:** 
  * Google App Engine (To easily deploy the app backend)
  * Firebase (For mobile app databases, authentication, and hosting)
  * Google Compute Engine (Scalable virtual machines for custom tasks)

---

### Client B – University
* **Recommended Cloud Platform:** Microsoft Azure
* **Justification:** I recommend Microsoft Azure for the university because it integrates natively with the tools they already use, like Windows Server, Microsoft 365, and Active Directory. Migrating to Azure means they will not have to rebuild their entire student and staff user management system from scratch. It also allows them to set up a hybrid cloud environment effortlessly, keeping sensitive local records secure while moving web services to the cloud.
* **Three (3) Recommended Services:**
  * Microsoft Entra ID (For managing user accounts and single sign-on access)
  * Azure Virtual Machines (To migrate and run their existing Windows Servers)
  * Azure SQL Database (For hosting administrative databases and student records)

---

### Client C – AI Research Company
* **Recommended Cloud Platform:** Google Cloud Platform (GCP)
* **Justification:** For an AI research firm that needs high-performance computing, I believe GCP is the absolute best choice. Google designed and built specialized custom hardware called TPUs which are engineered specifically to accelerate machine learning and deep learning training workloads. This gives the company the massive computing power they need for heavy mathematical simulations, allowing them to spin up big clusters on-demand and delete them when the research tasks are finished.
* **Three (3) Recommended Services:**
  * Cloud GPUs & Cloud TPUs (Hardware accelerators for deep learning models)
  * Vertex AI (An end-to-end data platform to build, train, and test AI models)
  * Google Cloud Storage (High-speed storage to hold massive research datasets)

---

### Client D – Global E-Commerce Company
* **Recommended Cloud Platform:** Amazon Web Services (AWS)
* **Justification:** I highly recommend AWS for this multinational online store because its massive global footprint is built to handle global retail operations. Since AWS grew out of Amazon's own e-commerce needs, its auto-scaling features and traffic distribution tools are highly dependable and mature. It offers resilient multi-region setups that ensure the shopping website stays online even during massive traffic surges like global holiday sales events.
* **Three (3) Recommended Services:**
  * Amazon EC2 Auto Scaling (To dynamically adjust server count based on shopper traffic)
  * AWS Application Load Balancer (To distribute international shopping traffic efficiently)
  * Amazon Aurora (A high-performance, globally distributed relational database)

---

## Checkpoint 6: Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
| :--- | :--- | :--- |
| **Startup Company** | Google Cloud Platform | It has low startup costs, great developer tools, and scales flexibly as the app grows. |
| **Enterprise Organization** | Amazon Web Services | It provides the most comprehensive catalog of stable, mature enterprise tools globally. |
| **Microsoft Environment** | Microsoft Azure | It offers native, hassle-free sync with existing Windows Servers and Office 365. |
| **AI / Machine Learning** | Google Cloud Platform | It gives researchers native access to advanced Google TPUs and Vertex AI pipelines. |
| **Kubernetes Deployment** | Google Cloud Platform | Google invented Kubernetes, making their container engine the most reliable and native. |
| **Global Web Application** | Amazon Web Services | Built on an infrastructure designed to handle massive, multi-region retail scales safely. |
