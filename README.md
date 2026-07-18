# LiteKanban

A fast, single-file Kanban board that runs entirely in your browser. No install, no account, no server, no build step — download `index.html` (or open it straight from GitHub Pages) and start organizing.

## Why

Most task boards ask you to sign up, install something, or trust a company with your data. LiteKanban is the opposite: it's one HTML file, your data never leaves your browser, and there's nothing to set up.

## Features

- **Columns & tasks** — create, rename, reorder, and delete columns; drag tasks between them or reorder within a column
- **Tags** — label tasks and filter by them
- **Due dates** — with automatic overdue / today / tomorrow highlighting
- **Subtasks / checklists** — track progress within a task, with a completion count
- **Task menu** — edit, duplicate, or delete any task in a couple of clicks
- **Column reordering mode** — drag whole columns into a new order
- **Custom board background** — set an image or color for the whole board
- **Themes** — accent color picker, adjustable density (comfortable/compact), shadow style, and font size
- **Keyboard shortcut** — press `N` to quickly add a new task
- **Local, persistent storage** — everything saves automatically to your browser's `localStorage`; close the tab and it's still there next time

## Getting started

**Option 1 — just open it**
Download `index.html` from this repo and double-click it. It opens in your default browser and works immediately — no internet connection required after that.

**Option 2 — use it online**
If GitHub Pages is enabled for this repo, you can open the board directly from a URL and bookmark it, without downloading anything:
`https://YOUR-USERNAME.github.io/kanvas/`

## 🔒 Data & privacy

All board data is stored locally in your browser via `localStorage`. Nothing is sent to a server. This also means your board is tied to the specific browser/device you use it on — clearing your browser data will clear your board.

To move a board between devices or share it with someone else, use the **Export** button in the top bar to download it as a `.json` file, then send that file however you like. The other person opens LiteKanban and clicks **Import** to load your exact board — columns, tasks, tags, due dates, and subtasks all included.

## Tech

Plain HTML, CSS, and JavaScript. No frameworks, no dependencies, no build tools. It's intentionally kept as a single file for maximum portability.

## Contributing

Issues and pull requests are welcome. Since it's a single file, the easiest way to contribute is to open `index.html`, make your change, and test it directly in a browser before submitting a PR.




