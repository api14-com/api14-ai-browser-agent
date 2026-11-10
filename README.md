# api14 AI Browser Agent for Windows

**api14 AI Browser Agent** is a free AI web browser for Windows with a built-in AI agent. It looks and works like Chrome, and the agent can browse, click, type, fill forms, read tables, compare data, generate images and videos, and create Excel, PDF and PowerPoint reports for you. Sign in once with [api14.com](https://api14.com) and the agent can use 400+ AI models: Claude, GPT, Gemini, Llama, DeepSeek, Qwen, Grok and more.

[![Download for Windows](https://img.shields.io/github/v/release/api14-com/api14-ai-browser-agent?label=Download%20for%20Windows&style=for-the-badge)](https://github.com/api14-com/api14-ai-browser-agent/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/api14-com/api14-ai-browser-agent/total?style=for-the-badge)](https://github.com/api14-com/api14-ai-browser-agent/releases)

## Download

1. Open the [latest release](https://github.com/api14-com/api14-ai-browser-agent/releases/latest).
2. Download `api14-browser-setup-<version>.exe` and run it.
3. Click **Connect with api14** and approve in your browser. No API key to copy.

Windows 10 and 11 (64-bit). The installer is not code-signed yet, so Windows SmartScreen may warn on first run: choose **More info**, then **Run anyway**. The app updates itself automatically from this repository's releases.

## What is an AI browser agent?

An AI browser agent is a web browser that an AI can operate for you. Instead of only summarizing a page, the agent plans a task, opens pages, reads them, clicks buttons, types into forms, checks the result and keeps going until the job is done. api14 AI Browser Agent shows every step: the plan, the reasoning, each tool call and its result, and it asks for your approval before anything risky.

## Features

### AI agent

- ChatGPT-style chat on the home screen: give the agent a task in plain language
- Pick any of 400+ AI models and a thinking level; see the cost of every chat
- Visible plan (to-do list), streamed reasoning and tool calls
- Parallel subagents for independent jobs (for example two ad accounts at once)
- Approval cards for actions that spend money, publish or delete
- Works in the background and shows the page it is working on in a live mini window

### Chrome-like web browser

- Multiple browser profiles, each with its own cookies, sign-ins and tabs
- Notes for every profile (client, account, goals) that the agent reads
- Address bar suggestions, bookmarks bar, downloads, history, find in page, zoom
- Right-click menus, duplicate / mute / reopen tabs, print, save as PDF, developer tools
- Chrome keyboard shortcuts and customizable Quick open links

### Browser automation with AI

- Read any page, click, type, press keys, scroll and wait like a person
- Extract tables and grids into structured data
- Ask a vision model questions about what is on the screen
- Upload files into web forms, download files with the browser's sign-in

### Google Ads and Meta Ads automation

- Pull campaign performance from Google Ads and Meta Ads Manager
- Compare platforms and accounts, find wasted spend and winners
- Write ad copy within platform limits and create ad images in the right sizes
- Prepare drafts; the final publish click always needs your approval

### AI content and reports

- Excel (xlsx), PDF, PowerPoint (pptx), CSV, Markdown and HTML reports with charts
- AI image generation, AI video generation, text to speech and transcription
- Everything is saved in `Documents/api14-browser`

## Use cases

- Marketing agencies managing many Google Ads and Meta Ads accounts
- Weekly performance reports in Excel, PDF and PowerPoint
- Competitor and market research across many websites
- Data entry and form filling in web dashboards
- Creating ad creatives and landing page copy

## Privacy and security

- Sign-in uses OAuth 2.0 with PKCE; your api14 key is stored encrypted on your PC (Windows DPAPI).
- The agent never types passwords; you sign in to websites yourself.
- Page content is treated as untrusted data, so instructions hidden in web pages cannot take over the agent.
- Files are written only to `Documents/api14-browser`.

## FAQ

**Is api14 AI Browser Agent free?**
Yes, the app is free. AI usage is paid from your [api14.com](https://api14.com) balance.

**Which AI models does it support?**
All tool-calling models on api14.com, including Claude, GPT, Gemini, Llama, DeepSeek, Qwen and Grok, plus image, video and speech models.

**How is it different from ChatGPT Atlas, Perplexity Comet or Opera Neon?**
It runs any of 400+ models from one account, keeps separate signed-in browser profiles for each client, shows every step of the agent, and is built for ad accounts and reporting work.

**Can it automate Google Ads and Meta Ads?**
Yes. Sign in to each account in its own browser profile and ask the agent. It asks before anything that spends money.

**Does it update automatically?**
Yes. On start it checks this repository's latest release, downloads the new installer, verifies its SHA-256 digest and installs it.

**Is there a macOS or Linux version?**
Windows only for now.

## Links

- Website: [api14.com](https://api14.com)
- Releases and changelog: [CHANGELOG.md](CHANGELOG.md)
- Report a problem: [Issues](https://github.com/api14-com/api14-ai-browser-agent/issues)
