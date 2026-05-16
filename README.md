# Push.

**Deploy your AI-built apps to GitHub Pages from your iPhone — no laptop, no terminal, one tap.**

[**Try Push →**](https://tinq777.github.io/push/)

---

## What is Push?

Push is a free PWA (Progressive Web App) that lets anyone deploy apps built with Claude, ChatGPT or any AI tool directly from their iPhone. Add it to your home screen, connect your GitHub account once, and deploy any ZIP or HTML file in seconds.

No laptop. No terminal. No technical knowledge required.

---

## How it works

1. **Ask an AI to build your app** — get a ZIP or HTML file
2. **Open Push on your home screen** — select the file
3. **Tap Deploy** — Push scans for security issues, then publishes live

Your app is live on GitHub Pages at `yourusername.github.io/your-app`

---

## Features

**Deployment**
- Deploy ZIP or HTML files to GitHub Pages from your phone
- Auto-creates GitHub repos with Pages enabled
- Supports multiple apps — manage them all in one place
- Deploy history with version numbers per app

**Security Scanner**
- Automatically scans every file before deploying
- 29 security checks across 3 severity levels
- 🔴 **Critical** — blocks deploy (API keys, tokens, private keys, JWT, SSH keys, Stripe, Slack, Google, Firebase)
- 🟡 **Warning** — flagged but optional (eval, document.write, unsafe innerHTML, HTTP connections, .env variables)
- 🔵 **Info** — best practice suggestions (console.log, localhost URLs, missing SRI)
- Deploy Readiness score (0–100%) with risk label
- Copy the full report with one tap to fix with AI
- Scan any already-deployed app anytime with the shield icon
- Skip scan toggle per app for trusted projects

**App Management**
- Home screen grid — swipe between pages of apps
- App icons fetched automatically from deployed apps
- Favourites, Recent and Search
- Deploy history with live GitHub Pages build status
- Repo visit stats per app (last 14 days)

**Settings & Security**
- Remember token on device or session-only mode
- Disconnect GitHub with one tap
- Fine-grained token support — limit access to specific repos
- Reminder to revoke token if device is lost
- Config backup to your own private GitHub repo
- Clear all data anytime from Settings

---

## Getting started

### Requirements
- iPhone with Safari
- GitHub account (free)
- GitHub Personal Access Token

### Setup
1. Open [tinq777.github.io/push](https://tinq777.github.io/push/) in Safari
2. Tap Share → Add to Home Screen
3. Open Push → tap ⚙ → enter your GitHub username and token
4. Tap Add App → name your app → Push creates the repo automatically
5. Select your ZIP or HTML file → tap Deploy

### Creating a GitHub token (fine-grained recommended)
1. Go to github.com → Settings → Developer settings
2. Personal access tokens → **Fine-grained tokens** (more secure)
3. Set repository access to your Push-related repos only
4. Enable **Contents** (Read & Write) and **Pages** (Read & Write)
5. Copy the token and paste into Push settings

Or use a classic token with **repo** scope for simplicity.

---

## Security

Push takes security seriously:

- **No backend** — there is no server. Everything runs on your device
- **Token safety** — stored in localStorage or session-only (your choice), never synced
- **Built-in scanner** — 29 checks for exposed secrets before every deploy
- **Deploy Readiness score** — 0–100% confidence rating per deploy
- **OWASP reviewed** — input sanitisation, CSP headers, XSS protection throughout
- **Open source** — inspect the code yourself

[Privacy Policy](https://tinq777.github.io/push/privacy)

---

## Tech stack

- Vanilla HTML, CSS, JavaScript — no framework
- GitHub API for deployments, repo management and config backup
- JSZip for client-side ZIP extraction
- Counter.dev for anonymous visit analytics
- Built entirely with [Claude](https://claude.ai)

---

## Files

| File | Description |
|------|-------------|
| `index.html` | Push app |
| `privacy.html` | Privacy policy |
| `favicon.svg` | Browser tab icon |
| `apple-touch-icon.svg` | Home screen icon |
| `README.md` | This file |

---

## License

MIT — see [LICENSE](LICENSE)

---

## Feedback

Found a bug or have a suggestion? [Open an issue](https://github.com/tinq777/push/issues/new)

If Push is useful to you, [⭐ star the repo](https://github.com/tinq777/push) — it helps others find it.

