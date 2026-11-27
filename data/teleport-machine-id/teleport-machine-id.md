## Overview

Teleport Machine ID is purpose-built for teams adopting zero-standing-credentials patterns. Rather than storing secrets securely, it eliminates static credentials by issuing short-lived identities at runtime.

## Key Features

- **Short-lived X.509 certificates or JWT-SVID (SPIFFE-compatible)** issued at runtime
- **Automatic expiration**: Credentials expire when the job completes
- **No credential rotation needed**: Credentials never rotate or leak
- **Native CI/CD integrations**: GitHub Actions, GitLab CI, CircleCI, Jenkins, Azure DevOps, Spacelift
- **Cloud authentication**: Short-lived JWTs to authenticate to AWS, GCP, and Azure without static credentials
- **SPIFFE/X.509 identities**: Enable mutual TLS across services and trust domains
- **AI agent support**: Agents receive scoped, ephemeral identities rather than broad API keys

## Pricing Model

Apache 2.0 / Commercial (open source core with commercial offerings).

## Deployment

Self-hosted and cloud options available.

## Integrations

- GitHub Actions
- GitLab CI
- CircleCI
- Jenkins
- Azure DevOps
- Spacelift
- AWS, GCP, Azure (via short-lived JWTs)