# Contributing to BOTANICA

Thanks for your interest in contributing! 🌿

BOTANICA is a static, single-file web application (no build step). Contributions
focus on UI polish, accessibility, security hardening, and documentation.

## Getting Started

1. Fork the repo and clone your fork.
2. Open `index.html` directly in your browser, **or** serve the folder:
   ```bash
   python3 -m http.server 8080
   # then open http://localhost:8080/
   ```
3. Make your changes on a feature branch:
   ```bash
   git checkout -b feat/short-description
   ```

## Coding Style

- HTML / CSS / JS live in a single `index.html` file by design — keep it that way unless we adopt a build pipeline.
- Use the existing CSS custom properties (`--moss`, `--forest`, `--sage`, etc.) instead of hard-coded colors.
- Indent with **2 spaces**.
- Wrap inline JS handlers sparingly — prefer the existing `state` pattern.
- **Never** insert untrusted strings into `innerHTML` without passing them through `escapeHtml()`.

## Security Rules

- Never commit API keys, tokens, secrets, or wallet private keys.
- Calls to third-party APIs (Anthropic, RPC providers, etc.) must go through a backend proxy. The frontend is public; anything in it is public.
- All external resources should use HTTPS.
- Run the workflows locally if you can:
  ```bash
  npx html-validate index.html
  npx lychee './**/*.md' './**/*.html'
  ```

## Pull Requests

- Open a PR against `main`.
- Fill in the PR template checklist.
- CI must pass (CodeQL, gitleaks, html-validate, link-check).
- Add before/after screenshots for UI changes.

## Reporting Bugs / Vulnerabilities

- For non-security bugs, open a GitHub Issue using the template.
- For **security vulnerabilities**, follow [SECURITY.md](./SECURITY.md) — do not open a public issue.

## Code of Conduct

Be respectful. Disagree about ideas, not people. Personal attacks, harassment, or discrimination of any kind will result in removal from the project.
