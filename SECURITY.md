# Security Policy

## Supported Versions

The latest commit on `main` is the only supported version. Older
commits do not receive security updates.

| Version    | Supported |
|------------|-----------|
| `main`     | ✅        |
| Older tags | ❌        |

## Reporting a Vulnerability

If you discover a security vulnerability in BOTANICA, **please do not
open a public GitHub issue**. Instead, report it privately so we can
fix it before any public disclosure.

Preferred channels (in order):

1. GitHub Security Advisories — open a private report at
   <https://github.com/studiobotanica/Botanica/security/advisories/new>.
2. Direct message to **[@botanicalai](https://x.com/botanicalai)** on X.

When reporting, please include:

- A clear description of the issue and its impact.
- Steps to reproduce (URLs, payloads, screenshots if helpful).
- Affected commit hash or deployed URL.
- Your name / handle if you would like credit in the advisory.

We aim to:

- Acknowledge new reports within **72 hours**.
- Provide a remediation plan within **7 days** for high-impact issues.
- Publicly credit reporters in the advisory unless they request otherwise.

## Out of Scope

The following are generally **not** considered vulnerabilities:

- Self-XSS that requires the victim to paste code into devtools.
- Missing security headers on third-party domains we don't control.
- Issues affecting unsupported browsers (IE, Opera Mini, etc.).
- Best-practice suggestions without a working PoC.

## Hardening Notes

- API calls to third parties **must not** include API keys directly in
  the static frontend. All AI / chain calls must go through a backend
  proxy.
- All dynamic strings injected into the DOM must be escaped (see the
  `escapeHtml` helper in `index.html`).
- External images, fonts, and badges should use HTTPS and `loading="lazy"`
  where possible.
