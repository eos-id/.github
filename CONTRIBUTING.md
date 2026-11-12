# Contributing to Enterprise-OS

Thank you for helping improve EOS. This guide defines the baseline contribution process; repository-specific instructions take precedence when they are more specific.

## Before starting

1. Read the target repository's README, contribution guide, and security policy.
2. Search existing issues, pull requests, architecture decisions, and implementation before proposing new work.
3. Identify the affected capability, owner, contracts, and downstream consumers.
4. For material changes, describe the problem and expected outcome before implementation.

## Change expectations

- Prefer the smallest coherent, reviewable change.
- Reuse existing domain concepts, APIs, workflows, and primitives where appropriate.
- Do not introduce duplicate Work identity, workflow engines, registries, or core primitives without an approved, evidence-backed decision.
- Preserve established compatibility and frozen-core boundaries. Changes to protected architecture require an explicit decision and approval from the responsible maintainers.
- Keep secrets, credentials, personal data, and production data out of commits, issues, logs, and test fixtures.
- Add or update tests and documentation when behavior or contracts change.

## Pull requests

A pull request should explain:

- **Context:** problem, user or operational impact, and related issue/work identifier.
- **Scope:** what changed and what deliberately did not change.
- **Architecture:** affected bounded contexts, APIs, events, dependencies, and compatibility.
- **Validation:** commands executed and their outcomes; do not claim checks that were not run.
- **Evidence:** test output, screenshots, traces, or other relevant evidence, with sensitive information removed.
- **Risk and rollout:** migration, security, observability, rollback, and release considerations where applicable.

Keep pull requests focused. Request review from the code owners or maintainers responsible for the affected area. Do not merge your own change where repository policy requires independent review.

## Review and merge

Reviewers assess correctness, maintainability, security, compatibility, tests, documentation, and evidence. Passing automation is necessary where configured, but does not replace domain-owner approval or required governance decisions.

Never bypass required checks, protections, or review requirements. If a control is unavailable due to GitHub plan or repository configuration, document a compensating process rather than implying the control is active.

## Questions

Use repository Discussions or an issue for non-sensitive questions. Follow [SECURITY.md](SECURITY.md) for vulnerability reports.
