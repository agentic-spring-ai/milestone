# Agentic Spring AI Milestones

This repository is the cross-repository release plan for Agentic Spring AI and
Agentic Spring AI Extensions. Code changes live in the product repositories;
this repository records version goals, ownership, dependencies, migration work,
and release gates.

## Version Matrix

| Version | Core | Extensions | Status | Plan |
| --- | --- | --- | --- | --- |
| 1.x patch | 1.1.2.3 | 1.1.2.4 | Released | [archive/1.x-patch.md](archive/1.x-patch.md) |
| 2.0.0.0 | 2.0.0.0 | 2.0.0.0 | Released | [archive/2.0.0.0.md](archive/2.0.0.0.md) |
| 2.1.0 | 2.1.0-dev | 2.1.0-dev | Release ready | [active/2.1.0.md](active/2.1.0.md) |
| 2.2.0 | 2.2.0-dev | 2.2.0-dev | Planned | [active/2.2.0.md](active/2.2.0.md) |
| 3.0.0.0-RC1 | 3.0.0.0-RC1 | 3.0.0.0-RC1 | Planned | [active/3.0.0-RC1.md](active/3.0.0-RC1.md) |
| 3.0.0.0 | 3.0.0.0 | 3.0.0.0 | Planned | [active/3.0.0.md](active/3.0.0.md) |

The `1.1.2.3` Core release and the `1.1.2.4` Extensions release are tracked
together because the published patch versions diverged.

## Status Definitions

- **Planned**: scope is proposed; no release gate has been met.
- **In progress**: implementation or validation is underway.
- **Release candidate**: scope is frozen; only blockers and release work remain.
- **Released**: artifacts and release notes are published.

## Planning Rules

1. Every non-trivial task links to a real issue or pull request in the owning repository.
2. Every removal names the exact artifact/module, replacement, deprecation period,
   and migration path.
3. A version is not release-ready until its release gates are checked and
   Core/Extensions versions are tested together.
4. Historical plans are kept under `archive/`; active work belongs under `active/`.
5. GitHub issues remain the execution tracker. This repository is the durable
   cross-repository release contract.

## Repositories

- [Agentic Spring AI](https://github.com/agentic-spring-ai/agentic-spring-ai)
- [Agentic Spring AI Extensions](https://github.com/agentic-spring-ai/agentic-spring-ai-extensions)
