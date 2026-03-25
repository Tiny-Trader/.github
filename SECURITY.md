# Security Policy

## Supported Versions

| Package | Supported |
|---|---|
| tt-connect (latest) | Yes |
| tt-connect (older) | No — upgrade to latest |

## Reporting a Vulnerability

**Do not open a public issue for security vulnerabilities.**

Email **security@tinytrader.in** with:

1. Package name and version
2. Description of the vulnerability
3. Steps to reproduce
4. Impact assessment (if known)

You will receive an acknowledgement within 48 hours. We aim to release a fix within 7 days for critical issues.

## Scope

We care about vulnerabilities in:

- Authentication and session handling
- Credential storage and leakage
- Order placement and modification (unintended trades)
- WebSocket data integrity
- Dependency vulnerabilities

## Out of Scope

- Broker API bugs (report to the broker directly)
- Rate limiting or throttling behavior
- Issues requiring physical access to the machine

## Disclosure

We follow coordinated disclosure. Once a fix is released, we will credit the reporter (unless they prefer anonymity) in the release notes.
