# Security Policy

## Reporting a vulnerability

**Do not open public GitHub issues for security vulnerabilities.**

Email **security@qabasone.com**, or open a private GitHub Security Advisory on the affected repository if you have access.

Include:

- Affected repository, version, or commit
- Steps to reproduce
- Impact assessment

We aim to acknowledge within **3 business days** and provide a remediation timeline for confirmed issues.

## Scope

This organization policy applies to repositories under [github.com/qabasone](https://github.com/qabasone) that do not define their own `SECURITY.md`. Product repos that ship a local policy (for example `qabasone-api`, `qabasone-app`, `qabasone-dash`) take precedence for that repository.

## Secure development expectations

Aligned with Atlas engineering governance (`qabasone-atlas`):

- Never commit secrets, `.env` files, or production credentials
- Prefer Dependabot / dependency review and CI quality gates on application repos
- Secret scanning and push protection should remain enabled where available
- Financial or auth-sensitive changes should follow Atlas authorization and API contract rules

## Supported versions

Unless a repository states otherwise: only the default branch (`main`) and tagged releases are supported.
