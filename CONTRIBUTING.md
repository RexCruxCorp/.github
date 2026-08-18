# Contributing to RexCrux

Thanks for contributing. This document covers the day-to-day workflow for working across RexCrux repositories.

## Branching

- `main` is always deployable. Do not commit directly to `main` except for trivial, pre-approved changes.
- Create a branch per change: `git checkout -b <type>/<short-description>` (e.g. `feat/qphase-gate-encoder`, `fix/foldshield-null-mutation`).

## Commits

- Keep commits small and focused on one logical change.
- Write commit messages in the imperative mood ("Add X", "Fix Y") and explain why when it isn't obvious from the diff.

## Pull Requests

1. Push your branch and open a PR against `main`.
2. Fill out the PR template completely so reviewers can scope the review without back-and-forth.
3. Request review from at least one other maintainer.
4. Make sure CI checks pass before merging.
5. Prefer squash-merge to keep `main` history readable.

## Code Style

- Run the project's linter/formatter before committing.
- Follow the existing conventions in whichever repo you're working in. FoldShield++, RainDrop, SynBraid, QPhase, SEE Engine, SME-BS, and UL DSL/USL each document their own local conventions in that repo's README.

## Reporting Bugs or Requesting Features

Use the issue templates provided. Include enough detail (repro steps, environment, expected vs. actual behavior) for a reviewer to act without follow-up questions.

## Security Issues

Do not open a public issue for security vulnerabilities. See [SECURITY.md](./SECURITY.md) instead.

## Questions

Reach out to the maintainers at info@rexcrux.com.
