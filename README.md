# Memoro: Long-Term Memory for AI

**Your AI forgets. Memoro remembers — in every chat, across every AI.**

🌐 **Website:** [getmemoro.pages.dev](https://getmemoro.pages.dev) · [Türkçe](https://getmemoro.pages.dev/tr/) · [Русский](https://getmemoro.pages.dev/ru/)

<a href="https://apps.microsoft.com/detail/9PBM9N3NDSDX"><img src="https://get.microsoft.com/images/en-us%20dark.svg" width="180" alt="Get it from Microsoft Store"></a>

Memoro is a Windows app that gives your AI a long-term memory: every new chat — in Claude, ChatGPT, Grok or Perplexity — picks up where you left off instead of starting from zero. Explain your project once; every AI you connect reads and updates the same short "status cards", so you stop re-explaining context every time you switch tools.

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

<a href="https://apps.microsoft.com/detail/9PBM9N3NDSDX"><img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200" alt="Get it from Microsoft Store"></a>

Windows 10 / 11 — **[get Memoro from the Microsoft Store](https://apps.microsoft.com/detail/9PBM9N3NDSDX)** (free). Everything it needs is included, Windows installs it without warnings, and updates arrive automatically through the Store. Mac and Linux are planned.

[Release notes](https://github.com/circassian1977-byte/memoro/releases)

## Privacy

Your memory lives on your computer (and, if you enable it, in your own Cloudflare account). No account with us, no ads, no tracking, no data sales. Full policy: [getmemoro.pages.dev/privacy](https://getmemoro.pages.dev/privacy/).

## Status and feedback

Early stage, actively developed. Questions and bug reports: [open an issue](https://github.com/circassian1977-byte/memoro/issues).

© 2026 Memoro. All rights reserved. This repository contains documentation and releases only; the source code is not open source.
