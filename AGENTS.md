# Starlight Intelligence Systems — Agent Operating Contract

Scope: All repositories under the **Starlight-Intelligence-Systems** GitHub Organization (https://starlightintelligence.org).
Brand register: `sis`

## Responsible Agent Team & Governance

| Role | Assigned Owner |
| :--- | :--- |
| **Human Codeowner** | `@frankxai` |
| **Organization Steward** | `steward-starlight` |
| **Executive Seat** | CSO (Strategy & Protocol) + CAIO (AI & Swarm Governance) |
| **Universal IS** | Starlight Orchestrator,Second Brain IS,Self IS |
| **Council Lead** | starlight-prime,starlight-sage,starlight-hermes |
| **Primary Harnesses** | `Claude Code`, `Antigravity`, `Codex`, `OpenCode` |

## Core Guardrails

1. **Think before coding.** State assumptions and surface tradeoffs. Verify file contents and branch state before writing.
2. **Surgical changes.** Touch only the files required for the active slice. Never overwrite or reset another agent's uncommitted worktree.
3. **Branch and worktree discipline.** Never push directly to `main`. Work on `agent/<harness>/<scope>` in a dedicated worktree and open a **draft** pull request first.
4. **Maker != Checker.** The harness that authors a pull request never approves or merges its own pull request.
5. **CI budget discipline.** Keep pull requests in draft until local verification (`lint`, `typecheck`, `test`, `build`) passes. Mark ready for review once.
6. **Non-waivable safety.**
   - Never commit secrets, API keys, or `.env` files.
   - Preserve repository visibility parity: never copy or mirror private repository contents into a public repository.
   - Money fails closed; no autonomous spend or paid API provisioning without explicit human approval.
   - In health and mind domains, model observations only; never diagnose or make clinical claims.

## Federated Repository Roster (6 repositories)

| Repository | Visibility | Primary Owner | Role |
| :--- | :--- | :--- | :--- |
| `Starlight-Intelligence-System` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/Starlight-Intelligence-System) |
| `starlight-research-hub` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/starlight-research-hub) |
| `starlight-knowledge-tree` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/starlight-knowledge-tree) |
| `starlight-cosmos-engine` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/starlight-cosmos-engine) |
| `starlight-swarm` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/starlight-swarm) |
| `starlight-memory-vault` | `private` | `frankxai` | federated-mirror (SSOT: frankxai/starlight-memory-vault) |

Built on SIP
