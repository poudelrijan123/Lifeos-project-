# Security Policy

## Current status

LifeOS is an early-stage demo. It is not suitable for sensitive personal, medical, or account information.

## Reporting a vulnerability

Please do not publish credentials, personal data, or sensitive health information in a public issue. Use GitHub's private vulnerability reporting feature if it is enabled for this repository.

## Production readiness requirements

Before production use, independently verify:
- Real authentication and secure session lifecycle
- Server-side authorization and database Row Level Security
- No privileged secrets in browser code
- Validation and safe handling of device and health data
- HTTPS, security headers, dependency scanning, and recovery procedures
