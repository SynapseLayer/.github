# Security Policy

## Synapse Layer Trust Architecture

Synapse Layer implements a **non-bypassable 4-layer Cognitive Security Pipeline** that protects every memory operation:

| Layer | Name | Protection |
|:---:|---|---|
| 1 | Semantic Privacy Guard™ | PII redaction with 15+ regex patterns |
| 2 | Intelligent Intent Validation™ | Two-step categorization with self-healing |
| 3 | AES-256-GCM Encryption | Authenticated encryption at rest |
| 4 | Differential Privacy | Calibrated Gaussian noise on embeddings |

## Supported Versions

| Version | Supported |
|---|---|
| 1.1.x | ✅ Active |
| 1.0.x | ⚠️ Security fixes only |
| < 1.0 | ❌ End of life |

## Reporting a Vulnerability

**Do NOT open a public issue for security vulnerabilities.**

Please report security issues to:

📧 **founder.synapselayer@proton.me**

Include:
- Description of the vulnerability
- Steps to reproduce
- Affected version(s)
- Potential impact assessment

### Response Timeline

- **Acknowledgment:** within 48 hours
- **Initial assessment:** within 5 business days
- **Fix or mitigation:** within 30 days for critical issues

### Disclosure Policy

We follow coordinated disclosure. We will credit reporters in our security advisories (unless anonymity is requested).

## Security Design Principles

1. **Defense in depth** — All 4 security layers are mandatory and non-bypassable
2. **Zero-knowledge by default** — Server never sees plaintext when encryption is enabled
3. **Audit-ready payloads** — Every operation returns verifiable metadata for GDPR/LGPD compliance
4. **Minimal surface area** — Trust Quotient™ weights and Neural Handover™ internals are proprietary (not in open-source code)

---

**Synapse Layer** — Security is not a feature. It's the foundation.
