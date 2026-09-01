<h1 align="center">Tania Tabrizi</h1>

<p align="center">
  <strong>Identity & Access Management | Identity Engineering & Automation</strong>
  <br><br>
  <em>Enterprise IAM experience across identity governance, authentication, lifecycle management, privileged access, compliance, and automation — now building deeper hands-on identity engineering capability.</em>
</p>

<p align="center">
  <a href="https://linkedin.com/in/tania-tabrizi/">
    <img src="https://img.shields.io/badge/LinkedIn-tania--tabrizi-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
</p>

---

## About

I am an Identity & Access Management professional with 5+ years of enterprise experience supporting identity governance, lifecycle management, authentication, privileged access, compliance, troubleshooting, and IAM operations.

My professional background includes **SailPoint IdentityIQ, Microsoft Entra ID, Active Directory, CyberArk PAM, PingID, PowerShell, Python, SQL, ServiceNow, SOX, and PCI-DSS**.

This portfolio focuses on extending that production IAM experience into deeper identity engineering through hands-on work with **Microsoft Graph, REST APIs, automation, identity lifecycle design, SSO, provisioning protocols, testing, logging, and secure access controls**.

The goal is not to build disconnected tutorials. Each project is based on a realistic enterprise identity problem I have encountered or supported professionally.

---

# 01 · Enterprise IAM Experience

*Selected areas of professional IAM experience that provide the foundation for the engineering work in this portfolio.*

| Area | Experience | Technologies / Concepts |
| --- | --- | --- |
| **Identity Governance** | Application onboarding, identity data validation, role governance, entitlement management, access certifications, orphan remediation, and SoD / toxic-combination controls | SailPoint IdentityIQ · IGA · RBAC · SoD |
| **Identity Lifecycle** | Joiner, mover, and leaver operations involving account provisioning, role changes, access assignment, licensing, and deprovisioning | SailPoint · Active Directory · Entra ID · ServiceNow |
| **Authentication & SSO** | Enterprise MFA support, authentication troubleshooting, application integration support, and identity access issue investigation | PingID · Entra ID · SAML · OIDC · OAuth 2.0 |
| **Privileged Access** | Governance of privileged and cloud access, safe structures, least-privilege controls, and access remediation | CyberArk PAM · Entra ID · Least Privilege |
| **Automation & Reporting** | Automated recurring IAM data extraction, reporting, validation, and operational workflows | PowerShell · Python · SQL |
| **Security & Compliance** | IAM risk identification, remediation coordination, control evidence, audit narratives, and continuous audit readiness | SOX · PCI-DSS · Access Reviews · Audit Evidence |

---

# 02 · Current Engineering Project

## Enterprise Joiner / Mover / Leaver Automation Engine

![In Progress](https://img.shields.io/badge/Status-In_Progress-e3a008?style=flat-square)

A hands-on identity lifecycle automation project that models how an enterprise IAM platform processes HR-driven joiner, mover, and leaver events.

The project is being built in stages so that lifecycle decisions, access rules, validation, logging, and error handling are understood before connecting the workflow to live Microsoft Graph operations.

### Engineering goals

- Translate HR identity attributes into access decisions
- Model role-based group and license assignment
- Automate joiner, mover, and leaver processing
- Compare current access with desired access before making changes
- Prevent inappropriate or privileged access assignments
- Support dry-run execution before production changes
- Make lifecycle operations idempotent and safe to re-run
- Add structured audit logging and correlation IDs
- Validate the final identity state after provisioning
- Handle API and provisioning failures safely

### Planned architecture

```text
HR Event
   ↓
Identity Validation
   ↓
Lifecycle Classification
   ↓
Role / Access Rules
   ↓
Desired Identity State
   ↓
Change Plan
   ↓
Microsoft Graph
   ↓
Users + Groups + Licenses
   ↓
Validation / Reconciliation
   ↓
Audit Log
