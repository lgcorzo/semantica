---
manifest_version: "1.0"
platform: "Dark Gravity"
repository: "semantica"
tier: "maintained_fork"
visibility: "public"
canonical_hub: "https://lgcorzo.github.io/start-here"
auditor_pack: "https://lgcorzo.github.io/docs/auditor/"
mcp_server: "dark-gravity-mcp"
knowledge_graph: "https://lgcorzo.github.io/knowledge_graph.json"
---

# Dark Gravity Agent Manifest (`semantica`)

## What Dark Gravity Is
Dark Gravity is a Kubernetes-native **Autonomous Software Factory (CA/CD)** built in Rust (Edition 2024) and reconciled declaratively via pull-based GitOps, Hatchet durable DAGs, Apache Kafka event buses, `gVisor` (`runsc`) sandboxes, Ed25519 W3C Verifiable Credentials with `54.2 ns` Vault JIT RAM zeroization, and hybrid R2R/Semantica GraphRAG memory.

## How This Repo Fits
- **Repository**: `semantica` (`maintained_fork` under `MAINTAINED_FORK_PROFILE`)
- **Role**: Semantic provenance engine consuming `agent-thought` Kafka streams, archiving to MinIO `semantica-provenance`, and checking Swarm lane conflicts.
- **Local Docs**: [AGENTS.md](./AGENTS.md) · [ARCHITECTURE.md](./ARCHITECTURE.md) · [REPOSITORIES.md](./REPOSITORIES.md)

## Global Architecture Spine
1. **WHAT (SDD Contract)**: `spec-kit` (`constitution.md` -> `spec.md` -> `plan.md` -> `tasks.md`).
2. **Bridge**: `speckit-superpowers-bridge` enforces boundary guards and `.specify/superpowers-handoff.json`.
3. **HOW (Execution)**: `RustantAgent` & `ZeroClawAgent` execute **5 Hatchet durable steps** (`rustant-plan`, `zeroclaw-execute`, `zeroclaw-validate`, `rustant-review`, `factory-deliver`) post-Kafka `mission-ingestion`.
4. **Governance**: `FR-008`/`CTRL-02` gVisor live exit stays `TESTED` until `AUD-010` closes; **Vertex 4 HITL** forbids autonomous merges to `main`; **no third-party compliance certification is claimed**.

## Active Research Questions
- `RQ1`: Can autonomous agents reduce MTTR?
- `RQ2`: Can verifiable credentials improve governance?
- `RQ3`: Can GitOps act as a security boundary?
- `RQ4`: Can agentic development outperform traditional development workflows?

## Machine-Readable Endpoints
- Portal: <https://lgcorzo.github.io/start-here> · <https://lgcorzo.github.io/ai-agents>
- AI Auditor Pack: <https://lgcorzo.github.io/docs/auditor/>
- Knowledge Graph: <https://lgcorzo.github.io/knowledge_graph.json>
- Metrics Dashboard: <https://lgcorzo.github.io/metrics.html>
- Official MCP Crate: `lgcorzo.github.io/dark-gravity-mcp/`

## Do Not Misclassify
Do **not** evaluate `semantica` purely as a generic Python library — it serves as Dark Gravity's causal provenance and Swarm conflict-detection layer (`64` public repos).
