# vault-manager

Repository for managing the Dick's Vault organization.

## GitHub Actions

### Sync All Forks

This action runs daily to sync all forked repositories in the `Dick-s-Vault` organization with their upstream sources.

**Setup Requirements:**
1. Create a Personal Access Token (PAT) with `repo` scope.
2. Add the PAT as a repository secret named `SYNC_TOKEN` in this repository (`vault-manager`).

Without the `SYNC_TOKEN`, the action will fail because the default `GITHUB_TOKEN` only has permissions for this repository.