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
  <a href="#highlights">Highlights</a>
  ·
  <a href="#updates">Updates</a>
  ·
  <a href="#system-requirements">System requirements</a>
  ·
  <a href="#support">Support</a>
</p>

<p align="center">
  <img width="1000" alt="Cortex desktop app" src="assets/screenshot-hero.png" />
</p>

## About

Most agent harnesses stop at a loop: a model, some tools, and a prompt. Cortex is the workspace around that loop. It gives the agent a place to work — projects and files, editable documents and presentations, source-backed knowledge, a creative canvas, your desktop, and the chat apps your team already uses — and it keeps you in charge of what the agent may do.

Conversations, projects, and settings are stored locally on your Mac. Model requests go to the providers you configure; connected apps and online tools access their own services within the permissions you grant. Local models and downloaded components can work offline.

## Download

| Platform | Package |
| --- | --- |
| macOS 13 or later, Apple silicon | [Latest release (`.dmg`)](https://github.com/FLock-io/cortex-releases/releases/latest) |

1. Open the latest release and download `Cortex-<version>-arm64.dmg`.
2. Drag **Cortex** into **Applications**.
3. Open **Cortex** from Applications and follow the setup to connect a model. You can skip model setup and return to it later.

The current release is Developer ID–signed and notarized by Apple. Office and creative editors, local speech models, and knowledge-search models download when needed or when you choose to install them; the app verifies each download against a pinned digest.

## Highlights

### Cola, your personal agent

Cola is an agent that works alongside you. It follows up on work within the scope you allow, reads across your projects and conversations, and comes back when there is progress or a decision to make. Describe a routine in plain language, such as "every morning at 9, send me yesterday's progress," and Cola sets it up.

<p align="center">
  <img width="1000" alt="Cola answering in a conversation, with its profile panel showing routines, memory, and model usage" src="assets/screenshot-cola.png" />
</p>

### Creative canvas

A design canvas built into the workspace. Generation nodes are artboards, any layer can be a reference, and every version stays inside its node. Ask the agent to design directly on the canvas: layers stay named and editable, and you can step in at any point.

<p align="center">
  <img width="1000" alt="A social post designed by the agent on the Creative canvas, with layers on the left and the agent conversation on the right" src="assets/screenshot-creative.png" />
</p>

### Model routing and cost

In Auto mode, a lightweight classifier sends each task to the model group that fits: fast, balanced, or deep reasoning. The usage panel shows today's tokens and known cost, a seven-day trend, and how runs split across groups and models. Costs are calculated on your Mac from your own runs. Runs without a known price are marked as unpriced, not counted as zero, and the panel shows usage rather than your provider's subscription quota.

<p align="center">
  <img width="420" alt="The usage panel: today's tokens and cost by provider and model, a seven-day cost trend, and run share by model group" src="assets/screenshot-routing.png" />
</p>

### Computer history and daily summaries

Optionally, Cortex keeps a local record of which apps you used and, every 10 minutes, a short summary of what you were doing. The overview shows your time at the computer, your longest focus, a day rhythm by category, and a plain-language timeline. A daily report is drafted at the time you choose.

It is off by default and available on macOS. You can pause it, exclude apps, or clear it at any time. Summaries are written by the model you choose.

<p align="center">
  <img width="1000" alt="The computer history overview: time at the computer, longest focus, a day rhythm grid by category, and a timeline of what you did" src="assets/screenshot-history.png" />
</p>

*Screenshots use fictional sample data.*

### Also in Cortex

- **Permissions you choose.** Use **Ask for approval**, **Auto-approve**, or **Plan** for each conversation. These modes keep a confirmation step for irreversible commands. Optional **Full access**, enabled separately in Settings, relaxes those checks for attended desktop and CLI conversations only.
- **Editable work.** Create documents, slide decks, and data dashboards in a conversation, keep editing them from the sidebar, and export to Word, PowerPoint, or HTML.
- **Source-backed knowledge.** Search your knowledge bases and follow citations to the original documents.
- **Meetings.** Record, transcribe locally, and get a summary with speaker labels.
- **Computer use.** Let an agent operate apps on your Mac, with per-app permission prompts.
- **Skills and MCP connectors.** Install a dependency once and every conversation can use it.
- **Bots for WeChat, Feishu / Lark, DingTalk, and Telegram.** Send tasks from your phone and get results back in the same chat.

## Updates

Cortex updates itself. With automatic updates on, the app checks shortly after launch and every four hours, downloads new versions in the background, and installs them the next time you quit. You can restart to update, check manually, or change these options in **Settings › Notifications & chats › Software update**.

Release notes for each version are on the [Releases](https://github.com/FLock-io/cortex-releases/releases) page.

## System requirements

- macOS 13 Ventura or later
- Apple silicon (M1 or later)
- An API key for at least one model provider, added in **Settings › Models & providers**

Intel Macs, Windows, and Linux are not supported yet.

## Support

Found a bug or have a feature request? [Open an issue](https://github.com/FLock-io/cortex-releases/issues/new) with your Cortex version (shown under **Settings › Notifications & chats › Software update**), your macOS version, and the steps to reproduce it. Please search [existing issues](https://github.com/FLock-io/cortex-releases/issues) first.

## About this repository

This repository hosts Cortex release builds. It does not contain source code.

© FLock.io. All rights reserved.
