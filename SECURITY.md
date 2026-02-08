# Security Policy

This policy applies to all repositories under the [github.com/hostelkhata](https://github.com/hostelkhata) organization.

## Reporting a Vulnerability

If you discover a security vulnerability in any hostelkhata project, please report it responsibly.

**Do NOT:**
- Open a public GitHub issue
- Post about it on social media
- Exploit the vulnerability

**Do:**
- Email us at [hello@hostelkhata.in](mailto:hello@hostelkhata.in) with subject "SECURITY: [repo-name]"
- Include detailed steps to reproduce
- Give us reasonable time to respond (48 hours)

## What We Consider Security Issues

- XSS vulnerabilities
- CSRF vulnerabilities
- Data exposure or leakage (tenant/financial data)
- Authentication/authorization bypasses
- Injection attacks (SQL, command, etc.)
- Supabase RLS bypass
- Sensitive data in client-side code or logs
- Dependency vulnerabilities (critical/high severity)
- DPDP Act compliance violations

## What We Don't Consider Security Issues

- Missing security headers on the static landing page
- Rate limiting on unauthenticated endpoints (pre-launch)
- Clickjacking on non-sensitive pages
- Theoretical attacks without proof of concept

## Response Timeline

- **Acknowledgment:** Within 48 hours
- **Initial assessment:** Within 7 days
- **Fix timeline:** Depends on severity (critical: 24-48h, high: 7 days, medium: 30 days)

## Recognition

We appreciate security researchers who help keep hostelkhata and its users' data safe.

---

**Contact:** [hello@hostelkhata.in](mailto:hello@hostelkhata.in)
**Website:** [hostelkhata.in](https://hostelkhata.in)
**Twitter:** [@hostelkhata](https://x.com/hostelkhata)
