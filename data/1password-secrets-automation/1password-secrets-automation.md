## Overview

1Password Secrets Automation is the developer-facing layer of the 1Password platform, designed for developer teams and CLI workflows. It allows developers to commit .env file references instead of secrets, with values loaded from 1Password at runtime.

## Key Features

- **.env file references**: Developers commit references instead of secrets; values load from 1Password at runtime
- **CLI plugins**: Shell plugins for securing local CLI access, eliminating plaintext credentials from ~/.aws and similar directories
- **Kubernetes integrations**: Native support for Kubernetes secret management
- **CI/CD integrations**: Integration with major CI/CD platforms
- **Zero-knowledge architecture**: All encryption happens client-side; 1Password servers never hold unencrypted data
- **Strict access controls**: Role-based access to secrets

## Pricing Model

Commercial product. Pricing is available through 1Password's business plans.

## Deployment

Cloud-hosted (SaaS). No self-hosted option.

## Integrations

- Kubernetes
- CI/CD platforms (GitHub Actions, GitLab CI, Jenkins)
- Shell/CLI plugins
- Major cloud platforms