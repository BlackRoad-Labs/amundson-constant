# Security Policy

## Reporting Vulnerabilities

Email: alexa@blackroad.io

Do NOT open public issues for security vulnerabilities.

## Supported Versions

Only the latest version on `main` is supported.

## Security Practices

- All secrets in env files with chmod 600
- No API tokens in code
- WireGuard for inter-node traffic
- Cloudflare proxy for all public endpoints
- UFW on all exposed nodes
- SSH key auth only (password auth disabled)
- Quarterly SSH key audit

---
*BlackRoad OS, Inc. All rights reserved.*
