## Overview

Pulumi ESC (Environments, Secrets, and Configuration) is designed for DevOps teams already using Pulumi for infrastructure-as-code. It introduces environments-as-code with hierarchical YAML configurations that cascade across environments.

## Key Features

- **Environments-as-code**: Hierarchical YAML environments that cascade from base configurations through dev, staging, and production
- **Dynamic secret pulling**: Retrieves secrets from AWS Secrets Manager, Azure Key Vault, GCP Secret Manager, HashiCorp Vault, and 1Password via OIDC
- **Short-lived credentials**: No plaintext secrets in pipelines
- **SDKs**: Python, TypeScript/JavaScript, and Go
- **Automated rotation**: For AWS IAM keys and database credentials (PostgreSQL, MySQL), launched in 2025
- **Eliminates secrets sprawl**: Reduces manual copying that causes secrets sprawl

## Pricing Model

Commercial product.

## Deployment

Cloud-hosted (SaaS).

## Integrations

- AWS Secrets Manager
- Azure Key Vault
- GCP Secret Manager
- HashiCorp Vault
- 1Password
- Pulumi IaC