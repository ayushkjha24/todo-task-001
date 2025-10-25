# Todo List — Round 2

## Overview
A lightweight, modern Todo List web app with a polished UI and zero dependencies. You can add, complete, edit, filter, and delete tasks. All your todos persist automatically in your browser via localStorage, so they’re still there the next time you open the page.

Highlights:
- Clean, responsive, accessible UI with subtle animations
- Add, toggle complete, edit in place (double‑click or pencil), delete
- Filter by All / Active / Completed and clear all completed
- Auto‑save and restore using localStorage

## Setup
- No build steps or external dependencies required.
- Download this folder and open index.html in any modern browser.

Tip: You can also serve it locally (optional) with any static server, e.g., using Python:
- Python 3: python -m http.server
- Then visit http://localhost:8000

## Usage
- Add a todo: Type in the input and press Enter or click Add.
- Complete a todo: Click its checkbox.
- Edit a todo: Double‑click the text or click the pencil icon. Press Enter to save, Esc to cancel.
- Delete a todo: Click the trash icon.
- Filter: Use All / Active / Completed to control the view (your last filter is remembered).
- Clear completed: Click “Clear completed” to remove all completed tasks.
- Persistence: Everything is saved automatically to localStorage and restored on reload.

Keyboard tips:
- Enter in the new‑todo input adds a task.
- While editing, Enter saves, Esc cancels.

## Improvements from Round 1
This Round 2 release includes several enhancements over the Round 1 version:
- Added persistence: Todos now automatically save to and load from localStorage.
- Upgraded UI styling: Modern, responsive design with a glassy card, gradient background, accent colors, and subtle animations.
- Better UX controls: Filter tabs (All/Active/Completed), Clear Completed button, and an empty‑state message.
- Inline editing: Double‑click or use the pencil to edit tasks directly in the list.
- Accessibility: Improved focus states, ARIA labels, and keyboard‑friendly interactions.
- State indicators: “Saved … ago” timestamp to reflect local save actions.