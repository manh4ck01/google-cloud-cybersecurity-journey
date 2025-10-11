# Module 1: Introduction to Cloud Computing  
*Google Cloud Cybersecurity Certificate*

---

## 📘 Overview
Module 1 introduces the fundamentals of **cloud computing**, including its architecture, deployment models, and the core services offered by Google Cloud. The module emphasizes **security, scalability, and best practices** for managing cloud resources.  

This module sets the foundation for understanding how to **secure cloud environments** and prepare for more advanced cybersecurity topics.

> **Note:** Detailed notes for this module can be found in [notes.md](./notes.md).

---

## 🌐 Key Concepts

### 1. The Cloud’s Impact
- The cloud enables **on-demand access to computing resources** over the internet.
- It transforms how businesses and education operate by providing:
  - **Scalability**
  - **Global accessibility**
  - **Cost-efficiency**

### 2. Cloud Composition
- Cloud systems are made up of:
  - **Compute** (VMs, containers, serverless functions)
  - **Storage** (object, block, file)
  - **Networking** (VPCs, load balancers)
  - **Security layers** (IAM, encryption, logging)

### 3. Deployment Models
| Model        | Description |
|--------------|-------------|
| Public Cloud  | Shared infrastructure (e.g., GCP) |
| Private Cloud | Dedicated infrastructure for one organization |
| Hybrid Cloud  | Combination of public and private |
| Multi-Cloud   | Use of multiple cloud providers |

### 4. Google’s Trusted Infrastructure
- Global network with **high availability and redundancy**.
- **Zero Trust security model**.
- **Encryption** for data at rest and in transit.
- Compliance certifications like **ISO, SOC, GDPR**.

### 5. Cloud Benefits & Limitations
**Benefits:**  
- On-demand scalability  
- Cost-effective, pay-as-you-go pricing  
- Resilient architecture with redundancy  

**Limitations:**  
- Shared responsibility for security  
- Dependence on provider uptime  
- Data residency and regulatory considerations  

---

## 🖥️ Compute in the Cloud

### Virtualization
- Running **multiple virtual machines** on a single physical host.
- Enables resource isolation and flexible deployment.

### Serverless Computing
- No need to manage infrastructure.
- Functions run **only when triggered**.
- Examples: **Cloud Functions**, **Cloud Run**.

### Containerization
- Package apps with all dependencies.
- Deploy via **GKE (Google Kubernetes Engine)**.
- Supports **microservices architectures**.

---

## 🗄️ Cloud Storage
### Benefits
- Highly available and durable.
- Scalable and cost-efficient.
- Integrated security and access controls.

### Types of Storage
- **Object Storage:** Stores unstructured data (e.g., Cloud Storage).  
- **Block Storage:** Persistent storage for VMs (e.g., Persistent Disk).  
- **File Storage:** Managed file systems (e.g., Filestore).

---

## 🔑 Security Highlights
- Cloud security is a **shared responsibility** between provider and user.
- Principles learned in Module 1:
  - Use **least privilege access**.
  - Encrypt **data at rest** and **in transit**.
  - Monitor resources via **Cloud Logging** and **Cloud Monitoring**.

---

## 🏦 Scenario: Cymbal Bank
- Hands-on labs involve securing a banking workload in Google Cloud.
- Key learnings:
  - Identity and Access Management (IAM)
  - Protecting sensitive data
  - Implementing **basic cloud security controls**

---

## ✅ Key Takeaways
- Cloud computing provides **flexibility, efficiency, and security**.
- Understanding **compute, storage, and deployment models** is essential for cybersecurity.
- Google Cloud’s infrastructure is **trusted, resilient, and compliant**.
- Security in the cloud is a **continuous process**, starting with foundational knowledge.

> For full notes with examples and lab tips, see [notes.md](./notes.md).

---

## 🔗 References
- [Google Cloud Docs](https://cloud.google.com/docs)  
- [Google Cloud Security Overview](https://cloud.google.com/security)  
- Labs and hands-on exercises provided in Module 1

---

*Author: Makhosi Andile Surge*  
*Course: Google Cloud Cybersecurity Certificate*  
*Module: 1 — Introduction to Cloud Computing*
