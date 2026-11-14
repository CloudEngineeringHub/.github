<div align="center">

<!-- Modern Cloud Native Organization Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,5,15,30&height=240&section=header&text=⚡%20CLOUD%20ENGINEERING%20HUB%20⚡&fontSize=48&fontAlignY=36&desc=Enterprise%20Cloud%20Architecture%20%7C%20Infrastructure%20as%20Code%20%7C%20Zero-Trust%20DevSecOps&descAlignY=58&descFontSize=18&animation=twinkling" width="100%" alt="CloudEngineeringHub - Enterprise Cloud & Platform Engineering" />

# ☁️ Welcome to **CloudEngineeringHub**

### 🚀 **Open Platform Engineering, Modular Infrastructure as Code & Zero-Trust Cloud Architecture**

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=0078D4&center=true&vCenter=true&width=920&lines=Enterprise+Cloud+Foundations+on+Microsoft+Azure;Modular+Infrastructure+as+Code+with+Terraform+%26+Terragrunt;Hardened+Kubernetes+(AKS)+%26+Zero-Trust+Workload+Identity;Shift-Left+DevSecOps+Pipelines+(Checkov%2C+Trivy%2C+GitLeaks);Enterprise+Hub-and-Spoke+Networking+%26+Private+Endpoints;Standardized+CI%2FCD+Workflows+for+Azure+DevOps+%26+GitHub+Actions)](https://git.io/typing-svg)

<p align="center">
  <a href="https://github.com/CloudEngineeringHub"><img src="https://img.shields.io/badge/GitHub_Org-CloudEngineeringHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Org" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Platform-Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure Platform" /></a>
  <a href="#"><img src="https://img.shields.io/badge/IaC-Terraform_Modular-844FBA?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform IaC" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Security-Zero--Trust_DevSecOps-107C41?style=for-the-badge&logo=auth0&logoColor=white" alt="Zero Trust" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Architecture-Cloud_Adoption_Framework-00A4EF?style=for-the-badge" alt="CAF" /></a>
  <a href="#"><img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License" /></a>
</p>

<!-- Quick Navigation Bar -->
<p align="center">
  <a href="#-about-cloudengineeringhub"><b>About Us</b></a> •
  <a href="#-core-platform-engineering-pillars"><b>Core Pillars</b></a> •
  <a href="#-organization-ecosystem-architecture"><b>Architecture Map</b></a> •
  <a href="#-featured-repositories-directory"><b>Repositories</b></a> •
  <a href="#-production-engineering-standards"><b>Standards</b></a> •
  <a href="#-leadership--maintainers"><b>Maintainers</b></a>
</p>

---

### 🌐 *"Engineering Deterministic, Resilient & Audit-Ready Cloud Platforms Through Code, Security & Automation"*

</div>

<br/>

## 📖 About CloudEngineeringHub

**CloudEngineeringHub** is an open platform engineering initiative dedicated to architecting, packaging, and maintaining **production-grade enterprise cloud foundations on Microsoft Azure**.

Our mission is to bridge the gap between ad-hoc cloud provisioning and **deterministic, auditable, enterprise-scale platform engineering**. Every repository under this organization is designed to adhere strictly to:
- 🏛️ **Microsoft Cloud Adoption Framework (CAF)** and Azure Well-Architected Framework (WAF).
- 🔒 **Zero-Trust Security & CIS Azure Foundations Benchmarks v2.0**.
- ⚙️ **Declarative, Modular Infrastructure as Code (IaC)** with remote state locking and automated drift detection.
- 🔄 **Shift-Left DevSecOps Continuous Delivery** with integrated vulnerability scanning, policy enforcement, and FinOps budget guardrails.

---

## 🏛️ Core Platform Engineering Pillars

```
                           [ CloudEngineeringHub Platform Ecosystem ]
                                                │
         ┌──────────────────────────────┬───────┴───────┬──────────────────────────────┐
         ▼                              ▼               ▼                              ▼
 [ Modular IaC & Modules ]     [ Enterprise Network ]  [ DevSecOps & Governance ]  [ CI/CD Workflows ]
  • Parametric Blueprints       • Hub-and-Spoke CAF     • Shift-Left Security Scans • Multi-Stage YAML
  • Azure Blob State Locking    • Azure Firewall IDPS   • Checkov / tfsec / Trivy   • Approval PR Gates
  • Semantic Versioning         • UDR Forced Egress     • GitLeaks Secret Scanner   • Progressive Delivery
  • Zero Configuration Drift    • Private Link Perim    • Infracost FinOps CI       • Automated Rollbacks
```

- ☁️ **Enterprise Cloud Foundations:** Complete architectural blueprints for multi-tier workloads, multi-AZ Kubernetes (AKS) clusters, distributed caching, and zone-redundant databases.
- 🧩 **Standardized Terraform Modules:** Reusable, parameterized Terraform modules with strict input validation, outputs encapsulation, and isolated Azure Blob storage backend locking.
- 🛡️ **Zero-Trust DevSecOps:** Security is a continuous automated pipeline gate. We eliminate static credentials using Azure Workload Identity and Azure Key Vault CSI secret auto-rotation.
- 🌐 **Modern Network Architecture:** Non-overlapping RFC 1918 CIDR IPAM, Hub-and-Spoke virtual networks, Azure Firewall Premium deep packet inspection, and Private Link isolation.
- 🔄 **Production-Ready CI/CD Workflows:** Scalable pipeline definitions and reusable GitHub Actions / Azure DevOps templates with automated PR quality checks and blue-green deployments.

---

## 🗺️ Organization Ecosystem Architecture

The following diagram illustrates how the repositories within **CloudEngineeringHub** interconnect to form an end-to-end, enterprise-scale cloud engineering foundation:

```mermaid
flowchart TD
    subgraph ModulesTier ["🧩 Reusable Module Catalog (terraform-modules)"]
        ModNet["Modular VNet & Subnet Blocks"]
        ModSec["Modular NSGs & Firewall Rules"]
        ModPaaS["Modular Private PaaS & Key Vault"]
    end

    subgraph NetworkTier ["🌐 Advanced Network Foundation (azure-networking-lab)"]
        HubVNet["🛡️ Central Hub VNet (10.100.0.0/16)\nAzure Firewall Premium & Bastion"]
        SpokeVNet["📦 Spoke VNets (10.101.0.0/16)\nIsolated Workload Segments"]
        UDR["🔀 UDR Forced Tunneling (0.0.0.0/0 -> FW)"]
    end

    subgraph InfraTier ["🏗️ Production Core (azure-terraform-infrastructure)"]
        AKS["☸️ Azure Kubernetes Service (AKS) Multi-AZ"]
        PaaS["🗄️ Zone-Redundant PostgreSQL Flexible Server"]
        PE["🔐 Private Endpoints (Zero Public Exposure)"]
    end

    subgraph SecurityTier ["🛡️ Security & Quality Gates (devsecops-tools)"]
        GitLeaks["🔑 GitLeaks Secret Scanner"]
        Checkov["🛡️ Checkov & tfsec IaC Linter"]
        Trivy["🐳 Trivy Container CVE Scanner"]
        Infracost["💰 Infracost Cloud FinOps CI Gate"]
    end

    subgraph PipelineTier ["🔄 Delivery Automation (pipeline_workflows)"]
        PRCheck["🔍 PR Validation & Quality Gate"]
        TFPlan["📋 Terraform Plan Artifact Generation"]
        ApprovalGate{"🛑 Production CAB Approval"}
        TFApply["🚀 Terraform Apply (Blob Lease Lock)"]
    end

    ModulesTier --> NetworkTier
    ModulesTier --> InfraTier
    NetworkTier <== "VNet Peering & Egress Inspection" ==> InfraTier
    SecurityTier --> PipelineTier
    PipelineTier -->|Provision & Validate| NetworkTier
    PipelineTier -->|Deploy & Scale| InfraTier
```

---

## 📂 Featured Repositories Directory

<table width="100%">
  <thead>
    <tr>
      <th width="35%">Repository</th>
      <th width="45%">Description &amp; Key Architectural Features</th>
      <th width="20%">Tech Stack</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <b>🏗️ <a href="https://github.com/CloudEngineeringHub/azure-terraform-infrastructure">azure-terraform-infrastructure</a></b>
      </td>
      <td>
        Enterprise production Azure infrastructure orchestrated via declarative Terraform. Implements multi-tier application architectures, multi-AZ AKS compute, zone-redundant storage, and Azure Blob remote state lease locking.
      </td>
      <td>
        <img src="https://img.shields.io/badge/Terraform-1.5+-844FBA?style=flat-square&logo=terraform&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/Azure-Production-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/IaC-State_Locking-107C41?style=flat-square" />
      </td>
    </tr>
    <tr>
      <td>
        <b>🛡️ <a href="https://github.com/CloudEngineeringHub/devsecops-tools">devsecops-tools</a></b>
      </td>
      <td>
        Comprehensive DevSecOps automation suite providing shift-left security scripts, CIS Azure Benchmark compliance checkers, Checkov/tfsec scanning configs, GitLeaks secret detection, and Trivy container vulnerability gates.
      </td>
      <td>
        <img src="https://img.shields.io/badge/Security-DevSecOps-107C41?style=flat-square&logo=auth0&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/Scan-Checkov_&_Trivy-2496ED?style=flat-square" /><br/>
        <img src="https://img.shields.io/badge/Compliance-CIS_Benchmark-red?style=flat-square" />
      </td>
    </tr>
    <tr>
      <td>
        <b>🌐 <a href="https://github.com/CloudEngineeringHub/azure-networking-lab">azure-networking-lab</a></b>
      </td>
      <td>
        Modular, hands-on enterprise networking lab implementing Hub-and-Spoke topology, Azure Firewall Premium with IDPS/TLS inspection, Azure Bastion zero-public-IP access, User-Defined Routes (UDR), and Private Link perimeters.
      </td>
      <td>
        <img src="https://img.shields.io/badge/Networking-Hub_&_Spoke-0078D4?style=flat-square" /><br/>
        <img src="https://img.shields.io/badge/Firewall-Premium_IDPS-red?style=flat-square" /><br/>
        <img src="https://img.shields.io/badge/Zero_Trust-Private_Link-black?style=flat-square" />
      </td>
    </tr>
    <tr>
      <td>
        <b>🧩 <a href="https://github.com/CloudEngineeringHub/terraform-modules">terraform-modules</a></b>
      </td>
      <td>
        Standardized, reusable, enterprise-grade Terraform modules published with semantic versioning. Covers VNets, Subnets, NSGs, AKS Nodepools, Azure SQL, Key Vault, and NAT Gateways with built-in input validation.
      </td>
      <td>
        <img src="https://img.shields.io/badge/Terraform-Reusable_Modules-844FBA?style=flat-square&logo=terraform&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/Versioning-SemVer_v1.0-orange?style=flat-square" /><br/>
        <img src="https://img.shields.io/badge/Quality-tflint_Validated-blue?style=flat-square" />
      </td>
    </tr>
    <tr>
      <td>
        <b>🔄 <a href="https://github.com/CloudEngineeringHub/pipeline_workflows">pipeline_workflows</a></b>
      </td>
      <td>
        Production-tested CI/CD pipeline definitions and reusable GitHub Actions / Azure DevOps workflows. Includes automated linting, security scanning, Infracost budget diffs, manual approval gates, and blue-green deployments.
      </td>
      <td>
        <img src="https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/CI%2FCD-Azure_Pipelines-0078D4?style=flat-square&logo=azure-devops&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/FinOps-Infracost-28A745?style=flat-square&logo=infracost&logoColor=white" />
      </td>
    </tr>
  </tbody>
</table>

---

## 🛡️ Production Engineering Standards We Enforce

Every codebase hosted under **CloudEngineeringHub** must adhere to the following non-negotiable engineering principles:

1. **Zero Out-of-Band Portal Changes:** 100% of cloud resources must be managed via declarative code. Nightly scheduled drift detection jobs trigger instant alerts if manual changes occur.
2. **Zero Plaintext Secrets:** Passwords, API tokens, and connection strings are strictly prohibited in repositories. Applications authenticate using Microsoft Entra ID Managed Identities and dynamic Azure Key Vault CSI secret rotation.
3. **Shift-Left Security as a PR Gate:** Pull requests are automatically blocked from merging if Checkov, tfsec, or Trivy detect High or Critical security vulnerabilities.
4. **FinOps Cost Consciousness:** Every infrastructure change PR includes an automated Infracost summary calculation showing the exact monthly financial impact before approval.
5. **High Availability & Disaster Recovery:** All production-grade architectures are designed with Multi-AZ redundancy and clear RTO (&lt; 15m) / RPO (&lt; 5m) disaster recovery runbooks.

---

## 👥 Leadership & Maintainers

**CloudEngineeringHub** was founded and is actively maintained by:

<div align="center">

<p align="center">
  <b>Neetu Patel</b><br/>
  <i>Senior DevOps Engineer &amp; Azure Cloud Platform Architect</i><br/>
  <a href="https://github.com/patelneetu10-stack"><img src="https://img.shields.io/badge/GitHub-%40patelneetu10--stack-181717?style=flat-square&logo=github&logoColor=white" alt="Neetu's GitHub" /></a>
  <a href="https://linkedin.com/in/patelneetu10"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="Neetu's LinkedIn" /></a>
  <a href="mailto:patel.neetu10@gmail.com"><img src="https://img.shields.io/badge/Email-patel.neetu10%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Neetu's Email" /></a>
</p>

</div>

---

## 🤝 Contributing & Community

We welcome contributions, issues, and discussions from fellow DevOps and Cloud Engineers!

- 🐛 **Found a bug or drift issue?** Please open an issue in the respective repository.
- 💡 **Have an architecture suggestion?** Submit a PR following our standard branch protection and commit conventions.
- ⭐ **Support the initiative:** If you find these architectures and modules helpful, please leave a star on our repositories!

<br/>

<div align="center">

<!-- Modern Waving Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,5,15,30&height=100&section=footer" width="100%" alt="Footer Wave" />

</div>
