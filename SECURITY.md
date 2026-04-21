# Security Policy — Synapse Layer Organization

**Report:** security@synapselayer.org · **Response:** 48h

**Do NOT open public issues for security vulnerabilities.**

## Supported

- `synapse-layer >= 1.2.0`

## Scope

Applies to all repositories under [github.com/SynapseLayer](https://github.com/SynapseLayer):

- synapse-layer
- synapse-layer-skill
- skills
- registry / servers (MCP mirrors)

## What we monitor

- Zero hardcoded secrets (CI `secret-scan.yml` on every push/PR)
- Header-first auth (`x-connect-token`)
- AES-256-GCM encryption at rest
- PII redaction pipeline
