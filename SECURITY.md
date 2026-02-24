# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| 0.1.x   | Yes       |

## Reporting a Vulnerability

SentinelCore is a penetration testing platform, but we take the security of the platform itself seriously.

If you discover a security vulnerability in SentinelCore (the platform code, gateway, daemon, or web dashboard), please report it responsibly:

1. **Do NOT** open a public GitHub issue
2. Email: **security@sentinelcore.dev** (or contact the maintainer directly)
3. Include:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if any)

We aim to acknowledge reports within 48 hours and provide a fix within 7 days for critical issues.

## Scope

The following are in scope for security reports:

- Gateway authentication bypass
- WebSocket injection / unauthorized RPC calls
- Privilege escalation in the daemon
- Scope enforcer bypass (allowing out-of-scope tool execution)
- XSS/injection in the web dashboard
- Dependency vulnerabilities with a viable exploit path

## Out of Scope

- Security tools themselves (nmap, sqlmap, etc.) — these are third-party
- Denial of service against the local daemon
- Social engineering
- Issues in development/test configurations
