# Security Policy

Security is a shared responsibility across EOS repositories.

## Reporting a vulnerability

**Do not disclose suspected vulnerabilities in public issues, pull requests, discussions, or commits.**

Use GitHub's private vulnerability reporting or private security advisory feature for the affected repository when available. If that feature is unavailable, contact the organization owner or repository maintainers through a private GitHub channel and include only the information needed to reproduce and assess the issue.

Please include, when safe:

- Affected repository, component, and version or commit.
- Impact and plausible attack scenario.
- Minimal reproduction steps or proof of concept.
- Suggested mitigation, if known.

Do not include real credentials, customer data, or unnecessary personal information.

## Handling

Maintainers should acknowledge reports privately, assess severity and affected versions, coordinate remediation, and agree on disclosure timing with the reporter. Do not publish exploit details before a fix or mitigation is available.

## Secure contribution requirements

- Never commit secrets, tokens, private keys, or production data.
- Use least-privilege credentials and rotate exposed credentials immediately.
- Validate untrusted input and enforce authorization at trust boundaries.
- Pin and review dependencies and workflow actions according to repository policy.
- Record security-relevant changes and validation evidence in the pull request.
