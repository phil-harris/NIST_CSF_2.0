# GRC Learning Roadmap & Applied Portfolio
**Target Framework:** NIST CSF 2.0 

---

## Executive Summary
Welcome to my GRC portfolio and learning repository. The objective of this repository is to bridge theoretical framework knowledge with practical technical implementation. Here, I document my study of NIST CSF 2.0, map security controls against real-world systems, perform gap analyses, and produce audit-ready evidence artifacts.

---

## Roadmap & Progress Tracking

| Phase | Objective | Focus Areas | Status |
| :--- | :--- | :--- | :--- |
| **Phase 1** | Framework Foundations | NIST CSF 2.0 Core Functions & Subcategories | 🟡 In Progress |
| **Phase 2** | Applied Technical Audits | Docker on Linux VM Control Validation | 🔵 Active Project |
| **Phase 3** | Policy & Governance | Container & OS Security Policy Writing | 🔴 Planned |
| **Phase 4** | Risk & Gap Analysis | System Risk Assessment & Remediation Plans | 🔴 Planned |

*Status Legend: 🟢 Complete | 🟡 In Progress | 🔵 Active Project | 🔴 Planned*

---

## Portfolio Index & Repository Map

### 1. Framework Deep Dives (`/01-framework-deep-dive`)
*Breakdown of NIST CSF 2.0 functions, mapping subcategories to practical security controls.*
* [Govern (GV)](./01-framework-deep-dive/govern-GV.md) — Governance, organizational context, and risk strategies.
* [Identify (ID)](./01-framework-deep-dive/identify-ID.md) — Asset management, risk assessment, and supply chain.
* [Protect (PR)](./01-framework-deep-dive/protect-PR.md) — Access control, platform security, and data protection.
* [Detect (DE)](./01-framework-deep-dive/detect-DE.md) — Continuous monitoring and anomaly detection.
* [Respond (RS)](./01-framework-deep-dive/respond-RS.md) — Incident management and communication.
* [Recover (RC)](./01-framework-deep-dive/recover-RC.md) — Recovery execution and resilience.

### 2. Applied Hands-on Labs (`/02-applied-labs`)
*Hands-on GRC projects demonstrating control auditing and evidence collection.*
* **[Lab 01: Hardened Docker Environment Audit](./02-applied-labs/lab-01-docker-vm-audit/)**
  * **Scope:** Linux VM hosting a Docker container engine.
  * **Framework Mapping:** NIST CSF 2.0 (PR.AA Access Control, PR.DS Data Security, DE.CM Continuous Monitoring).
  * **Key Artifacts:** Audit checklists, hardened `docker-compose.yml`, log evidence, gap report.

### 3. Governance & Policy Artifacts (`/03-policy-templates`)
*Original policy drafts and control standards written for lab environments.*
* [Container Security Policy Draft](./03-policy-templates/container-security-policy.md)
* [Linux Host Auditing Standard](./03-policy-templates/host-auditing-standard.md)

---

## Environment & Tooling
* **OS / Infrastructure:** Linux VM
* **Containerization:** Docker Engine / Docker Compose
* **Frameworks & Standards:** NIST CSF 2.0, CIS Benchmarks

<br>

### Additional Resources
[NIST Cybersecurity Framework (CSF) 2.0 Reference Tool](https://docs.google.com/spreadsheets/d/1Mlq27SxMdJ_S240yLUmBBcCFkVLOi_UB/edit?usp=sharing&ouid=112846220479532615624&rtpof=true&sd=true)

<br>

[NIST Cybersecurity Framework 2.0: RESOURCE & OVERVIEW GUIDE](https://drive.google.com/file/d/17TWCOWVxO5ncYIrfydfpT9FyjBxBcknc/view?usp=drive_link)
