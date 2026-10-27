<div align="center">

<img src="./assets/banner.svg" alt="Mihir Maurya - Cloud Solutions Architect & Enterprise DevSecOps" width="100%" />

<a href="https://readme-typing-svg.demolab.com/">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=20&pause=1200&color=00FF66&center=true&vCenter=true&width=900&height=50&lines=Cloud+Solutions+Architect+%7C+Enterprise+DevSecOps+%7C+Agentic+AI;Azure+CAF+Landing+Zones+%7C+Zero-Trust+Hub-and-Spoke+Topology;Secretless+CI%2FCD+with+OIDC+Workload+Identity+Federation;Model+Context+Protocol+(MCP)+%26+Autonomous+SRE+Agent+Swarms;174%2B+Production+Obsidian+Vault+Notes+%7C+400%2B+Architectural+Scenarios" alt="Animated DevSecOps headline" />
</a>

### ⚡ Enterprise Cloud Solutions Architect & DevSecOps Engineer | Agentic AI Systems

**Production Azure Infrastructure · Zero-Trust IaC · Shift-Left DevSecOps · Autonomous SRE Swarms**

[![Portfolio](https://img.shields.io/badge/Portfolio-mihirmaurya--dev.github.io-7B2CBF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://mihirmaurya-dev.github.io/)
[![Live Project](https://img.shields.io/badge/Live_Project-b18g119.online-00FF66?style=for-the-badge&logo=cloudflare&logoColor=0B0813)](https://b18g119.online)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mihirmauryaa1)
[![GitHub](https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MihirMaurya-dev?tab=repositories)
[![Control Plane](https://img.shields.io/badge/Status-Available_for_Senior_%26_Architect_Roles-00E5FF?style=for-the-badge&logo=opsgenie&logoColor=0B0813)](#-connect)

</div>

---

## 🛰️ Mission Control Telemetry Matrix

<div align="center">

| Subsystem | Telemetry Status | Architecture Standard | Gate Verification |
|:---|:---:|:---|:---:|
| ☁️ **Cloud Foundation** | `ONLINE` 🟢 | Azure Cloud Adoption Framework (CAF 3.0) | Multi-Subscription Hub & Spoke |
| 🛡️ **Supply Chain Security** | `ENFORCED` 🟢 | CIS Benchmark v2.0 · Checkov · tfsec | Automated Pre-Merge PR Gate |
| 🔑 **Identity & Access** | `SECRETLESS` 🟢 | Workload Identity Federation (OIDC) | Zero Static Service Principal Secrets |
| 🤖 **Agentic Incident AI** | `DEPLOYED` 🟢 | Model Context Protocol (MCP) · LangGraph | Self-Healing PR & Anomaly Triage |
| 📚 **Knowledge Repository** | `174+ RUNBOOKS` 🟢 | Markdown Obsidian Vault · 400+ Q&As | 16 Architecture Domains · ADR Engine |

</div>

---

## 🧑‍💻 Executive Summary

I am a **Cloud Solutions Architect and DevSecOps Engineer** specializing in enterprise-grade **Microsoft Azure platforms**, **Zero-Trust Infrastructure as Code (Terraform)**, and cutting-edge **Agentic AI systems (Model Context Protocol, RAG, and autonomous SRE operations)**.

Combining an analytical foundation in **Computer Applications & Mathematics (M.Sc Computer Science)** with intensive immersion in **DevOps Insiders (Batch 18)**, I engineer production platforms designed for high resilience, verifiable security compliance, and automated self-healing operations:

* ☁️ **Cloud Architecture & CAF Governance:** Architecting enterprise Hub-and-Spoke topologies, micro-segmented Virtual Networks, Route Tables with forced egress, Azure Firewall Premium, and production AKS clusters.
* 🛡️ **Shift-Left DevSecOps & Supply Chain:** Authoring 4-stage automated pipelines in Azure DevOps and GitHub Actions with secretless OIDC authentication, static code analysis (**Checkov**, **tfsec**, **TFLint**), secret scanning (**Gitleaks**, **TruffleHog**), and manual approval gates.
* 🤖 **Agentic AI & LLMOps:** Implementing **Model Context Protocol (MCP)** servers and **LangGraph** multi-agent swarms that ingest live infrastructure alerts, retrieve runbooks from vector stores, and autonomously generate remediation GitOps pull requests.
* 🧠 **Systemized Architectural Knowledge:** Architect of a **174+ note production-grade Obsidian Knowledge Vault** spanning 16 domains, 33 Azure services, 400+ scenario interview questions, and real-world Architecture Decision Records (ADRs).

---

## 🧭 Portfolio Delivery Architecture

```mermaid
flowchart TD
    subgraph Core["🏛️ Architecture & Governance"]
        A["Mihir Maurya Cloud Platform"] --> B["Azure CAF Landing Zones"]
        A --> C["Enterprise Hub & Spoke VNet"]
        A --> D["Agentic AI SRE & MCP Swarm"]
        A --> E["174+ Note Obsidian Vault"]
    end

    subgraph DevSecOps["🛡️ DevSecOps & Pipeline Gates"]
        B --> F["Terraform Modular IaC"]
        C --> F
        F --> G["Gitleaks & TruffleHog Scan"]
        G --> H["Checkov & tfsec CIS Gate"]
        H --> I["Azure DevOps / GitHub Actions OIDC"]
        I --> J["Environment Approval Gate"]
    end

    subgraph AI["🤖 Autonomous AI Operations"]
        D --> K["Model Context Protocol (MCP) Host"]
        E -.->|"Vectorized Runbooks"| L["RAG Incident Knowledge Base"]
        K --> L
        L --> M["LangGraph Self-Healing Agent"]
        M --> N["Automated GitOps Remediation PR"]
    end

    subgraph Runtime["☸️ Production Runtime"]
        J --> O["Zero-Trust Azure Runtime"]
        N --> O
        O --> P["Production AKS Platform"]
        O --> Q["Azure Firewall & Hub Peering"]
        O --> R["Key Vault Workload Identity"]
    end

    classDef purple fill:#1d0738,stroke:#9d4edd,stroke-width:2px,color:#fff;
    classDef matrix fill:#032111,stroke:#00ff66,stroke-width:2px,color:#fff;
    classDef cyan fill:#051b2e,stroke:#00e5ff,stroke-width:2px,color:#fff;
    classDef amber fill:#2d1900,stroke:#f59e0b,stroke-width:2px,color:#fff;

    class A,B,C,E purple;
    class F,G,H,I,J amber;
    class D,K,L,M,N cyan;
    class O,P,Q,R matrix;
```

---

## 🚀 Featured Enterprise Projects

---

### 1. 🕸️ [`azure-hub-spoke-architecture`](https://github.com/MihirMaurya-dev/azure-hub-spoke-architecture)

> **Enterprise Hub-and-Spoke Network Topology & CAF Segmentation via Modular Terraform**

[![Status](https://img.shields.io/badge/Status-Production_Ready-00FF66?style=flat-square&logo=azuredevops&logoColor=0B0813)](https://github.com/MihirMaurya-dev/azure-hub-spoke-architecture)
[![IaC](https://img.shields.io/badge/IaC-Terraform_Modular-7B2CBF?style=flat-square&logo=terraform&logoColor=white)](https://github.com/MihirMaurya-dev/azure-hub-spoke-architecture)
[![Security](https://img.shields.io/badge/Security_Scan-Checkov_CIS_Passed-00E5FF?style=flat-square&logo=bridgecrew&logoColor=0B0813)](https://github.com/MihirMaurya-dev/azure-hub-spoke-architecture)
[![Topology](https://img.shields.io/badge/Topology-Hub_%26_Spoke_CAF-1D0738?style=flat-square&logo=azureartifacts&logoColor=white)](https://github.com/MihirMaurya-dev/azure-hub-spoke-architecture)

| Architectural Dimension | Engineering Implementation |
|---|---|
| 🏢 **Hub Infrastructure** | Centralized VNet (`10.0.0.0/16`), `AzureFirewallSubnet`, `GatewaySubnet`, `BastionSubnet`, `ManagementSubnet`, and Private Key Vault |
| 🧪 **Spoke Segmentation** | Multi-environment isolation (`spoke-dev` at `10.1.0.0/16`, `spoke-prod` at `10.2.0.0/16`) interconnected via low-latency VNet Peering |
| 🛡️ **DevSecOps Simulation** | Custom PowerShell CI harness (`run-pipeline.ps1`) executing automated Checkov SAST, formatting checks, and plan artifact locking |
| 🔒 **State Decoupling** | Isolated remote state backends per environment in Azure Blob Storage to prevent concurrency conflicts and blast radiuses |

<div align="center">

[![Explore Codebase](https://img.shields.io/badge/Explore-Codebase_→-7B2CBF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MihirMaurya-dev/azure-hub-spoke-architecture)
[![Hub Deployment](https://img.shields.io/badge/Inspect-Hub_Deployment_→-00FF66?style=for-the-badge&logo=terraform&logoColor=0B0813)](https://github.com/MihirMaurya-dev/azure-hub-spoke-architecture/tree/main/terraform/environments/hub)
[![Network Modules](https://img.shields.io/badge/Inspect-Network_Modules_→-00E5FF?style=for-the-badge&logo=azureartifacts&logoColor=0B0813)](https://github.com/MihirMaurya-dev/azure-hub-spoke-architecture/tree/main/terraform/modules/network)
[![Pipeline Harness](https://img.shields.io/badge/Run-Pipeline_Simulator_→-1D0738?style=for-the-badge&logo=powershell&logoColor=white)](https://github.com/MihirMaurya-dev/azure-hub-spoke-architecture/blob/main/run-pipeline.ps1)

</div>

<details>
<summary><b>🔬 [INSPECT ARCHITECTURE SPEC] Multi-Tenant Hub-and-Spoke Topologies</b></summary>

```text
HUB-SPOKE/
├── azure-pipelines.yml       # 🔄 Azure DevOps Multi-Stage CI/CD pipeline
├── run-pipeline.ps1          # 🛠️ Shift-Left Checkov + Terraform execution harness
└── terraform/
    ├── environments/         # 🚀 ISOLATED STATE ROOT DEPLOYMENTS
    │   ├── hub/              # Central Hub: VNet (10.0.0.0/16), VPN GW, Key Vault
    │   ├── spoke-dev/        # Dev Workload VNet (10.1.0.0/16) -> Peered to Hub
    │   └── spoke-prod/       # Prod Workload VNet (10.2.0.0/16) -> Peered to Hub
    │
    └── modules/              # 🧩 REUSABLE TERRAFORM MODULES
        ├── key_vault/        # Private Key Vault with RBAC & Access Policies
        ├── network/          # Dynamic VNet/Subnet generator via for_each
        └── vpn/              # Enterprise Gateway & P2S / S2S VPN
```
</details>

---

### 2. 🛡️ [`master-devsecops-pipeline`](https://github.com/MihirMaurya-dev/master-devsecops-pipeline)

> **Enterprise 4-Stage Shift-Left Security, FinOps Cost Gating & Terraform CI/CD**

[![Orchestration](https://img.shields.io/badge/Orchestrator-Azure_DevOps_Pipelines-0078D7?style=flat-square&logo=azuredevops&logoColor=white)](https://github.com/MihirMaurya-dev/master-devsecops-pipeline)
[![Secret Scanning](https://img.shields.io/badge/Secret_Scan-Gitleaks_%26_TruffleHog-00FF66?style=flat-square&logo=github&logoColor=0B0813)](https://github.com/MihirMaurya-dev/master-devsecops-pipeline)
[![IaC Scanning](https://img.shields.io/badge/IaC_Security-tfsec_%26_Trivy-7B2CBF?style=flat-square&logo=terraform&logoColor=white)](https://github.com/MihirMaurya-dev/master-devsecops-pipeline)
[![FinOps](https://img.shields.io/badge/FinOps-Azure_Retail_Prices_API-00E5FF?style=flat-square&logo=microsoftazure&logoColor=0B0813)](https://github.com/MihirMaurya-dev/master-devsecops-pipeline)

| Pipeline Stage | Engineering Role & Gate Enforcement |
|---|---|
| **Stage 1: Plan & FinOps** | Terraform `init`, `fmt`, `validate`, `tflint`, compiles `tfplan`, and queries **Azure Retail Prices API** dynamically |
| **Stage 2: Security Scan** | Multi-engine scan: **Gitleaks** regex secrets, **TruffleHog** verified tokens, **tfsec** CIS tests, and **Trivy** misconfigurations |
| **Stage 3: Approval Gate** | Azure DevOps Environment Gate (`production-approval`) enforcing architectural reviewer signoff before deploy |
| **Stage 4: Immutable Apply**| Downloads and applies the verified `tfplan` artifact directly with zero runtime configuration drift |

<div align="center">

[![Explore Pipeline](https://img.shields.io/badge/Explore-Pipeline_Codebase_→-7B2CBF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MihirMaurya-dev/master-devsecops-pipeline)
[![Pipelines YAML](https://img.shields.io/badge/Inspect-Azure_Pipelines_YAML_→-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)](https://github.com/MihirMaurya-dev/master-devsecops-pipeline/blob/main/terraform-pipeline/azure-pipelines.yml)
[![Gitleaks Config](https://img.shields.io/badge/Inspect-Gitleaks_Policy_→-00FF66?style=for-the-badge&logo=github&logoColor=0B0813)](https://github.com/MihirMaurya-dev/master-devsecops-pipeline/blob/main/terraform-pipeline/.gitleaks.toml)

</div>

<details>
<summary><b>🔐 [INSPECT PIPELINE FLOW] 4-Stage Immutable CI/CD Lifecycle</b></summary>

```yaml
stages:
  - stage: Terraform_Plan
    jobs:
      - job: Plan_And_FinOps
        steps:
          - task: TerraformCLI@0 (init, validate, fmt -check)
          - task: PowerShell@2 (Query Azure Retail Prices API from tfplan JSON)
          - task: PublishPipelineArtifact (drop tfplan)

  - stage: DevSecOps_Security_Scan
    dependsOn: Terraform_Plan
    jobs:
      - job: Static_Analysis
        steps:
          - script: gitleaks detect --config .gitleaks.toml
          - script: trufflehog git file://. --only-verified
          - script: tfsec . --format junit --out tfsec-results.xml
          - script: trivy config . --severity CRITICAL,HIGH

  - stage: Production_Approval_Gate
    dependsOn: DevSecOps_Security_Scan
    jobs:
      - deployment: Human_Signoff
        environment: 'production-approval'

  - stage: Terraform_Apply
    dependsOn: Production_Approval_Gate
    jobs:
      - job: Apply
        steps:
          - task: DownloadPipelineArtifact (retrieve verified tfplan)
          - task: TerraformCLI@0 (apply tfplan)
```
</details>

---

### 3. 🤖 [`agentic-ai-devops`](https://github.com/MihirMaurya-dev/agentic-ai-devops)

> **Autonomous Incident Response & SRE Swarms driven by Model Context Protocol (MCP) & LangGraph**

[![Protocol](https://img.shields.io/badge/Standard-Model_Context_Protocol_(MCP)-00E5FF?style=flat-square&logo=anthropic&logoColor=0B0813)](https://github.com/MihirMaurya-dev/agentic-ai-devops)
[![Framework](https://img.shields.io/badge/Multi--Agent-LangGraph_Swarm-7B2CBF?style=flat-square&logo=chainlink&logoColor=white)](https://github.com/MihirMaurya-dev/agentic-ai-devops)
[![Pacing](https://img.shields.io/badge/Syllabus-16--Week_Engineering_Roadmap-00FF66?style=flat-square&logo=python&logoColor=0B0813)](https://github.com/MihirMaurya-dev/agentic-ai-devops/blob/main/agentic-ai-devops-16-week-roadmap.md)
[![Target](https://img.shields.io/badge/Target-Autonomous_SRE_%26_Self--Healing-1D0738?style=flat-square&logo=kubernetes&logoColor=white)](https://github.com/MihirMaurya-dev/agentic-ai-devops)

| Capability | Autonomous Agent Workflow |
|---|---|
| 🚨 **Telemetry Ingestion** | Ingests live Prometheus and Azure Monitor alert webhooks through an asynchronous event listener |
| 🔍 **Vector Runbook RAG** | Performs semantic chunking and dense vector queries against the 174+ note Obsidian knowledge vault |
| ⚡ **Tool Execution (MCP)** | Standardized Model Context Protocol servers securely invoke Azure RM & Kubernetes APIs without arbitrary bash scripts |
| 🛠️ **Self-Healing GitOps** | LangGraph cyclical state machine auto-drafts tested pull requests containing IaC resource fixes and Infracost diff calculations |

<div align="center">

[![Explore Agentic AI](https://img.shields.io/badge/Explore-Agentic_AI_Engine_→-7B2CBF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MihirMaurya-dev/agentic-ai-devops)
[![Roadmap Doc](https://img.shields.io/badge/Inspect-16--Week_Roadmap_→-00FF66?style=for-the-badge&logo=markdown&logoColor=0B0813)](https://github.com/MihirMaurya-dev/agentic-ai-devops/blob/main/agentic-ai-devops-16-week-roadmap.md)

</div>

---

### 4. 🧠 [`devops-knowledge-vault`](https://github.com/MihirMaurya-dev/DevOps-Notes)

> **Production-Grade Obsidian Knowledge Engine & Enterprise Architectural Runbooks**

[![Notes](https://img.shields.io/badge/Vault-174+_Evergreen_Notes-00FF66?style=flat-square&logo=obsidian&logoColor=0B0813)](https://github.com/MihirMaurya-dev/DevOps-Notes)
[![Domains](https://img.shields.io/badge/Coverage-16_Architecture_Domains-7B2CBF?style=flat-square&logo=obsidian&logoColor=white)](https://github.com/MihirMaurya-dev/DevOps-Notes)
[![Interview Q&A](https://img.shields.io/badge/Interview_Prep-400+_Architectural_Scenarios-00E5FF?style=flat-square&logo=azuredevops&logoColor=0B0813)](https://github.com/MihirMaurya-dev/DevOps-Notes)
[![Azure Services](https://img.shields.io/badge/Azure_Services-33_Deep_Dives-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)](https://github.com/MihirMaurya-dev/DevOps-Notes)

| Knowledge Domain | Content Breakdown & Architectural Value |
|---|---|
| 🏗️ **IaC & Terraform** | Deep dives into declarative theory, remote state lease-locking, custom modules, workspaces, and dynamic blocks |
| ☁️ **Azure Enterprise** | Comprehensive operational guides across 33 Azure services (AKS, VNet, PIM, Key Vault, Azure Firewall) |
| 🏢 **Landing Zone & CAF** | Complete mapping of enterprise workloads to Microsoft Cloud Adoption Framework pillars |
| 📋 **Decision Logs (ADRs)**| Architecture Decision Records articulating tradeoffs, security postures, and cost impacts |

<div align="center">

[![Explore Vault](https://img.shields.io/badge/Explore-Obsidian_Knowledge_Vault_→-7B2CBF?style=for-the-badge&logo=obsidian&logoColor=white)](https://github.com/MihirMaurya-dev/DevOps-Notes)
[![View Architecture Patterns](https://img.shields.io/badge/Inspect-Architecture_Patterns_→-00FF66?style=for-the-badge&logo=github&logoColor=0B0813)](https://github.com/MihirMaurya-dev/DevOps-Notes/tree/main/06-Architecture-Patterns)
[![View ADRs](https://img.shields.io/badge/Inspect-Architecture_Decision_Records_→-00E5FF?style=for-the-badge&logo=git&logoColor=0B0813)](https://github.com/MihirMaurya-dev/DevOps-Notes/tree/main/09-Decision-Logs)

</div>

<details>
<summary><b>📚 [INSPECT VAULT STRUCTURE] 16 Architecture Domains</b></summary>

| Index | Domain | Focus Areas |
|:---:|:---|:---|
| `01` | **Terraform** | HCL, State Locking, Custom Modules, Workspaces, Loops & Dynamic Blocks |
| `02` | **Azure** | 33 Services, AKS, VNet Peering, Private Endpoints, RBAC, Key Vault |
| `03` | **Landing Zone** | Microsoft CAF, Management Groups, Policy-as-Code, Subscription Design |
| `04` | **CI/CD** | Multi-Stage Pipelines, OIDC Workload Federation, Approval Gates, GitOps |
| `05` | **Linux** | Kernel Parameters, Systemd Services, Bash Scripting, Networking (iptables/ss) |
| `06` | **Architecture** | Hub-and-Spoke, Zero-Trust, Disaster Recovery (RTO/RPO), High Availability |
| `07` | **Interview Prep** | Scenario Whiteboarding, System Design Q&As, Troubleshooting Runbooks |
| `08` | **Real Builds** | Multi-Tier Enterprise Infrastructure, AKS Production Platforms |
| `09` | **Decision Logs** | Architectural Decision Records (ADR-001 through ADR-004) |
| `12` | **Agentic AI** | Model Context Protocol (MCP), ReAct Agents, LangGraph SRE Swarms |
| `14` | **Security** | Checkov, tfsec, TFLint, Gitleaks, Cosign, Trivy Vulnerability Scanning |
| `15` | **Cost Governance**| FinOps, Azure Cost Analysis, Resource Tagging, Infracost Budget Gates |

</details>

---

### 5. 🏛️ [`azure-caf-modular-iac`](https://github.com/MihirMaurya-dev/azure-caf-modular-iac)

> **Modular Azure Infrastructure as Code Framework · CAF Enterprise Blueprints & Multi-Tier Compute**

[![Platform](https://img.shields.io/badge/Platform-Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)](https://github.com/MihirMaurya-dev/azure-caf-modular-iac)
[![IaC](https://img.shields.io/badge/IaC-Terraform_Modular-7B2CBF?style=flat-square&logo=terraform&logoColor=white)](https://github.com/MihirMaurya-dev/azure-caf-modular-iac)
[![Security](https://img.shields.io/badge/Ingress-Azure_Bastion_Zero_Public_IP-00FF66?style=flat-square&logo=security&logoColor=0B0813)](https://github.com/MihirMaurya-dev/azure-caf-modular-iac)
[![Egress](https://img.shields.io/badge/Egress-NAT_Gateway_Static_IP-00E5FF?style=flat-square&logo=azureartifacts&logoColor=0B0813)](https://github.com/MihirMaurya-dev/azure-caf-modular-iac)

| Modular Component | Design Pattern & Security Boundary |
|---|---|
| 🔒 **Azure Bastion** | Secure browser-based TLS jumpbox connectivity eliminating the need for public IP addresses on VMs |
| 🛡️ **NAT Gateway** | Deterministic static IP egress for private subnets ensuring predictable external firewall allowlisting |
| 🌐 **Virtual Networks** | Parameterized address spaces with subnet slicing, NSG security associations, and route table definitions |
| 🚀 **Environment Tiers** | Pre-configured `Dev` and `Prod` environment directories ready for automated CI/CD deployment |

<div align="center">

[![Explore Modular IaC](https://img.shields.io/badge/Explore-Modular_IaC_Codebase_→-7B2CBF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MihirMaurya-dev/azure-caf-modular-iac)
[![Inspect Modules](https://img.shields.io/badge/Inspect-Reusable_Modules_→-00FF66?style=for-the-badge&logo=terraform&logoColor=0B0813)](https://github.com/MihirMaurya-dev/azure-caf-modular-iac/tree/main/modules)
[![Inspect Environments](https://img.shields.io/badge/Inspect-Environments_→-00E5FF?style=for-the-badge&logo=azureartifacts&logoColor=0B0813)](https://github.com/MihirMaurya-dev/azure-caf-modular-iac/tree/main/Environments)

</div>

---

### 6. 🏥 [`medikiosk-edge-platform`](https://github.com/MihirMaurya-dev/medikiosk-sih26047)

> **AI-Powered Clinical Intake & Triage Kiosk Platform (Smart India Hackathon SIH 2026)**

[![Hackathon](https://img.shields.io/badge/Hackathon-SIH_2026_Finalist-FF9800?style=flat-square&logo=hackerearth&logoColor=white)](https://github.com/MihirMaurya-dev/medikiosk-sih26047)
[![Backend](https://img.shields.io/badge/Framework-FastAPI_Async-009688?style=flat-square&logo=fastapi&logoColor=white)](https://github.com/MihirMaurya-dev/medikiosk-sih26047)
[![Multi-LLM](https://img.shields.io/badge/LLM_Engine-Groq_+_Gemini_Multimodal-00FF66?style=flat-square&logo=google&logoColor=0B0813)](https://github.com/MihirMaurya-dev/medikiosk-sih26047)
[![Protocol](https://img.shields.io/badge/Healthcare-ABHA_ID_+_SOAP_Notes-7B2CBF?style=flat-square&logo=health&logoColor=white)](https://github.com/MihirMaurya-dev/medikiosk-sih26047)

| Feature | System Engineering Detail |
|---|---|
| 🤖 **Multi-Provider Fallback** | Hybrid LLM routing: **Groq** for low-latency clinical dialogues and **Google Gemini** for multimodal document OCR |
| 📋 **Clinical Protocols** | Conducts dynamic clinical interviews (Allopathic SOCRATES & Ayurvedic Dashavidha Pariksha) with red-flag emergency detection |
| 🩺 **Real-Time Doctor Queue** | Reactive doctor dashboard displaying auto-generated structured S-O-A-P notes and instant approval feedback |

<div align="center">

[![Explore MediKiosk](https://img.shields.io/badge/Explore-MediKiosk_Platform_→-7B2CBF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MihirMaurya-dev/medikiosk-sih26047)
[![Architecture Document](https://img.shields.io/badge/Inspect-Architecture_Spec_→-00FF66?style=for-the-badge&logo=markdown&logoColor=0B0813)](https://github.com/MihirMaurya-dev/medikiosk-sih26047/blob/main/ARCHITECTURE.md)
[![Backend Modules](https://img.shields.io/badge/Inspect-FastAPI_Backend_→-009688?style=for-the-badge&logo=python&logoColor=white)](https://github.com/MihirMaurya-dev/medikiosk-sih26047/tree/main/backend)

</div>

---

## 🏛️ Architectural Decision Records (ADR Showcase)

Demonstrating the architectural rationale and risk-tradeoff evaluations applied across production environments:

| ADR ID | Decision Title | Architectural Choice & Tradeoff Rationale | Status |
|:---:|:---|:---|:---:|
| **ADR-001** | **Workload Identity (OIDC) vs Service Principals** | **Selected OIDC.** Eliminated long-lived client secrets stored in CI/CD variables; uses short-lived Azure AD tokens issued directly to GitHub/Azure DevOps runners. Eliminates credential leakage attack surface. | `ACCEPTED` 🟢 |
| **ADR-002** | **Central Hub-and-Spoke vs Full Mesh VNet** | **Selected Hub-Spoke.** Enforces all cross-environment and outbound egress through a centralized firewall with User Defined Routes (UDRs), avoiding complex N*(N-1)/2 mesh peering costs and lack of visibility. | `ACCEPTED` 🟢 |
| **ADR-003** | **Decoupled Remote States vs Monolithic State** | **Selected Decoupled State.** Split Hub, Spoke-Dev, and Spoke-Prod states into distinct Azure Blob containers with lease locking, preventing accidental blast radiuses and pipeline concurrency locks. | `ACCEPTED` 🟢 |
| **ADR-004** | **Model Context Protocol (MCP) for SRE AI** | **Selected MCP Standard.** Provides a standardized, sandboxed protocol for AI agents to invoke Azure CLI and Kubernetes tools with strict permission boundaries rather than unsafe bash scripts. | `ACCEPTED` 🟢 |

---

## 🧰 Technology & Tooling Matrix

<div align="center">

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=azure,terraform,kubernetes,docker,githubactions,git,linux,bash,powershell,python,postgres,prometheus,grafana&theme=dark&perline=7" alt="Tech Stack Icons" />
</a>

</div>

<br/>

| Domain | Enterprise Tools, Frameworks & Standards |
|:---|:---|
| ☁️ **Cloud Architecture** | Microsoft Azure, Hub-and-Spoke VNets, ExpressRoute / VPN GW, Azure Firewall, Private Endpoints, Azure Landing Zones (CAF), Azure Policy |
| 🏗️ **Infrastructure as Code** | Terraform, OpenTofu, Modular IaC, Azure Blob Remote State with Lease Locking, Dynamic `for_each` Subnet Generation, Drift Management |
| 🔄 **CI/CD & GitOps** | Azure DevOps Pipelines, GitHub Actions, Secretless OIDC Workload Identity, 4-Stage Gate Lifecycles, Environment Manual Approval Gates |
| 🛡️ **DevSecOps & Supply Chain** | Shift-Left Security, Checkov (CIS Microsoft Azure Benchmark), tfsec, Gitleaks, TruffleHog, TFLint, Prisma Cloud, HashiCorp Key Vault |
| 🤖 **Agentic AI & SRE** | Model Context Protocol (MCP), LangGraph, Vector Knowledge Bases (Qdrant/ChromaDB), ReAct Autonomous Loops, Self-Healing Incident Workflows |
| ☸️ **Containers & Platforms** | Azure Kubernetes Service (AKS), Docker, Helm 3, ACR, Key Vault CSI Driver, OIDC Workload Identity for Pods |
| 📊 **Observability & Ops** | Azure Monitor, Log Analytics (KQL), Prometheus, Grafana, OpenCost, Health Probes, Data Collection Rules (DCR) |
| 💻 **Systems & Scripting** | Linux (Ubuntu), Bash, PowerShell Core, Python 3, PHP 8, REST API Architecture, Git Workflows |

---

## 🔒 The Engineering Standard I Enforce

```
┌────────────────────────────────────────────────────────────────────────┐
│  1. ZERO-TRUST IDENTITY: No static passwords or client secrets in CI   │
│  2. IMMUTABLE IaC: All infrastructure versioned and drift-detected     │
│  3. SHIFT-LEFT GATES: Checkov & Gitleaks block vulnerabilities at PR   │
│  4. ARCHITECTURAL RIGOR: Every major design documented via an ADR      │
│  5. AUTONOMOUS RESILIENCE: AI agents augment SRE for rapid MTTR triage │
└────────────────────────────────────────────────────────────────────────┘
```

---

## 📈 Engineering Telemetry

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=MihirMaurya-dev&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="Mihir Maurya's GitHub Stats" width="48%" />
<img src="https://streak-stats.demolab.com?user=MihirMaurya-dev&theme=tokyonight&hide_border=true&background=0D1117&ring=9D4EDD&fire=00FF66&currStreakLabel=00FF66" alt="GitHub Streak" width="48%" />

</div>

<br/>

<div align="center">

[![Public Repos](https://img.shields.io/badge/Public_Repos-12-7B2CBF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MihirMaurya-dev?tab=repositories)
[![Obsidian Notes](https://img.shields.io/badge/DevOps_Notes-174+-00FF66?style=for-the-badge&logo=obsidian&logoColor=0B0813)](https://github.com/MihirMaurya-dev/DevOps-Notes)
[![Interview Scenarios](https://img.shields.io/badge/Architectural_Q%26A-400+-00E5FF?style=for-the-badge&logo=azuredevops&logoColor=0B0813)](https://github.com/MihirMaurya-dev/DevOps-Notes)
[![Location](https://img.shields.io/badge/Location-India-FF9800?style=for-the-badge&logo=googlemaps&logoColor=white)](https://mihirmaurya-dev.github.io/)

</div>

---

## 🤝 Let's Connect

I am actively open to discussions regarding **Cloud Solutions Architect**, **DevSecOps Engineer**, and **Agentic AI Platform** opportunities.

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-mihirmaurya--dev.github.io-7B2CBF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://mihirmaurya-dev.github.io/)
[![Live Project](https://img.shields.io/badge/Live_Project-b18g119.online-00FF66?style=for-the-badge&logo=cloudflare&logoColor=0B0813)](https://b18g119.online)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect_with_Mihir-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mihirmauryaa1)
[![Instagram](https://img.shields.io/badge/Instagram-@mihirmauryaa-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/mihirmauryaa/)
[![DevOps Vault](https://img.shields.io/badge/Obsidian-Explore_DevOps_Notes-9D4EDD?style=for-the-badge&logo=obsidian&logoColor=white)](https://github.com/MihirMaurya-dev/DevOps-Notes)

<br/><br/>

<img src="./assets/footer.svg" alt="Mihir Maurya Control Plane" width="100%" />

</div>
