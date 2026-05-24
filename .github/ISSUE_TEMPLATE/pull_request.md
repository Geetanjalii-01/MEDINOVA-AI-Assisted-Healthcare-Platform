---
name: 🔀 Pull Request
about: Submit a code change for MEDINOVA 
title: '[PR] '
labels: ''

---

## 📋 Summary
A clear and concise description of what this PR does.

Closes # (issue)

---

## 🔀 Type of Change
What type of change does this PR introduce? (check all that apply)

- [ ] 🐛 Bug fix (non-breaking change that fixes an issue)
- [ ] 🚀 New feature (non-breaking change that adds functionality)
- [ ] 💥 Breaking change (fix or feature that would cause existing functionality to change)
- [ ] 📦 Dependency update (upgrading or replacing a library)
- [ ] 🎨 UI/UX improvement (visual or experience changes)
- [ ] ♻️ Refactor (code restructuring without behavior change)
- [ ] 🧪 Tests (adding or improving test coverage)
- [ ] 📝 Documentation (README, comments, or other docs)
- [ ] 🔐 Security fix

---

## 📍 Affected Module
Which part of the codebase does this PR touch? (check all that apply)

- [ ] `react-app/` — Frontend (React)
- [ ] `server/` — Backend API (Node.js / Express)
- [ ] `py side/` — AI/ML Microservices (Python / Flask)
- [ ] `blockchain/` — Smart Contracts (Ethereum)
- [ ] Configuration / Environment
- [ ] Documentation only

---

## 🛠️ What Changed
Provide a detailed breakdown of what was changed and why.

- **Changed:** ...
- **Added:** ...
- **Removed:** ...
- **Fixed:** ...

---

## 🧪 How Has This Been Tested?
Describe the tests you ran to verify your changes.

- [ ] Tested locally on `localhost:3000`
- [ ] Tested Flask AI service(s) independently
- [ ] Tested blockchain interaction (transaction / block mining)
- [ ] Tested on mobile / responsive layout
- [ ] Ran `npm audit` — no new vulnerabilities introduced
- [ ] Ran `pip-audit` — no new vulnerabilities introduced (if Python changes)

**Test environment:**
| Field | Value |
|-------|-------|
| OS | e.g. Ubuntu 22.04 |
| Node.js | e.g. 16.13.1 |
| Python | e.g. 3.9.7 |
| Browser | e.g. Chrome 120 |

---

## 📸 Screenshots / Demo
If this PR includes UI changes, please add before/after screenshots or a short screen recording.

| Before | After |
|--------|-------|
| | |

---

## ✅ Checklist
Please confirm the following before requesting a review:

- [ ] My code follows the existing code style of this project
- [ ] I have commented my code in complex or non-obvious areas
- [ ] I have updated the README or documentation if needed
- [ ] My changes do not introduce new console errors or warnings
- [ ] I have not committed any API keys, secrets, or `.env` files
- [ ] I have linked the related issue above
- [ ] I have requested a review from at least one maintainer

---

## ⚠️ Deprecation Awareness
If your PR updates or replaces a deprecated dependency, please note it here and confirm backward compatibility has been considered.

> e.g. "Updated `react-scripts` from 4.x to 5.x — tested that existing routes and components still render correctly."

---

## 💡 Additional Notes
Anything else reviewers should know — trade-offs made, follow-up tasks, or related PRs.
