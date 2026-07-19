# 🗂️ LiteKanban

**A single-file Kanban board. No install, no account, no server — just open it and go.**

[![View Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?logo=github&logoColor=white)](https://github.com/AdhamAhmedo/LiteKanban)
[![Download](https://img.shields.io/badge/⬇-Download%20index.html-5a5af2?logo=googlechrome&logoColor=white)](https://github.com/AdhamAhmedo/LiteKanban/raw/main/index.html)
![Vanilla JS](https://img.shields.io/badge/JavaScript-Vanilla-f7df1e?logo=javascript&logoColor=black)
![No Build Step](https://img.shields.io/badge/Build%20Step-None-brightgreen)
![Single File](https://img.shields.io/badge/Files-1-blue)
![No Dependencies](https://img.shields.io/badge/Dependencies-0-lightgrey)

</div>

---

## 🚀 Get it now

1. Click **[⬇ Download index.html](https://github.com/AdhamAhmedo/LiteKanban/raw/main/index.html)**
2. Double-click the downloaded file
3. You're using it — no install, no sign-up, no internet needed after that

That's the entire setup. Everything below is for anyone who wants the details before or after downloading.

---

## 💡 Why

Most task boards ask you to sign up, install something, or trust a company with your data. LiteKanban is the opposite: it's one HTML file, your data never leaves your browser, and there's nothing to set up.

## ✨ Features

<details open>
<summary><strong>Boards & columns</strong></summary>

- Multiple boards — create, rename, delete, and switch between separate boards from a dropdown
- Columns — add, rename, delete, and reorder columns via a dedicated "Move" mode
- Per-column colors — set a custom header color and body color for each column

</details>

<details open>
<summary><strong>Tasks</strong></summary>

- Create, edit, duplicate, and delete tasks
- Mark tasks done — adds a checkmark badge and a distinct highlight
- Custom task colors, including your own hex colors, saved for reuse
- Tags — label tasks and filter the board by one or more tags
- Due dates — automatic overdue / today / tomorrow / upcoming highlighting
- Subtasks / checklists — track progress within a task, with inline checkboxes and a "+N more" expander for long lists
- Long task text automatically truncates with a "Show more / Show less" toggle
- Search bar to filter tasks by text, combinable with tag and date filters

</details>

<details open>
<summary><strong>Import & export</strong></summary>

- **Export** your current board to a `.json` file at any time
- **Import** a `.json` file — you're asked whether to **replace your current board** or **create a new board** from the import, so importing never silently overwrites your existing work

</details>

<details open>
<summary><strong>Undo</strong></summary>

- Deleting a task or column doesn't remove it right away — it queues an individual undo action with its own 5-second countdown
- Delete several things in a row and undo any one of them independently; the others stay queued

</details>

<details open>
<summary><strong>Appearance</strong></summary>

- Accent color picker, adjustable density (comfortable/compact), shadow style, and font size
- Custom board background — solid presets or your own uploaded image

</details>

<details open>
<summary><strong>Other</strong></summary>

- Keyboard shortcut — press `N` to quickly add a new task
- Everything saves automatically and instantly to your browser's `localStorage` — close the tab and it's still there next time

</details>

## 🔒 Data & privacy

All board data is stored locally in your browser via `localStorage`. Nothing is sent to a server. This also means:
- Your board is tied to the specific browser/device you use it on.
- Clearing your browser data will clear your board — consider that before doing a "clear all site data" cleanup.
- To move a board between devices or share it with someone else, use **Export** to download it as `.json`, send that file however you like, and have the other person use **Import** to load it in.

## 🛠️ Tech

Plain HTML, CSS, and JavaScript. No frameworks, no dependencies, no build tools. It's intentionally kept as a single file for maximum portability.

## 🤝 Contributing

Issues and pull requests are welcome. Since it's a single file, the easiest way to contribute is to open `index.html`, make your change, and test it directly in a browser before submitting a PR. Good luck with the 2600+ line of code. :)
