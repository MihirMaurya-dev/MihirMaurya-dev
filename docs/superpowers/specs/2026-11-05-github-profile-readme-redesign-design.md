# GitHub Profile README Redesign - Design Document

**Date:** 2026-11-05  
**Author:** Antigravity (Pair Programming with Mihir Maurya)  
**Status:** In Review / Ready for Approval  
**Target Repository:** `MihirMaurya-dev/MihirMaurya-dev` (`D:\DEV_OPS\profile-README\README.md`)

---

## 1. Intent and Why

Mihir Maurya's current GitHub Profile README relies on simulated "Mission Control Telemetry Matrix" tables with green lights, synthetic status indicators (e.g. `HASH: 0x9D4E...SEC`, `CONTROL PLANE: ONLINE`), and an inflated title ("Enterprise Solutions Architect") that detracts from real technical credibility. Furthermore, it contains projects that are outside his primary career direction (such as `medikiosk-sih26047`, an AI healthcare kiosk) and note-taking repositories (`DevOps-Notes`), while under-representing his actual, high-quality Azure cloud infrastructure and DevSecOps engineering repositories.

The goal is to completely redesign `README.md` into an authentic, high-impact, professional engineering showcase. It positions Mihir accurately and credibly as a **Cloud & DevSecOps Engineer** who builds real, production-patterned Azure infrastructure, zero-trust Terraform IaC, automated shift-left security pipelines, and modern agentic SRE tooling.

---

## 2. Goals, Non-Goals, and Anti-Goals

### Goals
- Present Mihir Maurya unmistakably as a **Cloud & DevSecOps Engineer**.
- Lead with verified technical rigor: Azure CAF landing zone design, Hub-and-Spoke networking, dynamic CI/CD pipelines, and shift-left security scanning.
- Highlight 4 core flagship repositories with clear architectural breakdowns, problems solved, and direct links to code:
  1. `azure-hub-spoke-architecture`
  2. `Master_PipeLine`
  3. `master-devsecops-pipeline`
  4. `azure-caf-modular-iac`
- Provide concise secondary highlights for:
  - `agentic-ai-devops` (MCP + LangGraph autonomous incident triage)
  - `genesis-iac-security-framework` (Custom Gitleaks regex rules & TFLint)
  - `azure-devops-iis-automation` (Self-hosted agent CI/CD with .NET/IIS)
- Include a categorized, verified Technology Stack (Azure, Terraform, Docker, Kubernetes, Linux, GitHub Actions, Azure DevOps, Python, Bash, Security tools).
- Articulate core engineering principles (Secretless OIDC, immutable tfplan, PR security gates, decoupled state).
- Provide a clean, unified Repository Directory table indexing his public repositories with real descriptions and links.
- Ensure professional formatting, mobile responsiveness, and high signal-to-noise ratio readable in under 60 seconds.

### Non-Goals
- Redesigning the web portfolio (`D:\DEV_OPS\Portfholio\index.html`) during this step (user explicitly said "first GitHub Profile README").
- Modifying underlying code in any of the external project repositories.
- Adding complex animated GIFs or heavy external assets that slow down GitHub page rendering.

### Anti-Goals (What MUST NOT be included)
- **NO INVENTED CLAIMS OR BUZZWORDS:** Absolutely no fake telemetry (e.g. "Mission Control Telemetry Matrix: ONLINE 🟢", "NODE ID: AZ-CENTRAL", "HASH: 0x9D4E...SEC").
- **NO INFLATED TITLES:** Do not use "Enterprise Principal Cloud Solutions Architect" or claim 10+ years of enterprise production maintenance.
- **REMOVE `medikiosk-sih26047`:** Explicitly requested to be removed by user.
- **REMOVE `DevOps-Notes` (174-note Obsidian vault):** Explicitly requested to be removed by user.
- **NO BROKEN LINKS OR BADGES:** Every repository link, workflow badge, or asset link must resolve to a valid target.

---

## 3. Constraints

- **Platform:** GitHub Profile README markdown format, rendered natively on GitHub web and mobile clients.
- **Asset Paths:** Local assets referenced in the README must exist in the repository (e.g. `./assets/banner.svg`). If updating `banner.svg`, ensure it aligns with the "Cloud & DevSecOps Engineer" title and contains no fake telemetry strings.
- **Badge Stability:** Badges must use reliable sources (`shields.io`, `skillicons.dev`, or native GitHub Actions badges) without broken parameters.

---

## 4. Approaches Considered & Selection

### Approach 1: The Production Architecture Showcase (SELECTED)
- **Description:** A balanced, comprehensive engineering profile that pairs Azure cloud architecture with end-to-end DevSecOps automation. Features 4 flagship repositories with architecture summaries, secondary specialized builds, engineering standards, and a clean repository directory.
- **Trade-offs:** Detailed enough to give hiring managers immediate technical proof, while maintaining high readability.
- **Selection Reason:** User selected Approach 1. It directly validates both sides of the "Cloud & DevSecOps Engineer" identity with real code and architectural patterns.

### Approach 2: The DevSecOps & Security Specialist
- **Description:** Heavily focused on pipeline hardening, SAST, secret detection, and pre-commit hooks, pushing cloud networking to a secondary level.
- **Trade-offs:** Strong for security roles, but neglects core Azure networking and CAF infrastructure strengths.
- **Selection Reason:** Rejected in favor of Approach 1 to maintain balance between cloud platform design and pipeline security.

### Approach 3: Minimalist Technical Card
- **Description:** Ultra-short summary with 3-bullet project cards and minimal badges.
- **Trade-offs:** Fast to read, but fails to demonstrate the architectural depth (state locking, peering, OIDC federation) required for competitive roles.
- **Selection Reason:** Rejected because it misses showcasing Mihir's deep understanding of enterprise patterns.

---

## 5. Specification of the New README Structure

### Section 1: Hero & Identity
- **Redesigned Custom Header SVG (`./assets/banner.svg`):**
  - Completely custom, unique vector artwork engineered specifically for Mihir Maurya.
  - Deep obsidian & twilight palette (`#080414` -> `#0f0926`) with subtle micro-grid and circuit/infrastructure path routing.
  - Crisp typography: "MIHIR MAURYA" with `[CLOUD & DEVSECOPS ENGINEER]`.
  - Four authentic engineering capsules:
    1. *Azure CAF Hub & Spoke*
    2. *Modular Terraform IaC*
    3. *Shift-Left CI/CD Gates*
    4. *Agentic AI & SRE Tooling*
  - Zero fake telemetry strings (no "NODE ID", "CONTROL PLANE ONLINE", or "v3.8-SEC").
- Clean tagline highlighting real focus:
  - "Automating Scalable Azure Infrastructure via Terraform"
  - "Enforcing Shift-Left Security & Secretless OIDC Pipelines"
  - "Building Resilient CI/CD Systems & SRE Automation"
- Quick links / badges:
  - Portfolio Website (`https://mihirmaurya-dev.github.io/`)
  - LinkedIn (`https://linkedin.com/in/mihirmauryaa1`)
  - Email (`mailto:chhotuverma2238@gmail.com`)
  - Status: Open to Cloud & DevSecOps Engineer roles

### Section 2: Executive Summary
A concise 2-paragraph professional summary:
- Focus on designing and provisioning automated, secure Microsoft Azure infrastructure using modular Terraform (IaC) and building robust CI/CD pipelines in Azure DevOps and GitHub Actions.
- Emphasis on shift-left security (Checkov, tfsec, Gitleaks, TruffleHog), zero-trust access (OIDC workload identity), and FinOps cost estimation (Infracost, Azure Retail Prices API).

### Section 3: Flagship Enterprise Projects (The Core 4)
Each flagship has:
- Repo link & title
- 1-sentence architectural summary
- Key technical highlights table (Architecture, Security, Automation, State/Cost)
- Direct inspection links (codebase, modules, pipeline YAML)

1. **[`azure-hub-spoke-architecture`](https://github.com/MihirMaurya-dev/azure-hub-spoke-architecture)**
   - *Title:* Enterprise Azure Hub-and-Spoke Network Topology & CAF Landing Zone
   - *Highlights:* Centralized Hub VNet (`10.0.0.0/16`), spoke isolation (`spoke-dev` `10.1.0.0/16`, `spoke-prod` `10.2.0.0/16`), VNet Peering, Azure Bastion, Azure Firewall Subnet, Key Vault, decoupled remote state with Azure Blob lease locking.
2. **[`Master_PipeLine`](https://github.com/MihirMaurya-dev/Master_PipeLine)**
   - *Title:* Monorepo Terraform CI/CD Bot & Pre-Commit Security Engine
   - *Highlights:* Dynamic matrix change detection (`tj-actions/changed-files`) executing only modified `.tf` directories in parallel, Infracost financial breakdown posted directly on PRs, pre-commit framework with Gitleaks, TFLint, and Terraform validation.
3. **[`master-devsecops-pipeline`](https://github.com/MihirMaurya-dev/master-devsecops-pipeline)**
   - *Title:* 4-Stage Azure DevOps CI/CD Pipeline & Predictive FinOps
   - *Highlights:* Stage 1 (Plan & FinOps via Azure Retail Prices API), Stage 2 (Multi-engine security scan: Gitleaks, TruffleHog, tfsec, Trivy), Stage 3 (Environment approval gate), Stage 4 (Immutable verified `tfplan` apply).
4. **[`azure-caf-modular-iac`](https://github.com/MihirMaurya-dev/azure-caf-modular-iac)**
   - *Title:* Modular Azure Infrastructure as Code Framework & Multi-Tier Blueprints
   - *Highlights:* Reusable modules for VNets, subnets, NSGs, Azure Bastion (zero-public-IP access), NAT Gateway (deterministic egress for private subnets), and separated Dev/Prod environments.

### Section 4: Specialized Engineering Builds
A concise 3-item grid/table showcasing domain breadth:
- **[`agentic-ai-devops`](https://github.com/MihirMaurya-dev/agentic-ai-devops):** Autonomous incident triage using Model Context Protocol (MCP) and LangGraph for SRE alert analysis and automated remediation PR generation.
- **[`genesis-iac-security-framework`](https://github.com/MihirMaurya-dev/genesis-iac-security-framework):** Custom Gitleaks regex detection suite, TFLint rules, and multi-stage CI/CD validation.
- **[`azure-devops-iis-automation`](https://github.com/MihirMaurya-dev/azure-devops-iis-automation):** Self-hosted Windows agent pipeline running .NET 8 unit testing, Cobertura code coverage, and automated IIS web deployment.

### Section 5: Engineering Principles & Standards
Clean structured bullet cards:
1. **Secretless Identity:** Workload Identity Federation (OIDC) eliminating static service principal secrets in CI runners.
2. **Immutable IaC:** Strict plan-then-apply workflows where only cryptographic artifacts tested in PR gates are deployed.
3. **Shift-Left Security:** Pre-commit hooks and multi-engine scanners (Gitleaks, TruffleHog, Checkov, Trivy) preventing vulnerabilities from reaching `main`.
4. **Blast-Radius Containment:** Decoupled state backends with lease locking and segregated network address spaces.

### Section 6: Technology & Tooling Matrix
Categorized, clean badges using `skillicons.dev` and structured markdown:
- **Cloud & Platforms:** Microsoft Azure (VNets, Hub-Spoke, Bastion, Key Vault, NAT GW, AKS)
- **Infrastructure as Code:** Terraform, OpenTofu, Modular IaC, Remote State Lease Locking
- **CI/CD & Automation:** GitHub Actions, Azure DevOps Pipelines, Pre-Commit, Bash, PowerShell
- **Security & Quality:** Checkov, tfsec, Trivy, TFLint, Gitleaks, TruffleHog
- **Containers & Systems:** Docker, Linux (Ubuntu), Git, REST APIs
- **Languages:** Python, Bash, PowerShell, HCL

### Section 7: Complete Public Repository Directory
Compact table listing all 11 relevant, verified public repositories owned by `MihirMaurya-dev` (excluding `medikiosk-sih26047` and `DevOps-Notes` per instruction):
1. [`azure-hub-spoke-architecture`](https://github.com/MihirMaurya-dev/azure-hub-spoke-architecture) - Enterprise Hub-and-Spoke Network Topology & CAF Landing Zone via Modular Terraform
2. [`Master_PipeLine`](https://github.com/MihirMaurya-dev/Master_PipeLine) - Monorepo Terraform CI/CD Bot, Dynamic Matrix Detection & Infracost
3. [`master-devsecops-pipeline`](https://github.com/MihirMaurya-dev/master-devsecops-pipeline) - 4-Stage Azure DevOps CI/CD Pipeline & Predictive FinOps
4. [`azure-caf-modular-iac`](https://github.com/MihirMaurya-dev/azure-caf-modular-iac) - Modular Azure IaC Framework & Multi-Tier Blueprints
5. [`agentic-ai-devops`](https://github.com/MihirMaurya-dev/agentic-ai-devops) - Autonomous SRE Swarms & MCP Protocol for Incident Triage
6. [`genesis-iac-security-framework`](https://github.com/MihirMaurya-dev/genesis-iac-security-framework) - Azure Terraform Suite with Custom Gitleaks Rules & TFLint
7. [`azure-devops-iis-automation`](https://github.com/MihirMaurya-dev/azure-devops-iis-automation) - Self-Hosted Agent Pipeline, .NET Core & Automated IIS Deployment
8. [`axion-enterprise-infra`](https://github.com/MihirMaurya-dev/axion-enterprise-infra) - Production 3-Tier Enterprise Infrastructure on Azure with Linux VMs
9. [`PipeLine`](https://github.com/MihirMaurya-dev/PipeLine) - Declarative GitHub Actions Azure Infrastructure Automation Engine
10. [`Terraform`](https://github.com/MihirMaurya-dev/Terraform) - Production-Ready Azure IaC Library & Load Balancer Blueprints
11. [`CI-CD`](https://github.com/MihirMaurya-dev/CI-CD) - Continuous Integration & Deployment Pipeline Workflows
12. [`FlexZone`](https://github.com/MihirMaurya-dev/FlexZone) - Full-Stack Fitness REST API Engine deployed on Azure VM
13. [`MihirMaurya-dev.github.io`](https://github.com/MihirMaurya-dev/MihirMaurya-dev.github.io) - Official Interactive Cloud & DevSecOps Engineer Portfolio Website

### Section 8: Connect & Custom Footer SVG
- Email (`mailto:chhotuverma2238@gmail.com`)
- LinkedIn (`https://linkedin.com/in/mihirmauryaa1`)
- Portfolio Website (`https://mihirmaurya-dev.github.io/`)
- **Redesigned Custom Footer SVG (`./assets/footer.svg`):**
  - Minimalist, elegant termination bar with subtle neon circuit traces.
  - Authentic signature: *"Architecting Resilient Cloud Infrastructure · Enforcing Zero-Trust DevSecOps"*
  - Direct timestamp & GitHub handle attribution without fake hash or fake node IDs.

---

## 6. What's Left to the Builder

- Exact SVG styling refinements for `assets/banner.svg` and `assets/footer.svg` to ensure labels match "Cloud & DevSecOps Engineer" and strip out all simulated "NODE ID", "CONTROL PLANE ONLINE", and "HASH 0x9D4E" text.
- Formatting of shields.io badges to ensure uniform visual consistency (flat-square or for-the-badge with consistent color scheme: Azure Blue `#0078D4`, Terraform Purple `#7B2CBF`, Green `#10B981`).
- Exact markdown syntax verification and link testing across all 13 repositories.
