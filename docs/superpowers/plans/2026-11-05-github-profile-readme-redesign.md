# GitHub Profile README Redesign Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Completely redesign Mihir Maurya's GitHub Profile README and custom SVG assets into a verified, high-impact, authentic showcase for a Cloud & DevSecOps Engineer, eliminating all fake telemetry and non-cloud projects.

**Architecture:** The profile is built in GitHub Flavored Markdown and custom SVG vector graphics. It leads with a custom obsidian-themed vector banner, concise executive positioning, 4 deeply detailed flagship cloud & DevSecOps repositories, 3 specialized builds, practical zero-trust engineering standards, a categorized tooling matrix, and a clean 13-repository public directory.

**Tech Stack:** GitHub Flavored Markdown, SVG (Scalable Vector Graphics), CSS animations, Shields.io, Skillicons.dev.

**Spec:** `docs/superpowers/specs/2026-11-05-github-profile-readme-redesign-design.md`

## Global Constraints

- **Strict Authenticity:** Absolutely zero invented telemetry (no "Mission Control Telemetry Matrix: ONLINE", "NODE ID: AZ-CENTRAL", "HASH: 0x9D4E", or "CONTROL PLANE ONLINE").
- **Title Accuracy:** Explicitly title Mihir Maurya as **Cloud & DevSecOps Engineer** across all markdown copy and SVG assets.
- **Project Exclusions:** Must NOT include `medikiosk-sih26047` or `DevOps-Notes` (per user explicit direction).
- **Zero Broken Links:** Every repository hyperlink must point to a live, verified GitHub repository owned by `MihirMaurya-dev`.
- **Theme Palette:** Deep obsidian (`#080414`), twilight violet (`#7B2CBF`), matrix green (`#00FF66`), and cyber cyan (`#00E5FF`).

## Review Focus

1. **Broken Repository Links:** A URL pointed to a non-existent repo (e.g. `terraform-azure`) results in a 404; ensure all 13 links match the verified GitHub API repository list.
2. **SVG Rendering Compatibility on GitHub:** GitHub caches SVGs via Camo proxy; ensure SVGs do not use external fonts or unsafe scripts that Camo blocks.
3. **Dark / Light Mode Contrast:** Markdown text and tables must remain crisp and readable in both GitHub dark and light modes.
4. **Mobile Responsiveness:** Tables and badges must wrap gracefully on mobile viewports without horizontal clipping.
5. **No Lingering Fluff:** Grep the entire workspace for residual sci-fi strings (`Mission Control`, `Telemetry Matrix`, `Autonomous SRE Swarms`, `Enterprise Solutions Architect`) to ensure complete cleanup.

---

### Task 1: Redesign Custom Header SVG (`assets/banner.svg`)

**Files:**
- Modify: `assets/banner.svg`

**Interfaces:**
- Consumes: Design spec Section 1 (`docs/superpowers/specs/2026-11-05-github-profile-readme-redesign-design.md:80-94`)
- Produces: `assets/banner.svg` referenced in `README.md` line 3

- [ ] **Step 1: Draft the modern vector SVG banner**
  - ViewBox: `0 0 1200 320`
  - Background: Deep obsidian gradient (`#06030e` to `#120727`) with fine grid pattern (`#7B2CBF` with low opacity) and animated circuit scan lines.
  - Header Tag: `> CLOUD_INFRASTRUCTURE // DEVSECOPS_AUTOMATION` in cyber cyan.
  - Primary Identity: `MIHIR MAURYA` in bold sans-serif, accompanied by `[CLOUD & DEVSECOPS ENGINEER]` in matrix green with subtle glow.
  - Subtitle: `Azure CAF Landing Zones · Zero-Trust Terraform IaC · Shift-Left CI/CD Pipelines`
  - 4 Capability Badges (authentic, zero fake telemetry):
    1. *Azure CAF Hub & Spoke* (`#0078D4`)
    2. *Modular Terraform IaC* (`#7B2CBF`)
    3. *Shift-Left CI/CD Gates* (`#00FF66`)
    4. *Agentic AI & SRE Tooling* (`#00E5FF`)
  - Status capsule (top right): `STATUS: OPEN FOR CLOUD & DEVSECOPS ROLES` with pulsing green indicator dot.

- [ ] **Step 2: Validate SVG syntax and local file integrity**
  Run: `powershell -Command "[xml](Get-Content assets/banner.svg) | Out-Null; Write-Host 'SVG Valid'"`
  Expected: `SVG Valid`

- [ ] **Step 3: Commit `assets/banner.svg`**
  ```bash
  git add assets/banner.svg
  git commit -m "style: redesign header banner SVG for Cloud & DevSecOps Engineer"
  ```

---

### Task 2: Redesign Custom Footer SVG (`assets/footer.svg`)

**Files:**
- Modify: `assets/footer.svg`

**Interfaces:**
- Consumes: Design spec Section 8 (`docs/superpowers/specs/2026-11-05-github-profile-readme-redesign-design.md:164-175`)
- Produces: `assets/footer.svg` referenced at the end of `README.md`

- [ ] **Step 1: Draft the modern minimalist footer SVG**
  - ViewBox: `0 0 1200 130`
  - Background: Deep obsidian container (`#06030e` to `#0f0520`) with rounded corners and glowing top gradient line.
  - Pulse Heartbeat Indicator: Green pulsing indicator with text `INFRASTRUCTURE AS CODE · SHIFT-LEFT SECURITY`.
  - Signature Tagline: `Architecting Resilient Cloud Infrastructure · Enforcing Zero-Trust DevSecOps`.
  - 4 Authentic Standard Badges:
    1. `AZURE CAF 3.0`
    2. `SECRETLESS OIDC`
    3. `IMMUTABLE IaC`
    4. `SHIFT-LEFT GATES`
  - Right-side attribution: `Mihir Maurya · github.com/MihirMaurya-dev` (removing all fake hash or node ID text).

- [ ] **Step 2: Validate SVG syntax and local file integrity**
  Run: `powershell -Command "[xml](Get-Content assets/footer.svg) | Out-Null; Write-Host 'SVG Valid'"`
  Expected: `SVG Valid`

- [ ] **Step 3: Commit `assets/footer.svg`**
  ```bash
  git add assets/footer.svg
  git commit -m "style: redesign footer SVG with clean engineering signatures"
  ```

---

### Task 3: Rewrite `README.md` with Authentic Approach 1 Structure

**Files:**
- Modify: `README.md`

**Interfaces:**
- Consumes: Design doc Sections 1-8 (`docs/superpowers/specs/2026-11-05-github-profile-readme-redesign-design.md`) and verified repo URLs
- Produces: Complete, authentic `README.md`

- [ ] **Step 1: Construct Section 1 & Section 2 (Hero, Typing Headline, Links, Executive Summary)**
  - Banner image embedding `./assets/banner.svg`.
  - Animated typing SVG headline with authentic phrases:
    `Cloud & DevSecOps Engineer;Modular Terraform IaC on Microsoft Azure;Shift-Left Security with Checkov, tfsec & Gitleaks;Dynamic CI/CD Automation & Infracost FinOps`.
  - Clean badge bar: Portfolio, Live Project, LinkedIn, GitHub, Open to Work.
  - Grounded 2-paragraph Executive Summary focused on Azure, modular Terraform, shift-left security, and CI/CD automation.

- [ ] **Step 2: Construct Section 3 (Flagship Projects Showcase)**
  Deeply detailed, structured breakdowns for:
  1. [`azure-hub-spoke-architecture`](https://github.com/MihirMaurya-dev/azure-hub-spoke-architecture)
     - Hub VNet (`10.0.0.0/16`), Spoke-Dev (`10.1.0.0/16`), Spoke-Prod (`10.2.0.0/16`), VNet Peering, Azure Bastion, Firewall Subnet, Key Vault, remote state lease-locking, `run-pipeline.ps1`.
  2. [`Master_PipeLine`](https://github.com/MihirMaurya-dev/Master_PipeLine)
     - Monorepo Terraform CI/CD Bot, dynamic matrix path detection (`tj-actions/changed-files`), pre-commit hooks (Gitleaks, TFLint, Terraform fmt/validate), Infracost PR finops.
  3. [`master-devsecops-pipeline`](https://github.com/MihirMaurya-dev/master-devsecops-pipeline)
     - 4-Stage Azure DevOps Pipeline: Plan & FinOps (Azure Retail Prices API), Security Scan (Gitleaks, TruffleHog, tfsec, Trivy), Approval Gate (`production-approval`), Immutable `tfplan` Apply.
  4. [`azure-caf-modular-iac`](https://github.com/MihirMaurya-dev/azure-caf-modular-iac)
     - Modular Azure IaC framework: Reusable modules (VNet, subnets, Bastion jumpbox, NAT Gateway static egress, separated Dev/Prod environments).

- [ ] **Step 3: Construct Section 4 & Section 5 (Specialized Builds & Engineering Standards)**
  - Specialized Builds:
    - [`agentic-ai-devops`](https://github.com/MihirMaurya-dev/agentic-ai-devops): MCP server protocol, LangGraph state machine, incident triage.
    - [`genesis-iac-security-framework`](https://github.com/MihirMaurya-dev/genesis-iac-security-framework): Custom Gitleaks regex rules, TFLint policy enforcement, CI validation.
    - [`azure-devops-iis-automation`](https://github.com/MihirMaurya-dev/azure-devops-iis-automation): Self-hosted agent on Windows Server, .NET 8 unit testing, Cobertura code coverage, IIS deployment.
  - Engineering Standards: 4 clear principles (Secretless Identity via OIDC, Immutable IaC, Shift-Left PR Gates, Decoupled State & Blast-Radius Containment).

- [ ] **Step 4: Construct Section 6 & Section 7 & Section 8 (Tooling Matrix, 13-Repo Directory, Connect & Footer)**
  - Skillicons badge grid + structured markdown category breakdown (Cloud & Platforms, IaC, CI/CD & Automation, Security & Governance, Systems & Scripting).
  - GitHub Stats & Streak card customized to dark theme.
  - Complete Public Repository Directory Table listing all 13 verified repositories with real descriptions, tools, and links.
  - Let's Connect contact links and embedded `./assets/footer.svg`.

- [ ] **Step 5: Verify markdown syntax and ensure total removal of excluded items**
  - Verify `medikiosk-sih26047` is completely absent.
  - Verify `DevOps-Notes` is completely absent.
  - Verify all fake telemetry strings are completely absent.
  - Run: `powershell -Command "$content = Get-Content README.md -Raw; if ($content -match 'medikiosk|DevOps-Notes|Telemetry Matrix|NODE ID|HASH:') { Write-Error 'Unwanted terms found!' } else { Write-Host 'Verification Passed' }"`
  - Expected: `Verification Passed`

- [ ] **Step 6: Commit `README.md`**
  ```bash
  git add README.md
  git commit -m "feat: complete redesign of profile README for Cloud & DevSecOps Engineer"
  ```

---

### Task 4: End-to-End Link & Visual Verification

**Files:**
- Verify: `README.md`, `assets/banner.svg`, `assets/footer.svg`

**Interfaces:**
- Consumes: Live GitHub repository URLs, git status

- [ ] **Step 1: Verify all 13 repository links via curl**
  Test all 13 repository URLs returning HTTP 200:
  ```powershell
  $repos = @(
    "azure-hub-spoke-architecture", "Master_PipeLine", "master-devsecops-pipeline",
    "azure-caf-modular-iac", "agentic-ai-devops", "genesis-iac-security-framework",
    "azure-devops-iis-automation", "axion-enterprise-infra", "PipeLine",
    "Terraform", "CI-CD", "FlexZone", "MihirMaurya-dev.github.io"
  )
  foreach ($r in $repos) {
    $code = (curl.exe -s -o NUL -w "%{http_code}" "https://github.com/MihirMaurya-dev/$r")
    if ($code -ne "200") { Write-Error "$r returned $code" } else { Write-Host "$r : OK (200)" }
  }
  ```
  Expected: All 13 repositories return `OK (200)`.

- [ ] **Step 2: Clean up dangling working directory files**
  - Check `git status`. Restore or remove unstaged deleted files (`footer.svg` / `header.svg` in root if superseded by `assets/`).
  - Ensure working tree is clean.

- [ ] **Step 3: Final commit and verification summary**
  ```bash
  git status
  ```
  Expected: Clean working tree on branch `main`.
