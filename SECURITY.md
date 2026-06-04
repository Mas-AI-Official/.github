# Security Policy

MAS-AI projects are security-sensitive because they involve AI agents, automation, and workflow orchestration.

## Reporting

Please report vulnerabilities privately through GitHub Security Advisories when available. If advisories are not enabled on the affected repository, contact Masoud Masoori through the public profile links.

Do not open public issues for exploitable vulnerabilities, secrets, account takeover paths, prompt-injection bypasses, or deployment credentials.

## Scope

In scope:

- authentication and authorization flaws
- secret exposure or unsafe configuration defaults
- prompt-injection paths that can trigger unsafe tool use
- data exfiltration, tenant isolation, or audit-log bypasses
- CI/CD workflow weaknesses that can leak tokens or run untrusted code with write permissions

Out of scope:

- cosmetic bugs
- denial-of-service reports without a practical impact path
- scanner-only findings without a reachable exploit path

## Baseline

Repositories should use least-privilege GitHub Actions permissions, Dependabot, branch cleanup after merge, and security scanning appropriate to the stack.
