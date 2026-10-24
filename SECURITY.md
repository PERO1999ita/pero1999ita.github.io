# Security Policy

## Supported Versions

Only the latest commit on the `main` branch of this repository is actively maintained and supported.

| Version / Branch | Supported          | Status             |
| ---------------- | ------------------ | ------------------ |
| `main`           | :white_check_mark: | Actively Maintained |
| Other branches   | :x:                | Unsupported        |

---

## Scope

### In-Scope
- Vulnerabilities within code hosted on `https://pero1999ita.github.io/` (DOM-based XSS, injection vectors, open redirects).
- Misconfigurations or security gaps in client-side scripts, styles, or external resource loaders.
- Insecure external references (missing `rel="noopener noreferrer"`).
- Accidental exposure of secrets, tokens, or credentials in git history.

### Out-of-Scope
- Infrastructure-level Denial of Service (DoS/DDoS) targeting GitHub Pages or DNS providers.
- Social engineering, phishing, or physical attacks targeting contributors or staff.
- Self-XSS or attacks requiring root/jailbroken client devices.
- Automated vulnerability scanner spam without actionable proof-of-concept.

---

## Reporting a Vulnerability

We value coordinated vulnerability disclosure. If you discover a vulnerability, please do **not** disclose it publicly.

1. **Preferred Channel**:
   - **Discord Hub**: [discord.bedcraftmc.eu](https://discord.bedcraftmc.eu/) — Open a private support ticket or contact **PERO1999** (`pero1999`).
   - **GitHub**: Open a private advisory under the [Security Advisories](https://github.com/PERO1999ita/pero1999ita.github.io/security/advisories) tab for [@PERO1999ita](https://github.com/PERO1999ita).
2. **Report Details**:
   - Detailed summary of the potential issue.
   - Step-by-step reproduction guide or Proof of Concept (PoC).
   - Expected impact and proposed remediation (if available).

---

## Response Timeline & Commitment

- **Initial Triage**: Within 24–48 hours.
- **Remediation**: Patches deployed within 7 business days depending on severity.
- **Disclosure**: Public disclosure coordinated once production fixes are verified.
- **Credit**: Responsible reporters will receive formal acknowledgment in release notes and commit history.
