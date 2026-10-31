# Mandatory Engineering Rules

**Status:** Proposed  
**Scope:** Initial baseline for AI-assisted engineering across consuming repositories.

These rules require engineering review before being treated as approved organization-wide controls.

## General

- Do not invent requirements or architectural decisions.
- Respect repository-specific instructions and constraints.
- Keep changes focused on the requested task.
- Explain material assumptions, risks, and trade-offs.

## Security and Privacy

- Never commit credentials, access tokens, private keys, or secrets.
- Do not expose personal, customer, or confidential data in documentation or examples.
- Follow the consuming repository's approved security and data-handling requirements.

## Quality

- Define verifiable acceptance criteria for non-trivial changes.
- Add or update automated tests for changed behavior.
- Run relevant tests and quality checks.
- Report what was verified and what was not.
- Never claim successful verification without evidence.

## Architecture

- Evaluate compatibility before changing APIs, events, schemas, or persisted data.
- Document material architecture decisions through an ADR or the repository's approved process.
- Justify new dependencies and infrastructure.

## Exceptions

Exceptions to validated policies must follow `exceptions.md`.

Until this document is approved, treat it as proposed guidance rather than an enforced organizational policy.