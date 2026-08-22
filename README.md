<h1 align="center">Tania Tabrizi</h1>

<p align="center">
  <strong>Identity & Access Management | Identity Engineering & Automation</strong>
  <br><br>
  <em>Building secure, scalable identity solutions across lifecycle automation, authentication, provisioning, governance, and cloud IAM.</em>
</p>

<p align="center">
  <a href="https://linkedin.com/in/tania-tabrizi/">
    <img src="https://img.shields.io/badge/LinkedIn-tania--tabrizi-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
</p>

---

> **About This Portfolio**
>
> I have 5+ years of Identity & Access Management experience supporting enterprise identity environments serving 15,000+ users.
>
> My professional background includes SSO, MFA, identity lifecycle management, identity governance, privileged access, troubleshooting, and enterprise IAM operations using technologies including **Microsoft Entra ID, Active Directory, SailPoint IdentityIQ, CyberArk PAM, and PingID**.
>
> I am expanding that experience deeper into identity engineering through hands-on projects focused on **PowerShell and Python automation, Microsoft Graph, REST APIs, SCIM, application integrations, cloud identity, and secure lifecycle automation**.
>
> These projects are designed around real IAM engineering problems: building solutions, troubleshooting failures, reducing manual work, enforcing least privilege, and validating that identity workflows operate securely and reliably.

---

# 01 · Enterprise IAM Experience

*Selected IAM initiatives and responsibilities from enterprise production environments.*

| Experience                                 | Focus                                                                                                                                                                                       | Technologies                                              |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| **PingID MFA & Authentication Operations** | Served as a PingID SME supporting enterprise MFA, troubleshooting authentication failures, investigating configuration issues, validating authentication behavior, and supporting end users | PingID · MFA · Authentication · Conditional Access        |
| **SSO Application Integrations**           | Supported application onboarding, requirements gathering, authentication configuration, testing, troubleshooting, and production rollout of enterprise SSO integrations                     | SAML 2.0 · OAuth 2.0 · OIDC · Entra ID · Active Directory |
| **Identity Lifecycle & Access Operations** | Supported user lifecycle processes across onboarding, role changes, access provisioning, entitlement management, and deprovisioning                                                         | Active Directory · Entra ID · SailPoint · ServiceNow      |
| **SailPoint IdentityIQ Governance**        | Worked with identity provisioning, access certifications, role-based access, entitlement management, lifecycle workflows, and least-privilege controls                                      | SailPoint IdentityIQ · IGA · RBAC · Identity Lifecycle    |
| **Privileged Access Management**           | Supported privileged account governance and access controls designed to reduce unnecessary administrative access                                                                            | CyberArk PAM · Least Privilege · Identity Governance      |
| **Identity Compliance & Governance**       | Supported access reviews, remediation, certification evidence, and validation of identity security controls                                                                                 | SOX · PCI-DSS · Access Reviews · Audit Evidence           |

---

# 02 · Identity Engineering Projects

*Hands-on projects focused on building, automating, integrating, troubleshooting, and securing identity systems.*

| Project                                              | Engineering Focus                                                                                                                                                         | Stack                                                                  | Status                                                                            |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **Automated Joiner / Mover / Leaver Workflow**       | Automates identity lifecycle events from HR-style source data through account creation, role changes, group membership, licensing, and deprovisioning                     | PowerShell · Microsoft Graph · Entra ID · REST API                     | ![In Progress](https://img.shields.io/badge/In_Progress-e3a008?style=flat-square) |
| **Microsoft Graph Identity Automation Toolkit**      | Builds reusable automation for user discovery, group membership, license management, lifecycle operations, reporting, logging, and error handling                         | Python · PowerShell · Microsoft Graph · OAuth 2.0                      | ![In Progress](https://img.shields.io/badge/In_Progress-e3a008?style=flat-square) |
| **Enterprise SSO Integration & Troubleshooting Lab** | Configures an application for federated authentication and tests common failures involving claims, redirect URIs, assignments, policies, and authentication configuration | Entra ID · SAML 2.0 · OIDC · OAuth 2.0 · JWT                           | ![In Progress](https://img.shields.io/badge/In_Progress-e3a008?style=flat-square) |
| **SCIM Provisioning Service**                        | Builds a SCIM-compatible service supporting user creation, updates, account disabling, and automated provisioning between an identity provider and application            | Python · SCIM 2.0 · REST API · OAuth 2.0                               | ![Planned](https://img.shields.io/badge/Planned-888888?style=flat-square)         |
| **IAM Least-Privilege Audit Tool**                   | Analyzes users, roles, groups, licenses, and privileged access to identify excessive or inappropriate permissions and produce an audit report                             | Python · Microsoft Graph · Entra ID · CSV/JSON                         | ![Planned](https://img.shields.io/badge/Planned-888888?style=flat-square)         |
| **Hybrid Identity: Active Directory → Entra ID**     | Builds a hybrid identity environment, synchronizes identities, validates attribute flows, and applies cloud authentication controls                                       | Active Directory · Entra Connect · Entra ID · MFA · Conditional Access | ![In Progress](https://img.shields.io/badge/In_Progress-e3a008?style=flat-square) |
| **Privileged Identity Management JIT Workflow**      | Implements temporary privileged access with approval, activation requirements, expiration, and audit visibility                                                           | Entra ID PIM · JIT Access · Least Privilege                            | ![Planned](https://img.shields.io/badge/Planned-888888?style=flat-square)         |

---

# 03 · Featured Engineering Scenarios

## Automated Identity Lifecycle

```text
HR Source
   ↓
Identity Attributes
   ↓
Role / Access Rules
   ↓
Microsoft Graph
   ↓
User + Groups + Licenses
   ↓
Applications
   ↓
Logging + Validation
```

**Engineering goals**

* Automate repetitive IAM operations
* Enforce role-based access
* Remove access when no longer required
* Handle errors safely
* Record actions for audit and troubleshooting

---

## Application SSO Integration

```text
Requirements
   ↓
SAML / OIDC
   ↓
Claims + Attributes
   ↓
IdP Configuration
   ↓
Application Configuration
   ↓
Test Users
   ↓
Authentication Validation
   ↓
Production
   ↓
Monitoring
```

**Engineering goals**

* Understand the full authentication flow
* Configure identity integrations
* Troubleshoot protocol and configuration failures
* Validate claims, tokens, assignments, and access
* Document and monitor the solution after deployment

---

## SCIM Provisioning

```text
Identity Provider
   ↓
SCIM API
   ↓
Create User
Update User
Disable User
   ↓
SaaS Application
```

**Engineering goals**

* Understand provisioning beyond the admin console
* Work directly with REST APIs
* Handle identity attributes and schemas
* Build reliable create/update/deactivate workflows

---

## Least-Privilege Access Analysis

```text
User
   ↓
Groups
   ↓
Roles
   ↓
Entitlements
   ↓
Privileged Access
   ↓
Risk Detection
   ↓
Remediation Report
```

**Engineering goals**

* Trace how access is inherited
* Identify excessive privilege
* Detect lifecycle/access-control failures
* Improve governance using automation

---

# 04 · Technical Skills

### Identity & Directory

* Microsoft Entra ID
* Active Directory
* SailPoint IdentityIQ
* PingID
* CyberArk PAM

### Authentication & Provisioning

* SAML 2.0
* OAuth 2.0
* OpenID Connect
* JWT
* SCIM 2.0
* LDAP / LDAPS
* Kerberos

### Automation & APIs

* PowerShell
* Python
* Microsoft Graph API
* REST APIs
* SQL
* JSON

### Identity Engineering

* Joiner / Mover / Leaver lifecycle
* SSO integrations
* Automated provisioning
* Identity lifecycle automation
* API integrations
* Troubleshooting and root-cause analysis
* Logging and validation
* Role and entitlement management

### Identity Security & Governance

* RBAC
* ABAC
* Least Privilege
* Identity Governance
* Access Certifications
* Privileged Access Management
* Conditional Access
* MFA

---

# 05 · Engineering Approach

I approach IAM problems using a repeatable troubleshooting and engineering process:

```text
Scope
  ↓
Logs / Data
  ↓
Root Cause
  ↓
Secure Solution
  ↓
Test
  ↓
Validate
  ↓
Document
  ↓
Monitor
  ↓
Prevent Recurrence
```

My focus is not only on restoring access, but understanding **why an identity workflow failed and how the underlying design, automation, or control can be improved**.

---

# 06 · Security Governance

| Project                                 | Purpose                                                                                                                          | Status                                                                            |
| --------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **ISO 27001/27002 IAM Control Mapping** | Maps identity security controls to ISO requirements and documents how IAM capabilities support each control                      | ![In Progress](https://img.shields.io/badge/In_Progress-e3a008?style=flat-square) |
| **Access Control Policy**               | Develops an access control policy covering lifecycle management, least privilege, privileged access, and governance requirements | ![Planned](https://img.shields.io/badge/Planned-888888?style=flat-square)         |

---

# 07 · Certifications & Training

## Completed

![SailPoint](https://img.shields.io/badge/SailPoint_IdentityIQ_Core_Training-0078D4?style=flat-square)

![Azure IAM](https://img.shields.io/badge/Microsoft_Azure_Identity_&_Access_Management-0078D4?style=flat-square\&logo=microsoftazure\&logoColor=white)

![PAM](https://img.shields.io/badge/Privileged_Access_Management_\(PAM\)-2ea44f?style=flat-square)

## In Progress

![SC-300](https://img.shields.io/badge/SC--300_Identity_and_Access_Administrator-e3a008?style=flat-square\&logo=microsoftazure\&logoColor=white)

## Planned

![Okta](https://img.shields.io/badge/Okta_Certified_Professional-888888?style=flat-square)

![AWS Security](https://img.shields.io/badge/AWS_Security_Specialty-888888?style=flat-square)

---

<p align="center">
  <strong>Enterprise IAM experience. Building deeper identity engineering capability through automation, APIs, integrations, and cloud identity.</strong>
  <br><br>
  <a href="https://linkedin.com/in/tania-tabrizi/">Connect on LinkedIn</a>
</p>
