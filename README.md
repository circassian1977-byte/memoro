# Memoro

**A personal AI memory layer that follows you across every AI you use.**

Memoro is a lightweight Windows app that gives every AI assistant you talk to (Claude, ChatGPT, Grok, Perplexity, Gemini) a shared, persistent memory of you: your projects, decisions, preferences, and the people in your life. Tell one AI something once; every other AI you use can pick it up from exactly where you left off.

## Why

Every AI chat starts from zero. Explain your project to Claude on Monday, switch to ChatGPT on Tuesday, and you're re-explaining everything. Memoro fixes that, without asking you to trust a third-party server with your data.

## How it works

Memoro runs quietly in the background on your own computer. A small MCP (Model Context Protocol) connector, added once to each AI platform, lets your AI read and write to your memory. Memory is stored as "status cards": one focused, up-to-date summary per topic, not a raw chat log. An optional, free Cloudflare Worker and D1 layer, deployed in your own Cloudflare account, gives you access from anywhere, even when your computer is off.

Nothing is ever stored on a server we run. We don't operate one. Your data lives on your machine and, optionally, in cloud infrastructure you own.

## Features

Works with Claude, ChatGPT, Grok, Perplexity, and Gemini. Right click "Save to Memoro" browser extension for one off notes. Multi device sync via your own OneDrive or Google Drive (Pro). Team Projects: a shared memory for a team, with conflict resolution and an approval step for critical changes (Pro). Seven day free trial of every Pro feature, no card required.

## Installation

Windows only for now (Mac and Linux planned). Download and pricing: see the project's release page (coming soon here).

## Privacy

No hosting of your data, no data sales, no ads. The only thing Memoro sells is the software itself.

## Status

Early stage, actively developed. Issues and feedback welcome.
