# Security Policy

## Supported Versions

| Branch | Supported |
| ------ | --------- |
| `main` | Yes |
| Other branches or forks | No |

The `main` branch is the supported branch for security updates. Older branches and forks may not receive fixes.

---

## Reporting a Vulnerability

If you discover a security vulnerability, please report it responsibly.

- Do not open a public GitHub issue for security reports.
- Use GitHub's private vulnerability reporting or contact the maintainer privately through GitHub.
- Include a clear description, steps to reproduce, potential impact, and any suggested fix.

You can expect an initial acknowledgement within 3-5 business days. Confirmed issues will be reviewed and addressed based on severity and project maintainability.

---

## Security Guidelines

For contributors and users:

- Do not commit secrets, API keys, credentials, or `.env` files.
- Validate and sanitize user-provided vehicle, customer, sales, or account data.
- Review dependencies before adding them, and keep them updated where practical.
- Avoid exposing private customer, transaction, or dealership information in test data, screenshots, logs, or issues.
