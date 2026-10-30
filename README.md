# Alex Gromer

**Systems architect · DevOps/SRE · security engineering · AI tooling**

I build infrastructure that stays up and tooling that keeps engineers honest: Kubernetes platforms, identity and
migration tooling, air-gapped delivery, guard rails for AI coding agents, and evaluation pipelines for local models.
Go, Rust, C for the parts that matter; Bash and Python where they fit.

Site and app policies: [alexgromer.github.io](https://alexgromer.github.io)

## What I work on

- **Platform & delivery** — Kubernetes (Deckhouse-flavoured too), Helm generation, GitOps, self-hosted runners, closed-network installs.
- **Identity & migration** — Keycloak migration tooling across DBMS and deployment shapes, JWT handling without dependencies.
- **Security engineering** — fail-closed guards for shell execution, secret-leak gates, egress control for AI agents, audit tooling.
- **AI tooling** — agent configuration frameworks, deterministic test harnesses, model evaluation and judge calibration pipelines.
- **Home lab** — Proxmox, Ceph, K3s, ArgoCD; a local AI server for private workloads.

## Selected public projects

| Project | What it is |
|---|---|
| [sentinel](https://github.com/AlexGromer/sentinel) | Self-healing UI-testing agent: explores a web app, freezes a replayable plan, repairs locators on DOM drift. Go spine, Python brain, TypeScript executor. |
| [deckhouse-helm-generator](https://github.com/AlexGromer/deckhouse-helm-generator) | CLI that turns live Kubernetes resources into Helm charts with relationship detection (CRDs, Prometheus Operator, Gateway API, KEDA, cert-manager, Argo Rollouts). |
| [keycloak-migration](https://github.com/AlexGromer/keycloak-migration) | Multi-DBMS, multi-deployment Keycloak migration framework: auto-discovery, atomic checkpoints, air-gap support. |
| [jwt-parser](https://github.com/AlexGromer/jwt-parser) | Pure Bash + Go JWT parser with zero dependencies for closed networks; 131 tests. |
| [ssh-yaml-validator](https://github.com/AlexGromer/ssh-yaml-validator) | Pure Bash YAML validator for air-gapped hosts. |
| [claude-code-operator-framework](https://github.com/AlexGromer/claude-code-operator-framework) | Model-agnostic Claude Code configuration: output styles, rules, agents, hooks, MCP servers. |
| [dead-code-checker](https://github.com/AlexGromer/dead-code-checker) | Dead-code detection with a public-API mode and an LLM second opinion. |
| [rlm](https://github.com/AlexGromer/rlm) | Recursive Language Model methods. |
| [vot-local](https://github.com/AlexGromer/vot-local) | Voice-over translation of local video files into a dubbed .mkv. |
| [ACEV-Framework](https://github.com/AlexGromer/ACEV-Framework) | Knowledge-base framework: Second Brain + Zettelkasten. |

## Contributing

- [heretic](https://github.com/AlexGromer/heretic) — fork with fused MoE experts, FP8 checkpoint loading and ARA on flattened I/O, prepared as upstream pull requests.

## Principles

- Worse is better: ship the simple thing, measure, then harden.
- Fail closed. A guard that times out is a guard that denies.
- Everything reproducible: pinned sources, signed commits, deterministic builds and tests.

---

Contact: GitHub issues or discussions on any of the repositories above.
