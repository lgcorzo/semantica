<!-- DARK-GRAVITY-CONTEXT:START -->
## Dark Gravity Autonomous Software Factory Context

**Dark Gravity** is a Kubernetes-native, **Continuous Agentic / Continuous Deployment (CA/CD)** autonomous software engineering factory — do **NOT** evaluate `semantica` in isolation without reading the ecosystem context below.

- **This Repository's Tier & Role**: `maintained_fork` (`MAINTAINED_FORK_PROFILE`, upstream `Hawksight-AI/semantica`) — Semantic domain modeling, ontological causal provenance, and parallel lane conflict detector (`SemanticaClient::detect_conflicts`) consuming Kafka `agent-thought` events inside Dark Gravity.
- **Mandatory Ecosystem Read Order (< 5 min)**:
  1. [./DARK_GRAVITY_MANIFEST.md](./DARK_GRAVITY_MANIFEST.md) — Concise machine- and human-readable ecosystem manifest
  2. [./ARCHITECTURE.md](./ARCHITECTURE.md) — Semantic ontology architecture (including upstream pipeline below)
  3. [./REPOSITORIES.md](./REPOSITORIES.md) — Full multi-repository ecosystem topology
  4. Unified Entry Portal: <https://lgcorzo.github.io/start-here> (Agent Entry: <https://lgcorzo.github.io/ai-agents>)
  5. AI Auditor Pack: <https://lgcorzo.github.io/docs/auditor/>
- **Canonical Ecosystem Invariants**:
  - **Fork Policy (`MAINTAINED_FORK_PROFILE`)**: Preserve upstream directory layouts & `LICENSE`, omit `upstream` remote, use `[agent]` commit prefixes, route security advisories privately, and NEVER auto-merge PRs (`Vertex 4 HITL`).
  - **Portfolio Reconciliation**: `64` public repositories (`22` original + `42` maintained forks; `69` historical baseline; `72` Spec `004` inventory). `lgcorzo/kes` is permanently `FROZEN_READONLY`.
  - **Mission & Isolation**: Kafka `mission-ingestion` -> **5 Hatchet durable steps**; `gVisor` (`runsc`) (`FR-008`/`CTRL-02` kept `TESTED` until `AUD-010` closes); **no third-party compliance certification is claimed**.
<!-- DARK-GRAVITY-CONTEXT:END -->

# AGENTS.md — `semantica`

- Submit all dependency, security, and feature patches on dedicated feature branches via PRs for manual Vertex 4 HITL review and merge.
- Enforce `DOC-011`: never commit private repository names, workstation paths, secrets, or internal LAN IPs into public files.
