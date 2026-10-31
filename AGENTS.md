# Engineering Knowledge — Agent Instructions

## Mission

Use this repository as the canonical source for reusable engineering principles, standards, policies, architectural decisions, and workflows.

## Before Working

1. Read `README.md` and `knowledge/README.md`.
2. Identify the task domain and relevant documentation.
3. Read applicable mandatory policies.
4. Distinguish validated standards from proposals and observations.
5. Inspect the target repository before recommending or implementing changes.
6. Consult only the knowledge documents relevant to the task.

## Source of Truth

- `policies/` — engineering policies and exception rules.
- `knowledge/` — validated standards and technical guidance.
- `knowledge/decisions/` — architecture decision records.
- Consumer repository — local requirements, implementation, and constraints.

If sources conflict, report the conflict instead of silently overriding a policy or inventing a resolution.

## Engineering Rules

- Do not invent requirements or architecture decisions.
- Prefer existing, validated patterns when compatible with applicable policies.
- Justify new dependencies and material architectural changes.
- Define acceptance criteria for non-trivial changes.
- Add or update automated tests for changed behavior.
- Evaluate security, performance, and observability impacts.
- Keep changes scoped to the requested task.
- Report assumptions, risks, and verification results.
- Never expose secrets, credentials, or sensitive data.

## Knowledge Maintenance

- Treat new findings as proposals until reviewed.
- Never silently overwrite an approved standard.
- Reference the applicable knowledge documents when applying a standard.
- Record rationale, evidence, and trade-offs for architectural decisions.
- Propose documentation updates separately when new lessons emerge.