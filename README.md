# Memoro

**One memory for every AI you use — stored on your own computer.**

🌐 **Website:** [getmemoro.pages.dev](https://getmemoro.pages.dev) · [Türkçe](https://getmemoro.pages.dev/tr/) · [Русский](https://getmemoro.pages.dev/ru/)

Memoro is a Windows app that gives Claude, ChatGPT, Grok and Perplexity one shared, always-current memory of your projects, decisions and preferences. Explain your project once; every AI you connect reads and updates the same short "status cards", so you stop re-explaining context every time you switch tools.

## Why

Every AI chat starts from zero. Plan with Claude on Monday, continue in ChatGPT on Tuesday, and you spend the first ten minutes re-explaining everything. Built-in AI memories are locked inside a single app and don't talk to each other. Memoro is one memory for all of them — without sending your data to a server we run (we don't run one).

## How it works

- Memoro runs quietly in the background on your PC and exposes your memory to AI assistants through MCP (Model Context Protocol).
- Memory is kept as **status cards**: one focused, up-to-date summary per topic (what was decided, what was ruled out, what's next). Cards are updated instead of piling up contradictions, and older versions are kept.
- Claude Desktop connects locally. Browser and phone AIs (claude.ai, ChatGPT, Grok, Perplexity) connect through an optional bridge that Memoro deploys to **your own** free Cloudflare account.
- Memoro does not scrape your chats. The AI writes cards through Memoro's tools when something is worth keeping, or when you ask.

## Free and Pro

| | Free | Pro — $9.99/year or $1.99/month |
|---|---|---|
| Claude Desktop connection | ✓ | ✓ |
| Unlimited memories and status cards | ✓ | ✓ |
| claude.ai, ChatGPT, Grok, Perplexity | — | ✓ |
| Phone and browser access (cloud bridge) | — | ✓ |
| "Add AI" for any MCP-compatible assistant | — | ✓ |
| Sync across several PCs | — | ✓ |
| Team Projects (beta) | — | ✓ |

Every new install gets **all Pro features free for 7 days**, no card required. To activate Pro, paste the license key from your purchase email into the **License** section of the Memoro control panel.

## Download

Windows 10 / 11. **[Download the latest version](https://getmemoro.pages.dev/download)** · [Release notes](https://github.com/circassian1977-byte/memoro/releases)

Memoro needs Node.js (free); the installer tells you if it's missing. The installer isn't code-signed yet, so Windows may show "Windows protected your PC" — click **More info → Run anyway**. Mac and Linux are planned.

## Privacy

Your memory lives on your computer (and, if you enable it, in your own Cloudflare account). No account with us, no ads, no tracking, no data sales. Full policy: [getmemoro.pages.dev/privacy](https://getmemoro.pages.dev/privacy/).

## Status and feedback

Early stage, actively developed. Questions and bug reports: [open an issue](https://github.com/circassian1977-byte/memoro/issues).

© 2026 Memoro. All rights reserved. This repository contains documentation and releases only; the source code is not open source.
