# Security Policy

## Supported Content

This repository provides reference CI/CD pipeline definitions and documentation.

## Reporting a Vulnerability

If you discover a security issue, do not open a public issue.

Please report privately to the repository maintainers with:

- A description of the issue
- Steps to reproduce
- Potential impact
- Suggested remediation (if available)

The maintainers will acknowledge receipt and investigate as quickly as possible.

## Security Best Practices for This Repo

- Never commit real secrets, tokens, or connection strings.
- Use platform secret stores (GitHub Secrets, Azure DevOps variable groups).
- Prefer OIDC/workload identity over long-lived credentials.
- Keep dependencies and actions/tasks up to date.
- Require approvals for production deployments.

## Disclosure Process

1. Private report received.
2. Triage and impact assessment.
3. Fix prepared and validated.
4. Coordinated disclosure after mitigation.
