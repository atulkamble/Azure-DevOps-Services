# 🚀 **Azure DevOps & DevOps-Related Services in Azure**

Azure provides a **full DevOps ecosystem** covering CI/CD, IaC, containers, monitoring, Git repos, security, and collaboration.

---

# 🔵 **1. Azure DevOps Services (Core DevOps Platform)**

### **1️⃣ Azure Repos**

* Git repositories (private)
* Branch policies, PR reviews
* CI/CD integration with Pipelines

### **2️⃣ Azure Pipelines**

* Build + Release pipelines
* YAML + Classic pipelines
* Supports multi-platform (Linux, Windows, macOS)
* Deploy to AKS, VMs, App Services, Functions, Containers

### **3️⃣ Azure Boards**

* Agile project management
* Epics → Features → User Stories → Tasks
* Backlog, Sprint planning, Kanban board

### **4️⃣ Azure Artifacts**

* Package registry
* Supports Maven, npm, NuGet, Python

### **5️⃣ Azure Test Plans**

* Manual + automated testing
* Bug reporting, UAT, traceability

---

# 🟦 **2. Azure DevOps Beyond Azure DevOps Services**

### **6️⃣ Azure Kubernetes Service (AKS)**

* Container orchestration
* Integrates with ACR, Pipelines, Monitor

### **7️⃣ Azure Container Registry (ACR)**

* Private Docker registry
* Supports build tasks, geo-replication

### **8️⃣ Azure App Service (Web Apps, API Apps)**

* Easy CI/CD integration
* Blue-Green deployments with slots

### **9️⃣ Azure Functions**

* Serverless CI/CD
* GitHub Actions / Azure Pipelines support

### **1️⃣0️⃣ Azure Virtual Machines**

* Used for self-hosted agents
* Useful for custom CI/CD workloads

---

# 🟩 **3. Infrastructure as Code (IaC) Services**

### **1️⃣1️⃣ Azure Resource Manager (ARM Templates)**

* JSON templates to deploy resources

### **1️⃣2️⃣ Bicep**

* Simplified ARM language
* Most recommended IaC for Azure now

### **1️⃣3️⃣ Terraform**

* Widely used IaC tool
* AzureRM provider to deploy any Azure resource

### **1️⃣4️⃣ Ansible**

* Configuration management
* Works with Azure modules (VMs, Networks, etc.)

---

# 🟧 **4. Monitoring & Observability**

### **1️⃣5️⃣ Azure Monitor**

* End-to-end monitoring solution
* Combined logs, metrics, alerts

### **1️⃣6️⃣ Log Analytics Workspace**

* Centralized logging
* Query using **KQL**

### **1️⃣7️⃣ Application Insights**

* Performance monitoring for apps
* Distributed tracing
* Alerts, dashboards

### **1️⃣8️⃣ Azure Dashboard**

* Custom monitoring dashboards

---

# 🟥 **5. Azure Security & Governance (DevSecOps)**

### **1️⃣9️⃣ Azure Key Vault**

* Secure secrets, keys, certificates
* Integrates with Pipelines, Functions, AKS

### **2️⃣0️⃣ Azure Policy**

* Enforce compliance rules
* Ex: block VMs without tags

### **2️⃣1️⃣ Azure Blueprints**

* Governance at scale
* Combine ARM templates + policies

### **2️⃣2️⃣ Defender for Cloud**

* Cloud security posture management (CSPM)
* Vulnerability scanning

---

# 🟫 **6. Code, CI/CD, Deployment Ecosystem Integrations**

### **2️⃣3️⃣ GitHub**

* GitHub Actions
* GitHub Packages
* GitHub Advanced Security (CodeQL)

### **2️⃣4️⃣ GitHub Actions for Azure**

* Deploy to AKS, ACR, App Service, Functions
* Replace Azure Pipelines for many teams

---

# 🟪 **7. Additional DevOps-Friendly Azure Services**

### **2️⃣5️⃣ Azure Automation**

* Runbooks, patching, workflows

### **2️⃣6️⃣ Azure Logic Apps**

* DevOps integrations (Slack, Teams, GitHub, Jira)

### **2️⃣7️⃣ Azure DevTest Labs**

* Quickly provision dev/test environments

### **2️⃣8️⃣ Azure Service Bus / Event Grid**

* Event-driven CI/CD automation

---

# 🎯 **Quick Revision**

| Category             | Azure Services                       |
| -------------------- | ------------------------------------ |
| **CI/CD**            | Azure Pipelines, GitHub Actions      |
| **Git Repos**        | Azure Repos, GitHub                  |
| **Project Tracking** | Azure Boards                         |
| **Artifacts**        | Azure Artifacts, GitHub Packages     |
| **IaC**              | ARM, Bicep, Terraform, Ansible       |
| **Containers**       | AKS, ACR, Container Apps             |
| **Monitoring**       | Monitor, App Insights, Log Analytics |
| **Security**         | Key Vault, Policy, Defender          |
| **Automation**       | Automation Account, Logic Apps       |

---
