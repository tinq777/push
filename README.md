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

**Security Scanner**
- Automatically scans every file before deploying
- Checks for 18 security vulnerabilities across 3 severity levels
- 🔴 **Critical** — blocks deploy (hardcoded API keys, tokens, private keys)
- 🟡 **Warning** — flagged but optional (eval, document.write, unsafe innerHTML)
- 🔵 **Info** — best practice suggestions (console.log, localhost URLs)
- Copy the full report with one tap to fix with AI
- Scan any already-deployed app anytime with the shield icon

**App Management**
- Home screen grid — swipe between pages of apps
- Favourites, Recent and Search
- Deploy history with live GitHub Pages build status
- Traffic stats per app (GitHub repo visits)

**Settings & Privacy**
- All data stored locally on your device
- GitHub token never leaves your phone except to talk directly to GitHub API
- Config backup to your own private GitHub repo
- Clear all data anytime from Settings

---

## Getting started

### Requirements
- iPhone with Safari
- GitHub account (free)
- GitHub Personal Access Token with `repo` scope

### Setup
1. Open [tinq777.github.io/push](https://tinq777.github.io/push/) in Safari
2. Tap Share → Add to Home Screen
3. Open Push → tap ⚙ → enter your GitHub username and token
4. Tap Add App → name your app → Push creates the repo automatically
5. Select your ZIP or HTML file → tap Deploy

### Creating a GitHub token
1. Go to github.com → Settings → Developer settings
2. Personal access tokens → Tokens (classic)
3. Generate new token → enable **repo** scope
4. Copy the token and paste into Push settings

---

## Security

Push takes security seriously:

- **No backend** — there is no server. Everything runs on your device
- **Token safety** — your GitHub token is stored in localStorage only, never synced or shared
- **Built-in scanner** — Push scans your code for exposed secrets before every deploy
- **OWASP reviewed** — input sanitisation, CSP headers, XSS protection throughout
- **Open source** — inspect the code yourself

[Privacy Policy](https://tinq777.github.io/push/privacy)

---

## Tech stack

- Vanilla HTML, CSS, JavaScript — no framework
- GitHub API for deployments and repo management
- JSZip for client-side ZIP extraction
- Counter.dev for anonymous visit analytics
- Built entirely with [Claude](https://claude.ai)

---

## License

MIT — see [LICENSE](LICENSE)

---

## Feedback

Found a bug or have a suggestion? [Open an issue](https://github.com/tinq777/push/issues/new)

If Push is useful to you, [⭐ star the repo](https://github.com/tinq777/push) — it helps others find it.
