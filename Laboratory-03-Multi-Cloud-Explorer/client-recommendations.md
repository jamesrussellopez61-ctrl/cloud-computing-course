# Client Cloud Recommendations & Decision Matrix

## Client Recommendations

### Client A: Fast-Growing Tech Startup
* **Recommended Provider**: AWS
* **Justification**: AWS offers an extensive ecosystem of developer tools, vast community resources, and generous startup credit programs (AWS Activate). Its pay-as-you-go scaling allows rapid MVP development with minimal initial infrastructure overhead.
* **3 Recommended Services**: Amazon EC2, Amazon S3, AWS Lambda

### Client B: Enterprise University with Microsoft Stack
* **Recommended Provider**: Microsoft Azure
* **Justification**: The university already relies on Microsoft tools and Active Directory, making Azure the most cost-effective and operationally seamless fit. They can utilize Azure Hybrid Benefit to lower licensing costs and easily integrate student/faculty identity management.
* **3 Recommended Services**: Azure Virtual Machines, Azure SQL Database, Microsoft Entra ID

### Client C: AI Research Lab
* **Recommended Provider**: Google Cloud Platform (GCP)
* **Justification**: GCP provides industry-leading infrastructure tailored for machine learning, high-performance computing, and massive data processing. Custom TPU hardware and specialized AI frameworks give researchers a distinct computational edge.
* **3 Recommended Services**: Compute Engine (with GPUs/TPUs), Vertex AI, Google BigQuery

### Client D: Global E-Commerce Retailer
* **Recommended Provider**: AWS (or Multi-Cloud AWS + GCP)
* **Justification**: E-commerce requires maximum global availability, fault tolerance, and rapid auto-scaling during traffic spikes (e.g., peak sales events). AWS’s massive global availability zone footprint and proven track record with retail backbones guarantee uptime.
* **3 Recommended Services**: Amazon CloudFront, Amazon Aurora, AWS Auto Scaling

---

## Multi-Cloud Decision Matrix

| Requirement / Scenario | Recommended Cloud Provider | Key Reason |
| :--- | :--- | :--- |
| **Startup / Rapid Scaling** | AWS | Massive service catalog & global developer adoption |
| **Existing Microsoft Stack** | Azure | Native Active Directory & license cost savings |
| **AI / ML & Big Data** | GCP | Best-in-class tools (BigQuery, Vertex AI, TPUs) |
| **Global High-Availability Retail** | AWS | Unmatched infrastructure scale & edge locations |
