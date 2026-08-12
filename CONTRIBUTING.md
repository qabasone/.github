# Contributing to QabasOne

Thank you for your interest in QabasOne.

## Authority

**Atlas governs engineering.** Architecture, domain boundaries, API contracts, branching, and contribution rules live in the private `qabasone-atlas` repository. Deviations require an ADR.

This file is the organization default for repositories that do not ship their own `CONTRIBUTING.md`.

## External contributors

Most application repositories are **private**. Public work is limited (for example [`qabasone-ui`](https://github.com/qabasone/qabasone-ui)).

1. Open an issue on a **public** repository describing the problem or proposal.
2. Wait for maintainer feedback before investing in a large PR.
3. We are selective about outside PRs while the core platform remains private.

## Internal / invited collaborators

Follow Atlas contribution governance and each repository’s local guidance (`AGENTS.md`, `CODEOWNERS`, `CONTRIBUTING.md`, branch rulesets) where present.

High-level expectations from Atlas:

- Work lands through pull requests — not direct commits to protected branches
- Prefer `feat/*`, `fix/*`, and `hotfix/*` branch naming
- Keep CI green before merge
- Do not weaken repository security or release controls without an ADR

## Security reports

See [`SECURITY.md`](./SECURITY.md). Do not file public issues for unpatched vulnerabilities.

## Product naming

Use consistent product naming in docs and UI copy:

| Name | Use for |
| --- | --- |
| **QabasOne** | Product / platform |
| **Al Qabasy** / **Al Qabasy Trading** | Company |
| **AlQabasyGo** | Fleet / driver logistics surface |

Prefer `https://www.qabas.one` for the company site, `https://dash.qabas.one` for operations, and `https://app.qabas.one` for drivers.
