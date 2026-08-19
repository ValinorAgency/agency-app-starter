# Valinor Agency App Starter

This repository is the technology-agnostic baseline for Valinor client projects. It defines the minimum project context, decisions, quality expectations, and agent contract needed for humans and coding agents to work from the same evidence.

It does not select a technical profile or contain application code. Record only confirmed project information; use `Pending confirmation`, `Not decided`, or `Not applicable` where appropriate.

## Start a project

1. Complete [PRODUCT.md](PRODUCT.md) with confirmed product context and scope.
2. Complete [DESIGN.md](DESIGN.md) when the project has a visual surface.
3. Record actual technical decisions in [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md).
4. Replace unconfigured quality gates with real commands in [docs/QUALITY.md](docs/QUALITY.md) as tooling is adopted.
5. Set the project's technical profile in [.valinor/system.json](.valinor/system.json) when a formal profile is applied.

## Canonical documents

| Topic | Source |
| --- | --- |
| Product, requirements, and scope | [PRODUCT.md](PRODUCT.md) |
| Design direction | [DESIGN.md](DESIGN.md) |
| Architecture | [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md) |
| Quality gates and validation commands | [docs/QUALITY.md](docs/QUALITY.md) |
| Significant decisions | [docs/decisions/](docs/decisions/) |
| Proven project learnings | [docs/LESSONS.md](docs/LESSONS.md) |
| Coding-agent contract | [AGENTS.md](AGENTS.md) |

Git-tracked project files are the official source of truth. Keep facts, decisions, and open questions explicit, and update the canonical document rather than creating parallel sources.
