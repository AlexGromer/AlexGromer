<h1 align="center">Alex Gromer</h1>

<p align="center">
  <b>Systems architect · DevOps/SRE · Security engineering · AI tooling</b><br>
  Infrastructure that stays up, and tooling that keeps engineers honest.
</p>

<p align="center">
  <a href="https://alexgromer.github.io"><img alt="Site" src="https://img.shields.io/badge/site-alexgromer.github.io-1f6feb?style=flat-square"></a>
</p>

## About

I design and run platforms where failure is expected and contained: Kubernetes delivery, identity and
database migrations, air-gapped installs, and guard rails for AI coding agents. Go, Rust and C for the parts
that matter; Bash, Python and TypeScript where they fit.

- **Platform & delivery**: Kubernetes, Helm generation, GitOps, self-hosted runners, closed-network installs.
- **Identity & migration**: Keycloak migration across DBMS and deployment shapes, dependency-free JWT handling.
- **Security engineering**: fail-closed guards for shell execution, secret-leak gates, egress control, audit tooling.
- **AI tooling**: agent configuration frameworks, deterministic test harnesses, local-model evaluation pipelines.
- **Home lab**: Proxmox, Ceph, K3s, ArgoCD and a local AI server for private workloads.

## Tech stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
<br>
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![K3s](https://img.shields.io/badge/K3s-FFC61C?style=flat-square&logo=k3s&logoColor=black)
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Ceph](https://img.shields.io/badge/Ceph-EF5C55?style=flat-square&logo=ceph&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square&logo=keycloak&logoColor=white)

## Featured work

| Project | What it does |
|---|---|
| [**sentinel**](https://github.com/AlexGromer/sentinel) | Self-healing UI-testing agent: explores a web app, freezes a replayable plan, repairs locators on DOM drift. Go, Python, TypeScript. |
| [**deckhouse-helm-generator**](https://github.com/AlexGromer/deckhouse-helm-generator) | Turns live Kubernetes resources into Helm charts, with relationship detection (CRDs, Prometheus Operator, Gateway API, KEDA, cert-manager, Argo Rollouts). Go CLI. |
| [**keycloak-migration**](https://github.com/AlexGromer/keycloak-migration) | Multi-DBMS, multi-deployment Keycloak migration framework: auto-discovery, atomic checkpoints, air-gap support. |
| [**jwt-parser**](https://github.com/AlexGromer/jwt-parser) | JWT parser with zero dependencies for closed networks; 131 tests. Bash and Go. |
| [**ssh-yaml-validator**](https://github.com/AlexGromer/ssh-yaml-validator) | YAML validator for air-gapped hosts. Bash. |

<details>
<summary>More repositories</summary>

- [claude-code-operator-framework](https://github.com/AlexGromer/claude-code-operator-framework): model-agnostic Claude Code configuration (output styles, rules, agents, hooks, MCP servers).
- [dead-code-checker](https://github.com/AlexGromer/dead-code-checker): dead-code detection with a public-API mode and an LLM second opinion.
- [vot-local](https://github.com/AlexGromer/vot-local): voice-over translation of local video files into a dubbed .mkv.
- [rlm](https://github.com/AlexGromer/rlm): Recursive Language Model methods.
- [ACEV-Framework](https://github.com/AlexGromer/ACEV-Framework): knowledge-base framework (Second Brain + Zettelkasten).
- [uka-runner-bootstrap](https://github.com/AlexGromer/uka-runner-bootstrap).
- [elasticsearch-analysis-morphology-prebuilt-plugin](https://github.com/AlexGromer/elasticsearch-analysis-morphology-prebuilt-plugin): prebuilt morphology analysis plugin for Elasticsearch.

</details>

## Open-source contributions

| Project | Contribution | Status |
|---|---|---|
| [FOSWLY/vot.js](https://github.com/FOSWLY/vot.js) | edX support ([#143](https://github.com/FOSWLY/vot.js/pull/143)); configurable media proxy host ([#144](https://github.com/FOSWLY/vot.js/pull/144)) | Merged |
| [ilyhalight/voice-over-translation](https://github.com/ilyhalight/voice-over-translation) | Media proxy host setting ([#1894](https://github.com/ilyhalight/voice-over-translation/pull/1894)); tests and check fixes ([#1881](https://github.com/ilyhalight/voice-over-translation/pull/1881)) | Merged |
| [FOSWLY/media-proxy](https://github.com/FOSWLY/media-proxy) | Pull request [#115](https://github.com/FOSWLY/media-proxy/pull/115) | Open |
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | Reproducible bug report: [#104986](https://github.com/anthropics/claude-code/issues/104986), background subagent terminated at its first Bash call | Reported |
| [AlexGromer/heretic](https://github.com/AlexGromer/heretic) | Fork with three branches prepared as upstream PRs: fused MoE experts, FP8 checkpoint loading, ARA on flattened I/O | In preparation |

## Principles

- **Fail closed.** A guard that times out is a guard that denies.
- **Reproducible.** Pinned sources, signed commits, deterministic builds and tests.
- **Worse is better.** Ship the simple thing, measure, then harden.

## GitHub stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=AlexGromer&show_icons=true&hide_border=true&theme=dark&bg_color=00000000">
    <img alt="GitHub stats" height="170" src="https://github-readme-stats.vercel.app/api?username=AlexGromer&show_icons=true&hide_border=true&theme=default&bg_color=00000000">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=AlexGromer&layout=compact&hide_border=true&theme=dark&bg_color=00000000">
    <img alt="Top languages" height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AlexGromer&layout=compact&hide_border=true&theme=default&bg_color=00000000">
  </picture>
</p>
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=AlexGromer&hide_border=true&theme=dark&background=00000000">
    <img alt="Contribution streak" src="https://streak-stats.demolab.com?user=AlexGromer&hide_border=true&theme=default&background=00000000">
  </picture>
</p>

---

<p align="center">Contact: <a href="https://alexgromer.github.io">alexgromer.github.io</a>, or issues and discussions on any repository above.</p>
