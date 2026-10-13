# My Dashboard

**A Windows desktop task widget that keeps your assignments and deadlines visible without living in another browser tab.**

My Dashboard is a lightweight Windows productivity app built for people who want a simple, always-available view of what is due next.

> **Current status:** Free beta (v0.3.1)

## What it does

- Add, edit, complete, undo, and delete tasks.
- See **Overdue, Today, Upcoming, and Completed** tasks at a glance.
- Use a separate translucent desktop widget alongside the full dashboard.
- Drag and resize the widget and keep its position between sessions.
- Optionally launch in the background with Windows.
- Import tasks from a user-selected Excel workbook.
- Preview imports before applying them and avoid duplicate tasks.
- Optionally sync records across devices with Supabase.
- Optionally connect Ollama or LM Studio for local AI-assisted planning. AI-proposed changes always require confirmation.

Your normal task list works locally without an account, Excel, or AI.

## Windows beta

The Windows installer is available in this repository's **Releases** section. Executable installers and updater files are distributed as release assets, not as README downloads.

Install the latest version from Releases. Existing users can also update through **Settings → About / Updates → Check for Updates**.

> **Windows warning:** Windows may show an unknown-publisher or SmartScreen warning while the app is still in beta. Only download releases from this repository.

## Who this beta is for

The app is especially useful if you:

- want assignments or tasks visible directly on your Windows desktop;
- already track school or work deadlines in Excel;
- prefer local/offline tools instead of putting every task into a cloud service;
- want a small desktop widget rather than constantly opening a full planner.

## Privacy

- A fresh installation starts empty.
- Normal task data is stored locally on your computer.
- Excel files are only read when you explicitly select and scan one.
- No AI model is bundled with the app.
- Optional sync and AI integrations are only used if you configure them.

## Beta feedback

This is an early public beta. If something is confusing, broken, or missing, please open an issue in this repository and describe:

1. what you were trying to do;
2. what happened;
3. what you expected instead;
4. your Windows version, if relevant.

## Current limitation

My Dashboard tracks deadlines but does **not** currently create Windows notification alarms.

---

Built as a practical Windows dashboard for keeping important tasks in sight.
