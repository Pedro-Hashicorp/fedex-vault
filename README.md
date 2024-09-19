# Vault Proof of Value - Functional Use Cases

## Vault API & Policy Evaluation
**Requirements:**
FedEx requires the ability to retrieve secrets from Vault via its API. Additionally, FedEx needs to verify Vault’s ability to apply real-time policy updates. Once a policy change is made on the Vault side that grants access to an application, any subsequent request from the running application should be authorized without the need to restart the application or perform re-authentication to Vault.

**Pre-requisites:**
All actions must be performed in non-production environments and the FedEx team must complete configuration
An existing Vault Enterprise or HCP Vault environment
A virtual machine or other FedEx-approved device from which the API calls can be made
Additional Documentation
https://developer.hashicorp.com/vault/docs/concepts/policies



GitHub Action Integration

- [Vault + Kubernetes Secret Injection](./arch/vault-k8s-secrets-management/)
