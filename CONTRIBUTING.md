# Contributing to Sw7l Projects

Sw7l Projects builds software for AbuSwe7l community operations, Discord systems, web tooling, APIs, automation, and security-minded engineering work.

Keep contributions small, clear, and easy to review.

## Good Contributions

| Area               | Good examples                                                          |
| ------------------ | ---------------------------------------------------------------------- |
| Bot features       | Commands, moderation improvements, tickets, role flows, event handling |
| Web and dashboards | Admin screens, forms, UI fixes, responsive behavior                    |
| Backend            | API endpoints, validation, workers, webhooks, integration fixes        |
| DevOps             | CI, Docker, deploy scripts, monitoring, runbooks                       |
| Security           | Dependency cleanup, secret hygiene, safer defaults, defensive checks   |
| Docs               | Setup steps, examples, architecture notes, troubleshooting             |

## Flow

1. Read the target repository README first.
2. Pick a focused task. If scope is unclear, open an issue or ask a maintainer.
3. Keep the PR small enough to review properly.
4. Add tests or a clear manual verification note.
5. Update docs when behavior, setup, commands, or ownership changes.

## Pull Request Standard

A useful PR answers four questions:

- What changed?
- Why was it needed?
- How was it tested?
- What risk should reviewers check?

No secrets in diffs. Never commit tokens, `.env` files, private keys, production credentials, or private Discord configuration.

## Review Standard

Review for correctness first, then readability, security, maintainability, and docs. If a change affects production, bot permissions, Discord moderation, authentication, deployment, or data storage, call that out in the PR.

## Security

Don't report vulnerabilities in public issues. Email `support@abuswe7l.com` with reproduction steps, impact, affected repository, and any safe proof of concept.
