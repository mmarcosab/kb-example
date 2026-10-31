# Engineering Knowledge Base

A centralized engineering knowledge base leveraging BMAD and Spec-Driven Development (SDD) to standardize architecture, development, testing, security, and observability. It provides reusable standards and workflows to guide AI agents across multiple repositories, improving software quality, consistency, and productivity.

## Purpose

This repository is the canonical source for reusable engineering knowledge. Application-specific requirements, implementation details, and deployment instructions remain in their respective code repositories.

## Core Principles

- Reusable knowledge over duplicated documentation.
- Validated standards over undocumented assumptions.
- Explicit specifications and acceptance criteria.
- Automated testing and verifiable quality.
- Human review for architectural decisions and policy changes.
- Incremental improvement through documented engineering lessons.

## Repository Structure

- `knowledge/` — engineering standards, architecture, and technical guidance.
- `policies/` — mandatory rules and exception management.
- `agents/` — responsibilities and guidelines for AI engineering roles.
- `workflows/` — reusable engineering processes.
- `examples/` — recommended practices and anti-patterns.
- `AGENTS.md` — instructions for AI coding agents.

## Knowledge Governance

Every substantive knowledge document should identify its status, scope, rationale, and verification criteria.

A pattern observed in an existing codebase is evidence of current practice, not automatically an approved engineering standard.

## Adoption

AI agents working in consumer repositories should:

1. Read the applicable repository instructions.
2. Consult relevant knowledge documents and policies.
3. Analyze the target repository before proposing changes.
4. Apply relevant standards and report deviations.
5. Verify changes through tests and appropriate quality checks.
6. Propose knowledge updates when new lessons are validated.

## BMAD Integration

BMAD will provide structured agents and workflows for engineering activities. Its generated configuration and runtime files should be managed according to the official installation process.

## Contributions

Changes to validated standards and mandatory policies require engineering review. Contributions should include rationale, examples, scope, and verification criteria.