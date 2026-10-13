<p align="center">
  <img width="96" alt="Cortex app icon" src="assets/icon.png" />
</p>

<h1 align="center">Cortex</h1>

<p align="center">
  <strong>Not just another agent harness.</strong>
</p>

<p align="center">
  A local-first AI workspace where agents work across your files, knowledge, apps, and chats — with you in control.
</p>

<p align="center">
  <a href="https://github.com/FLock-io/cortex-releases/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/FLock-io/cortex-releases?label=release&color=111111" /></a>
  <img alt="macOS 13+ on Apple silicon" src="https://img.shields.io/badge/macOS-13%2B%20%C2%B7%20Apple%20silicon-111111?logo=apple" />
  <a href="https://github.com/FLock-io/cortex-releases/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/FLock-io/cortex-releases/total?color=111111" /></a>
</p>

<p align="center">
  <a href="#download">Download</a>
  ·
  <a href="#features">Features</a>
  ·
  <a href="#updates">Updates</a>
  ·
  <a href="#system-requirements">System requirements</a>
  ·
  <a href="#support">Support</a>
</p>

<p align="center">
  <img width="1024" alt="Cortex desktop app showing Cola, the personal work agent" src="assets/cortex-cola.png" />
</p>

## About

Most agent harnesses stop at a loop: a model, some tools, and a prompt. Cortex is the workspace around that loop. It gives the agent a place to work — projects and files, a verified knowledge base, a creative canvas, your desktop, and the chat apps your team already uses — and it keeps you in charge of what the agent may do.

Everything runs on your Mac. Conversations, projects, and settings are stored locally, and requests go only to the model providers you configure.

## Download

| Platform | Package |
| --- | --- |
| macOS 13 or later, Apple silicon | [Latest release (`.dmg`)](https://github.com/FLock-io/cortex-releases/releases/latest) |

1. Open the latest release and download `Cortex-<version>-arm64.dmg`.
2. Drag **Cortex** into **Applications**.
3. On first launch, if macOS says the app can't be verified, open **System Settings › Privacy & Security** and click **Open Anyway**. Builds are signed with a Developer ID certificate but not yet notarized.

## Features

- **Cola, your work double.** A personal agent that follows up on work within the scope you allow, reads across your projects and conversations, and comes back when there is progress or a decision to make.
- **Agents with guardrails.** Choose **Ask for approval**, **Auto-approve**, or **Plan** for each conversation. Shell commands run in a write sandbox, and irreversible actions always need your confirmation.
- **Verified enterprise knowledge.** Answers cite their sources, and every citation is checked against the original document before it is shown.
- **Creative canvas.** Connect text, image, and generation nodes to produce images and video, keep every version inside its node, and run a selected chain after previewing it.
- **Computer use.** Let an agent operate apps on your Mac, with per-app permission prompts and one conversation in control at a time.
- **Skills and MCP connectors.** Install a dependency once and every conversation can use it. When a connector fails to start, Cortex shows why.
- **Bots for WeChat, Feishu, and DingTalk.** Send tasks from your phone and get results back in the same chat.
- **Built for daily work.** A per-conversation terminal, voice input with live transcription, subagents and background tasks, and automatic model routing.

## Updates

Cortex updates itself from this repository. The app checks for a new release shortly after launch and every four hours, downloads it in the background, and installs it the next time you quit — or right away from **Settings › Notifications & chats › Software update**, where you can also check manually or turn automatic checks off.

Release notes for each version are on the [Releases](https://github.com/FLock-io/cortex-releases/releases) page.

## System requirements

- macOS 13 Ventura or later
- Apple silicon (M1 or later)
- An API key for at least one model provider, added in **Settings › Models & providers**

Intel Macs, Windows, and Linux are not supported by these builds yet.

## Support

Found a bug or have a feature request? [Open an issue](https://github.com/FLock-io/cortex-releases/issues/new) with your Cortex version (shown under **Settings › Notifications & chats › Software update**), your macOS version, and the steps to reproduce it. Please search [existing issues](https://github.com/FLock-io/cortex-releases/issues) first.

## About this repository

This repository hosts signed release builds of Cortex and serves as its update feed. It does not contain source code.

© FLock.io. All rights reserved.
