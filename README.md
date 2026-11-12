# eos-id — Enterprise-OS Governance

This repository is the organization-wide entry point for governance and community standards across the Enterprise-OS ecosystem.

## Purpose

Provide consistent contribution, security, support, and collaboration defaults without coupling the organization to a particular runtime, interface, agent framework, or implementation.

## Documents

- [Organization profile](profile/README.md)
- [Contributing](CONTRIBUTING.md)
- [Security policy](SECURITY.md)
- [Code of conduct](CODE_OF_CONDUCT.md)
- [Support](SUPPORT.md)
- [Pull request template](.github/PULL_REQUEST_TEMPLATE.md)
- [Bug report template](.github/ISSUE_TEMPLATE/bug_report.yml)
- [Feature proposal template](.github/ISSUE_TEMPLATE/feature_request.yml)

## Governance principles

1. Work continuity is preserved while execution authority remains replaceable.
2. Existing capabilities and primitives are reused before new abstractions are proposed.
3. Frozen-core boundaries are respected; exceptions require explicit decisions.
4. Changes are traceable from requirements and decisions through implementation, tests, and evidence.
5. Security, privacy, least privilege, and operational readiness are part of engineering quality.
6. Repository boundaries follow real ownership and lifecycle needs; avoid unnecessary fragmentation.

## Scope and limitations

These files establish baseline documentation and contribution conventions. They do **not** automatically configure organization permissions, repository rulesets, branch protection, required checks, CODEOWNERS enforcement, secret scanning, or deployment environments. Those controls must be assessed and configured separately based on repository ownership, GitHub plan, and operational requirements.

The EOS engineering state repository remains engineering memory for development history, decisions, experiments, evidence, and open issues. It is not live runtime state and is not replaced by this governance repository.
