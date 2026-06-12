# Zscaler Labs — ZIA & ZPA Hands-On

Practical configuration and troubleshooting work across **Zscaler Internet Access (ZIA)** and **Zscaler Private Access (ZPA)**, covering secure web gateway policies, SSL inspection, Zero Trust application access, identity integration, and client-side troubleshooting.

This repo documents hands-on tasks I've performed in real and lab Zscaler environments as part of my work as a Network Security Engineer.

---

## What's covered

### ZIA — Zscaler Internet Access
- **URL filtering & access policies** — built and tuned URL filtering rules, defined acceptable-use categories, and applied policies to user groups and locations.
- **SSL inspection** — configured SSL/TLS inspection policy, set up inspection bypass for sensitive categories, and validated certificate handling on endpoints.
- **Security policies** — applied threat-protection and access controls aligned to acceptable-use and data-protection requirements.

### ZPA — Zscaler Private Access
- **Application segmentation** — defined application segments and segment groups for granular, least-privilege access to internal apps.
- **Zero Trust access** — configured access policies so users connect to specific applications rather than the full network, reducing lateral movement.
- **App Connector concepts** — worked with connector-based access for private application reachability.

### Identity & Authentication
- **SAML / SSO integration** — configured SAML-based authentication and SSO for user identity, mapping users and groups to access policies.

### Troubleshooting
- **Zscaler Client Connector** — diagnosed and resolved client-side connectivity and authentication issues, including tunnel state, posture, and policy evaluation problems.

---

## Topics / Keywords
`Zscaler` · `ZIA` · `ZPA` · `Zero Trust` · `ZTNA` · `URL Filtering` · `SSL Inspection` · `Application Segmentation` · `SAML` · `SSO` · `Zscaler Client Connector` · `Secure Web Gateway` · `Cloud Security`

---

## Repository structure
> Suggested layout — add your own notes, configs, and screenshots into these folders.

```
zscaler-labs/
├── README.md
├── zia/
│   ├── url-filtering-notes.md
│   ├── ssl-inspection-notes.md
│   └── screenshots/
├── zpa/
│   ├── app-segmentation-notes.md
│   ├── access-policy-notes.md
│   └── screenshots/
├── identity/
│   └── saml-sso-setup-notes.md
└── troubleshooting/
    └── client-connector-issues.md
```

---

## Notes
- Configuration screenshots are from lab / trial tenant environments; production work is described conceptually without exposing any organization-specific data, policy names, or tenant identifiers.
- This repository is for demonstrating hands-on familiarity and documentation, not for sharing any confidential configuration.

---

**Author:** Miriyala Durga Rao — Network Security Engineer
[Portfolio](https://mdurgarao-tech.github.io) · [LinkedIn](https://www.linkedin.com/in/miriyala-durgarao)
