# Minimal To-Do (single file)

A tiny, minimalist to‑do list implemented as a single HTML file. It saves tasks locally in your browser using `localStorage`, supports adding and deleting tasks, and includes a persistent light/dark theme toggle.

Files
- `index.html` — the complete app (HTML/CSS/JS) in one file.

Features
- Add tasks (press Enter or click Add).
- Delete tasks (trash button, confirmation).
- Clear all tasks (Clear button, confirmation).
- Persistent storage using `localStorage` (`todoList` key).
- Light / Dark theme toggle (persistent, `theme` key).

Quick start

1. From the project root, open `index.html` directly in a modern browser (double-click).
2. Or run a simple static server and visit the page:

```bash
python -m http.server
# open http://localhost:8000/index.html
```

Notes
- Tasks are stored in your browser profile (per origin). To back them up, open DevTools → Application → Local Storage → `todoList` and copy the JSON.
- Theme preference is saved under the `theme` localStorage key.
- No external dependencies or build steps required.

Want more?
- I can add export/import JSON, inline edit, due dates, or keyboard shortcuts. Tell me which and I’ll implement it.
# ToDoList_App