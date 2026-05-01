# 🌿 BOTANICAL AI

> **Your Plants, Identified Instantly.**

![Last Updated](https://img.shields.io/badge/last%20updated-2026-05-01-brightgreen) ![Interactive Demo](https://img.shields.io/badge/demo-live%20samples-blue) ![License](https://img.shields.io/badge/license-MIT-green)

BOTANICA is an  plant identification web app that lets you scan any plant or flower and instantly get its name, care guide, pest diagnosis, and more — built on Solana and Base. Starting March 2026, BOTANICA evolves into a fully autonomous **AI Agent** with deep integration on **Solana** and **Base**.


---

## 🔗 Links

| Platform | URL |
|----------|-----|
| 🌐 Website | [botanica.web.id](https://botanica.web.id) |
| 𝕏 Twitter / X | [@botanicalai](https://x.com/botanicalai) |
| 🐙 GitHub | [github.com/studiobotanica](https://github.com/studiobotanica) |

---

## ✨ Features

### Free
| Feature | Description |
|---------|-------------|
| 🔍 Plant Identification | Identify 50,000+ species by photo or camera scan |
| 📖 Full Plant Profile | Common name, Latin name, origin, traits & family |
| 🔓 Free Plan | 3 scans per day — no credit card required |

### PRO
| Feature | Description |
|---------|-------------|
| 💧 Care Guide | Watering, light, soil, humidity & fertilizer tips |
| 🐛 Pest & Disease Scanner | Detect pests from photo + treatment advice |
| 📚 Scan History | Full record of all past identifications |
| 🌺 My Collection | Personal botanical collection with tags |
| 🪙 Mint Plant NFTs | Turn discoveries into on-chain NFT collectibles |
| ♾️ Unlimited Scans | No daily scan limits |

---

## 🚀 How It Works

1. **Upload or Scan** — Take a photo or upload any image of a plant, flower, leaf, or tree.
2. **AI Analysis** — AI analyzes against a database of 50,000+ species.
3. **Get Results** — Name, Latin name, origin, description, care guide & pest detection.
4. **Mint as NFT** *(PRO)* — Connect your wallet and mint your discovery as a digital collectible.

---

## 🤖 AI Agent Integration (Mar – May 2026)

BOTANICA is evolving beyond a plant scanner into a **fully autonomous AI Agent** — capable of monitoring, deciding, and executing on-chain actions on **Solana** and **Base** without manual input.

### Phase 1 — March 2026 · Agent Core `◎ Solana` `🔵 Base`

The BOTANICA Agent launches as an autonomous  runtime that:

- **Monitors** your plant collection continuously in the background
- **Detects** pest risks and watering schedule deviations proactively
- **Schedules** care tasks and pushes alerts without user triggers
- **Signs & broadcasts** on-chain notification messages to your Solana or Base wallet
- Runs on **Solana Devnet** and **Base Sepolia** during testnet phase

```
Agent Stack:
├── Runtime:     AI Agent Runtime — agentic loop
├── Chain 1:     Solana (Devnet → Mainnet)
├── Chain 2:     Base (Sepolia → Mainnet)
├── Wallet:      MPC Agent Wallet (non-custodial)
└── Trigger:     Event-based + time-based scheduling
```

---

### Phase 2 — April 2026 · Autonomous On-Chain Execution `◎ Solana` `🔵 Base`

The agent graduates from notifications to **real on-chain actions**:

| Action | Chain | Description |
|--------|-------|-------------|
| Auto-mint NFT | Solana / Base | Mints automatically when rare species detected |
| Metadata update | Solana / Base | Updates NFT care log metadata on-chain |
| SPL token transfer | Solana | Micro-payments for in-app agent services |
| ERC-20 payment | Base | In-app purchases via Base ERC-20 tokens |
| Cross-chain bridge | Solana ↔ Base | NFT & token bridging via Wormhole protocol |
| Agent Wallet (MPC) | Both | Non-custodial agent-controlled MPC wallet |

```
Agent Execution Flow:
User Collection → Agent Reads State
       ↓
AI Decision Engine
       ↓
On-Chain Action (Solana / Base)
       ↓
Transaction Signed by MPC Agent Wallet
       ↓
Result logged to User Dashboard
```

---

### Phase 3 — May 2026 · Multi-Agent Ecosystem & Marketplace `◎ Solana` `🔵 Base`

The agent ecosystem scales to a **multi-agent architecture** with a public marketplace:

- **Sub-agent spawning** — Main agent deploys specialized agents (Care Agent, Pest Agent, Market Agent)
- **Agent Marketplace** — Publish, subscribe, and monetize custom plant agents
- **Smart contract subscriptions** — On-chain recurring payments via Solana SPL & Base ERC-20
- **DAO governance** — Community votes on agent upgrades via on-chain proposals
- **On-chain audit log** — Every agent decision recorded immutably on-chain

```
Multi-Agent Architecture:
BOTANICA Root Agent
├── Care Agent          ← Watering, light, fertilizer
├── Pest Agent          ← Disease detection, treatment
├── Market Agent        ← NFT pricing, rarity scoring
└── Bridge Agent        ← Cross-chain asset management (Wormhole)
```

---

## 📅 Full Roadmap

| Period | Milestone | Status |
|--------|-----------|--------|
| Jan 2026 | BOTANICA v1.0 — Core Launch | ✅ Shipped |
| Feb 2026 | Mobile optimization & social layer | ✅ Shipped |
| **Mar 2026** | **AI Agent Phase 1 — Agent Core (Solana + Base)** | 🔄 Active |
| **Apr 2026** | **AI Agent Phase 2 — Autonomous On-Chain Execution** | 🔜 Upcoming |
| **May 2026** | **AI Agent Phase 3 — Multi-Agent Marketplace** | 🔜 Upcoming |
| Q3 2026+ | Native mobile apps + DePIN sensor integration | 🔭 Planned |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| AI Vision | AI Vision API |
| AI Agent Runtime | AI Agentic Loop |
| Frontend | HTML, CSS, Vanilla JavaScript |
| Plant Database | 50,000+ species |
| Chain 1 | Solana (SPL tokens, Metaplex NFT) |
| Chain 2 | Base (ERC-20, ERC-721) |
| Cross-chain | Wormhole Protocol |
| Agent Wallet | MPC (non-custodial) |
| Web3 Auth | MetaMask, WalletConnect, Coinbase Wallet, Trust Wallet |
| Fonts | Cormorant Garamond, DM Sans, DM Mono |

---

## 📦 Project Structure

```
botanica/
├── index.html              ← single-file static app
├── README.md
├── LICENSE
├── SECURITY.md             ← vulnerability disclosure policy
├── CONTRIBUTING.md
├── .gitignore
├── .github/
│   ├── dependabot.yml
│   ├── ISSUE_TEMPLATE/
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── workflows/          ← CI: CodeQL, gitleaks, html-validate, link-check, GH Pages
└── assets/                  (optional — referenced from README)
    ├── botanica_logo.jpg
    └── ...
```

## 🛡️ Security & CI

The repo ships with a hardened CI pipeline:

| Workflow | Purpose |
|----------|---------|
| `codeql.yml` | Weekly + per-PR CodeQL static analysis (`security-and-quality`) for JavaScript |
| `gitleaks.yml` | Detect accidental secret leaks on every push |
| `html-validate.yml` | Lint `index.html` markup on every push |
| `link-check.yml` | Catch broken links with Lychee |
| `pages-deploy.yml` | Auto-publish `main` to GitHub Pages |
| `dependabot.yml` | Weekly bump of GitHub Actions versions |

The frontend also enforces a strict **Content-Security-Policy**, escapes
all AI/user data before injecting into the DOM, and follows the
disclosure policy in [SECURITY.md](./SECURITY.md).

---

## 📱 Mobile Support

- Hamburger navigation drawer on small screens
- Touch-friendly scan & upload interface
- Live camera access for plant scanning
- Adaptive grid layouts for all screen sizes

---

## 🧪 Testnet

| Environment | Status |
|-------------|--------|
| Plant Scan Sandbox | ✅ Live |
| NFT Mint — Solana Devnet | 🔧 In Progress |
| NFT Mint — Base Sepolia | 🔧 In Progress |
| AI Agent — Solana Devnet | 🚀 March 2026 |
| AI Agent — Base Sepolia | 🚀 March 2026 |
| Cross-chain Bridge (Wormhole) | 🔧 In Progress |

---

## 📊 Stats

- **50,000+** Plant species in database
- **98%** Identification accuracy
- **12,000+** Happy users

---

## 💡 Why We Built It

Most people encounter plants every day but have no idea what they're looking at. We built BOTANICA to close that gap — giving everyone instant, accurate botanical knowledge right from their phone. With the AI Agent layer launching in March 2026, BOTANICA becomes the first autonomous botanical intelligence — a system that doesn't just identify plants but actively cares for them, transacts on your behalf, and builds a living, on-chain record of your botanical world.

---

## 📄 License

© 2025–2026 BOTANICA. All rights reserved.
built on Solana and Base Vision · Solana · Base · Web3 Ready
