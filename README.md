# vault-manager

Repository for managing the **Dick's Vault** organization. This project serves as the central command center for automation, governance, and status reporting across all 260+ repositories.

---

## 📊 Comprehensive Status

| Metric | Status | Last Updated |
| :--- | :--- | :--- |
| **Org-Wide Sync** | ![Sync Status](https://img.shields.io/badge/Status-Active-brightgreen) | Daily |
| **Fork Health** | ![Fork Health](https://img.shields.io/badge/Health-Monitored-blue) | Weekly |
| **Governance** | ![Policy Enforcement](https://img.shields.io/badge/Governance-Draft-yellow) | - |
| **Cleanup Operations** | ![Cleanup](https://img.shields.io/badge/Cleanup-Pending-lightgrey) | - |

### 🛠️ Active Modules
- **[Sync All Forks](./.github/workflows/sync-forks.yml):** Daily synchronization of forked repositories with their upstream sources.
- **Label Manager (In Progress):** Standardizing labels across the organization.
- **Policy Enforcer (Planned):** Automated file injection (LICENSE, README templates).

---

## 📋 Management Tasks

See [Issues](https://github.com/Dick-s-Vault/vault-manager/issues) for the active roadmap. Key initiatives:
- [#1] Label Standardization
- [#2] Stale Fork Auditing
- [#4] Merged Branch Cleanup

---

## 🚀 Setup & Requirements

1. **SYNC_TOKEN:** Ensure a Personal Access Token with `repo` scope is added as a repository secret named `SYNC_TOKEN`.
2. **Permissions:** Actions in this repository operate organization-wide. Verify access before adding new modules.
