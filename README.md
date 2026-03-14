# Nova Editor

A fast, clean, browser-based code and text editor. No installation, no backend — just open the file and start writing.

![Nova Editor](https://img.shields.io/badge/version-2.0.0-f0a500?style=flat-square) ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![CodeMirror](https://img.shields.io/badge/CodeMirror-5.x-d6d6d6?style=flat-square)

---

## Features

- **Multi-tab editing** — open multiple files side by side, switch between them instantly
- **Syntax highlighting** — auto-detects language from file extension (JS, TS, HTML, CSS, Python, Rust, C/C++, Java, JSON, Markdown, XML)
- **Rename files** — click the filename in the titlebar or double-click any tab to rename inline
- **Open & Download** — open files from disk, download/save with one click or `Ctrl+S`
- **Drag & drop** — drag any file onto the window to open it
- **Find** — `Ctrl+F` opens a find bar with match cycling and result count
- **Dark / Light theme** — toggle with `Ctrl+Shift+T`, persists across sessions
- **Word wrap** — toggle with `Alt+Z`
- **Font zoom** — `Ctrl++` / `Ctrl+-`
- **Unsaved indicator** — amber dot on tab when file has unsaved changes
- **Status bar** — live line/column, word count, character count, language, filename
- **Responsive** — collapses to a hamburger menu on mobile/small screens

---

## Usage

No build step needed. Just open `textEditor.html` in any modern browser.

```bash
git clone https://github.com/middi870/browser_text_editor
cd browser_text_editor
# open textEditor.html in your browser
```

Or use it live at: **[middi870.github.io/browser_text_editor/textEditor.html](https://middi870.github.io/browser_text_editor/textEditor.html)**

---

## Keyboard Shortcuts

| Action | Shortcut |
|---|---|
| New File | `Ctrl + N` |
| Open File | `Ctrl + O` |
| Save / Download | `Ctrl + S` |
| Save As | `Ctrl + Shift + S` |
| Close Tab | `Ctrl + W` |
| Find | `Ctrl + F` |
| Toggle Theme | `Ctrl + Shift + T` |
| Toggle Word Wrap | `Alt + Z` |
| Zoom In | `Ctrl + =` |
| Zoom Out | `Ctrl + -` |
| Undo | `Ctrl + Z` |
| Redo | `Ctrl + Y` |

---

## Supported Languages

`JavaScript` · `TypeScript` · `HTML` · `CSS` · `Python` · `Rust` · `C` · `C++` · `Java` · `JSON` · `Markdown` · `XML` · `Plain Text`

---

## Tech Stack

- Vanilla HTML, CSS, JavaScript — zero dependencies, zero frameworks
- [CodeMirror 5](https://codemirror.net/5/) for the editor core and syntax modes
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) for the editor font
- Single self-contained `.html` file — no build tools required

---

## Author

**Aditya Ranjan Jha** · [github.com/middi870](https://github.com/middi870) · [middi870.github.io](https://middi870.github.io)