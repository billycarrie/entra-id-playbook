# **Entra ID Playbook**

> Operational runbooks, policy frameworks, and automation scripts for governing Microsoft Entra ID in a retail/ecommerce SMB environment — Carrie Cares tenant.

## **Status**

🚧 **Under active development** — sandbox configurations complete, documentation being added.

---

## **What This Covers**

| Area | Description | Status |
|---|---|---|
| Conditional Access | Policy design, naming conventions, exclusion strategy | 🚧 In progress |
| Privileged Identity Management | Role architecture, activation workflows, access reviews | 📋 Planned |
| App Registration Standards | Naming, ownership, permission governance | 📋 Planned |
| Guest Access Governance | B2B lifecycle, external identity controls | 📋 Planned |
| Automation Scripts | PowerShell — stale guests, CA export, admin role review | 📋 Planned |

---

## **Repo Structure**

```
entra-id-playbook/
│
├── README.md
│
├── docs/
│   ├── conditional-access-policy-design.md
│   ├── pim-role-assignment-guide.md
│   ├── app-registration-standards.md
│   └── guest-access-governance.md
│
└── scripts/
    ├── Get-StaleGuestAccounts.ps1
    ├── Export-CAPolicy.ps1
    └── Review-AdminRoleAssignments.ps1
```

---

## **SMB Context**

Built in a live Entra ID P2 sandbox simulating **Carrie Cares** — a ~200 employee retail/ecommerce company building its identity program from the ground up. All configurations reflect real portal work, not theoretical examples.

---

## **Related Repos**

| Repo | Focus | Status |
|---|---|---|
| [nhi-lifecycle-mgmt](https://github.com/billycarrie/nhi-lifecycle-mgmt) | Non-Human Identity governance | ✅ Complete |
| [entra-id-playbook](https://github.com/billycarrie/entra-id-playbook) | Entra ID operational runbooks | 🚧 In progress |
| [powershell-iam-toolkit](https://github.com/billycarrie/powershell-iam-toolkit) | IAM automation scripts | 📋 Planned |
| [iam-program-framework](https://github.com/billycarrie/iam-program-framework) | IAM program design templates | 📋 Planned |
| [zero-trust-identity](https://github.com/billycarrie/zero-trust-identity) | Zero Trust identity architecture | 📋 Planned |
| [kql-identity-queries](https://github.com/billycarrie/kql-identity-queries) | KQL detection query library | 📋 Planned |

---

## **Author**

**Billy Carrie** — IAM Engineer | Founding M&A Security Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/billycarrie/)
