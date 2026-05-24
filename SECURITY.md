# Security Policy

## ⚠️ Deprecation Notice

This project was built in 2022 and its dependencies are currently **outdated**. A full security audit and dependency refresh is planned as part of **v3**. We strongly recommend **not deploying this project in a production environment** until the update is complete.

---

## Supported Versions

Only the latest release is actively maintained. Older versions are no longer supported with security patches.

| Version | Supported |
|---------|-----------|
| 3.x (coming soon) | ✅ |
| 1.x | ❌ |
| < 1.0 | ❌ |

---

## Reporting a Vulnerability

If you discover a vulnerability in MEDINOVA , please  **follow responsible disclosure practices**.

### How to Report

Send a private email to the project maintainer:

📧 **geet.anjali1022@gmail.com**

Please include:
- A clear description of the vulnerability
- Steps to reproduce the issue
- The affected component (`react-app/`, `server/`, `py side/`, or `blockchain/`)
- Any potential impact or exploit scenario you've identified
- Your suggested fix (optional but appreciated)

### After Review

- If the vulnerability is **accepted**, we will work on a fix, credit you in the release notes (unless you prefer anonymity), and publish a patch as soon as possible.
- If the vulnerability is **declined** (e.g. out of scope or not reproducible), we will explain our reasoning clearly.

---

## Known Security Considerations

Given the nature of this application, please pay special attention to:

- 🔐 **Authentication** — Face ID (TensorFlow), LinkedIn OAuth, and JWT tokens
- 🪪 **ID Card OCR** — Nanonets API handles sensitive personal identity data
- 🔗 **Blockchain** — Ethereum smart contracts managing patient medical records
- 💳 **Payments** — Stripe API integration for subscriptions and transactions
- 🗄️ **Database** — MongoDB storing user, appointment, and medical data

---

## Scope

The following are **in scope** for security reports:

- Authentication bypass or session vulnerabilities
- Unauthorized access to patient medical records
- Smart contract vulnerabilities (reentrancy, overflow, etc.)
- API key or credential exposure in the codebase
- Injection attacks (NoSQL, command injection)
- Insecure direct object references (IDOR)


---

## Security Best Practices for Contributors

If you're contributing to this project, please ensure:

- Never commit API keys, secrets, or credentials — use `.env` files
- Always validate and sanitize user inputs on both client and server
- Follow the principle of least privilege for database and API access
- Keep dependencies updated — run `npm audit` and `pip-audit` regularly

---

*For general questions or non-security bugs, please open a [GitHub Issue](https://github.com/Geetanjalii-01/MEDINOVA-AI-Assisted-Healthcare-Platform/issues).*
