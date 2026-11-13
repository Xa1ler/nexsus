# Nexus

One control panel for your AI agents. Run **Claude Code** and **Codex** side by side, watch every agent work live, approve what they want to do, and undo anything they change. It runs on your own Claude and ChatGPT plans, with no API keys needed.

## Download

Get the latest version from **[Releases](../../releases/latest)**.

- **New install:** download `Nexus Setup <version>.exe` and run it. Windows may show a SmartScreen warning because the app isn't code-signed yet: click **More info → Run anyway**.
- **Already have Nexus?** You don't need to do anything. Nexus checks for updates every few hours, downloads them in the background and installs them when you close it.

## What you need

- Windows 10 or 11
- [Claude Code](https://claude.com/claude-code), installed and signed in (run `claude` once)
- Optional: [Codex](https://github.com/openai/codex) for ChatGPT, Team mode, Race and image generation (`npm install -g @openai/codex`, then `codex login`)
- Optional: [Git for Windows](https://git-scm.com) for undo and change review

## Features

- Chat with Claude or Codex, with the model and effort you pick
- Team, Race and Debate modes where both AIs work together
- Live view of every agent and helper agent
- One permissions inbox for both AIs, with safety blocks for dangerous actions
- Undo for any file the agents change, and Git commits written for you
- Token saver: short "caveman" replies, a project vault and code map, cheaper helper models
- Roblox Studio and Blender connections, auto test-and-fix, Discord pings, mini HUD, themes

## Updates are signed

Every update is signed with the developer's private key. Nexus refuses any update without a valid signature, even if it comes from this page.

## License

Nexus is proprietary software. Copyright (c) 2026 Xa1ler, all rights reserved. See [LICENSE](LICENSE). The source code is not public.
