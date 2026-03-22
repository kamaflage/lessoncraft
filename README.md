# LessonCraft

**Professional lesson plan builder for Ontario educators.**

A single-file PWA — no install, no account, works offline after first load.

## Features

- **Three-Part Lesson framework** — Minds On, Action, Consolidation
- **6 lesson templates** — Blank, Rich Blank, Math (Financial Literacy), Science (Inquiry), Language Arts (Reading Response), Social Studies (Community Roles)
- **AI interview prompt** — generates a structured JSON lesson plan from a conversation
- **Save / Import / Export** — `.json` drafts + `.docx` professional export
- **Dark mode** — persistent across sessions
- **PWA** — installable on iOS and Android, works offline

## Deploy

Upload to any static host. Files needed:
- `index.html`
- `sw.js`
- `manifest.json`
- `icon-192.png`
- `icon-512.png`

## Usage

1. Open [kamaflage.github.io/lessoncraft](https://kamaflage.github.io/lessoncraft)
2. Pick **Templates** → select a subject or start blank
3. Fill in the form — progress tracked automatically
4. **Save** to download a `.json` draft anytime
5. **Export** to download a formatted `.docx` lesson plan

## Stack

Single HTML file · Vanilla JS · docx.js (CDN) · No frameworks · No build step
