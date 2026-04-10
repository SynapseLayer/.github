<div align="center">

  <h2>Synapse Layer</h2>

  <p><strong>Continuous Consciousness Infrastructure for AI Systems</strong></p>

  <p>Persistent. Secure. 1-line integration. 🧠</p>

  <p>MCP-Native · Zero-Knowledge · Built in Brazil 🇧🇷</p>

</div>

---

### What We Build

Memory infrastructure for the Agent Economy.

| Repo | Description |
|---|---|
| [**synapse-layer**](https://github.com/SynapseLayer/synapse-layer) | Core SDK — Open Source (Apache 2.0) |
| [**synapse-layer-skill**](https://github.com/SynapseLayer/synapse-layer-skill) | Agent entrypoint for MCP & marketplaces |
| [**.github**](https://github.com/SynapseLayer/.github) | Governance, templates & community |

---

### Quick Start

```python
from synapse_memory import SynapseMemory, SqliteBackend, remember

memory = SynapseMemory(agent_id="my-agent", backend=SqliteBackend())

@remember(memory)
async def answer(prompt: str) -> str:
    return llm.chat(prompt)  # auto recall + store
```

### Connect

- 📦 **PyPI:** `pip install synapse-layer`
- 🔌 **MCP:** `forge.synapselayer.org/api/mcp`
- 📖 **Docs:** [docs.synapselayer.org](https://docs.synapselayer.org)
- 🌐 **Website:** [synapselayer.org](https://synapselayer.org)

---

<p align="center"><strong>Giving Agents a Past. Giving Models a Soul. ⚗️</strong></p>
