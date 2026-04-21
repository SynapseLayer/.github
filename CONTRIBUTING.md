# Contributing to Synapse Layer

## Workflow

1. Fork → feature branch → changes → tests → PR
2. CI `secret-scan` must pass (no real tokens committed)
3. Use placeholders: `YOUR_TOKEN`, `sk_connect_xxx`, `sk_connect_test_`
4. Clear PR description required (use the template)

## Code of Conduct

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## Security

See [SECURITY.md](SECURITY.md) — never commit real credentials.

## Local Dev

```bash
git clone https://github.com/SynapseLayer/synapse-layer.git
cd synapse-layer
pip install -e ".[dev]"
pytest
```
