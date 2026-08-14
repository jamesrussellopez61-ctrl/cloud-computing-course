# Cloud Platform Comparison & Analysis

## Cloud Platform Comparison Matrix

| Feature / Metric | Amazon Web Services (AWS) | Microsoft Azure | Google Cloud Platform (GCP) |
| :--- | :--- | :--- | :--- |
| **Launch Year** | 2006 | 2010 | 2008 |
| **Compute Service** | Amazon EC2 | Azure Virtual Machines | Compute Engine |
| **Storage Service** | Amazon S3 | Azure Blob Storage | Google Cloud Storage |
| **Database Service** | Amazon RDS / DynamoDB | Azure SQL / Cosmos DB | Cloud Spanner / Bigtable |
| **Identity Service** | AWS IAM | Microsoft Entra ID (Azure AD) | Google Cloud IAM |
| **Primary Strength** | Broadest features & market maturity | Enterprise & Microsoft stack integration | Data analytics, AI/ML & Kubernetes |
| **Ideal Target Org** | Startups to large enterprises | Microsoft-centric enterprise orgs | Data-heavy orgs & AI innovators |

---

## Service Category Matching Table (Checkpoint 5)

| Service Category | AWS Equivalent | Azure Equivalent | GCP Equivalent |
| :--- | :--- | :--- | :--- |
| **Virtual Machines** | Amazon EC2 | Azure VMs | Compute Engine |
| **Object Storage** | Amazon S3 | Azure Blob Storage | Google Cloud Storage |
| **Relational Database**| Amazon RDS | Azure SQL Database | Cloud SQL |
| **Kubernetes Hosting** | Amazon EKS | Azure AKS | Google GKE |
| **Serverless Functions**| AWS Lambda | Azure Functions | Cloud Functions |

---

## Comparative Analysis Questions

1. **How do pricing models differ across AWS, Azure, and GCP?**  
   All three platforms utilize pay-as-you-go pricing models with options for reserved instances or committed use discounts for long-term workloads. AWS offers extensive Spot Instances and Savings Plans, Azure provides significant cost savings via Azure Hybrid Benefit for existing Windows/SQL licenses, and GCP features automatic Sustained Use Discounts without requiring upfront commitments.

2. **Which platform provides the best integration for existing enterprise Microsoft environments, and why?**  
   Microsoft Azure provides the best integration due to its native compatibility with Windows Server, Active Directory (Entra ID), and Microsoft 365. Organizations running legacy Microsoft infrastructure can migrate seamlessly with existing software licenses, minimizing reconfiguration overhead and identity management friction.

3. **In what scenarios would GCP be the clear choice over AWS or Azure?**  
   GCP is the primary choice for organizations heavily focused on modern data analytics, artificial intelligence, and containerized microservices. Its industry-leading BigQuery platform, native Kubernetes support (GKE), and advanced Vertex AI suite make it superior for high-throughput data processing and machine learning workflows.

4. **Why might an enterprise adopt a multi-cloud strategy despite the operational complexity?**  
   Enterprises adopt multi-cloud strategies to prevent vendor lock-in, maximize resilience through redundant disaster recovery across providers, and leverage best-of-breed services from each cloud. Additionally, multi-cloud setups help meet strict regional data sovereignty regulations and optimize overall IT spend.
