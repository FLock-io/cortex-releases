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
  <a href="#screenshots">Screenshots</a>
  ·
  <a href="#updates">Updates</a>
  ·
  <a href="#system-requirements">System requirements</a>
  ·
  <a href="#support">Support</a>
</p>

<p align="center">
  <img width="1000" alt="Cola, the personal work agent in Cortex, answering in a conversation with its profile panel open" src="assets/screenshot-cola.png" />
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

## Features

- **Cola, your work double.** A personal agent that follows up on work within the scope you allow, reads across your projects and conversations, and comes back when there is progress or a decision to make.
- **Permissions you choose.** Use **Ask for approval**, **Auto-approve**, or **Plan** for each conversation. These modes keep a confirmation step for irreversible commands. Optional **Full access**, enabled separately in Settings, relaxes those checks for attended desktop and CLI conversations only; it does not apply to Cola, bots, or unattended runs.
- **Editable work.** Create documents, slide decks, and data dashboards in a conversation, then reopen and keep editing the same work from the sidebar. Select a passage to ask the agent to revise it, and export documents to Word, presentations to PowerPoint, and dashboards to HTML.
- **Source-backed enterprise knowledge.** Search your knowledge bases, follow citations to the original documents, and have every source checked before it is shown.
- **Meetings.** Record a meeting on your Mac, transcribe it locally, and get a summary with speaker labels that opens as an editable document. Ask questions about the meeting or list your to-dos.
- **Creative canvas.** Built on a design engine: generation nodes are artboards on the canvas, any layer can be a reference, and every version stays inside its node. Produce images and video, and run a selected chain after previewing it.
- **Computer use.** Let an agent operate apps on your Mac, with per-app permission prompts and one conversation in control at a time.
- **Skills and MCP connectors.** Install a dependency once and every conversation can use it. When a connector fails to start, Cortex shows why.
- **Interactive views.** Agents can answer with live charts, sliders, and demos that you can open beside the chat, adjust, and export as a web page.
- **Bots for WeChat, Feishu / Lark, DingTalk, and Telegram.** Send tasks from your phone and get results back in the same chat. Scan a QR code to create a Feishu app, and choose how replies stream back.
- **Automatic model routing and usage.** Route tasks to model groups and review local cost, run, and token statistics by day, group, and model. This shows usage, not your provider's subscription quota.
- **Built for daily work.** A per-conversation terminal, cloud or local voice input with live transcription, subagents, and background tasks.

## Screenshots

Screenshots use fictional sample data.

<p align="center">
  <img width="1000" alt="A slide deck open in the Work editor, with a bar chart and key figures" src="assets/screenshot-work.png" />
</p>
<p align="center"><em>Work: documents, decks, and dashboards you can keep editing</em></p>

<p align="center">
  <img width="1000" alt="An answer with numbered citations from selected knowledge documents" src="assets/screenshot-knowledge.png" />
</p>
<p align="center"><em>Knowledge: answers cite the documents they came from</em></p>

<p align="center">
  <img width="1000" alt="A meeting summary with key takeaways and topic columns" src="assets/screenshot-meetings.png" />
</p>
<p align="center"><em>Meetings: record, transcribe, and summarize</em></p>

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
