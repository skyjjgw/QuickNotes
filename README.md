# QuickNote

A lightweight, cross-platform desktop sticky note application built with Electron. Supports Markdown syntax, providing a minimalist floating window mode and efficient shortcut operations.

## Features

*   **Dual Mode Switching**:
    *   **Expanded Mode**: Full note editing and management interface.
    *   **Floating Mode**: Compact desktop floating window, always on top for easy reference.
*   **Markdown Support**: Supports headers, lists, bold, code blocks, and other common Markdown formats.
*   **Auto Save**: All changes are saved automatically in real-time.
*   **Multi-note Management**: Supports creating, deleting, and switching between multiple notes.
*   **Recycle Bin**: Protection mechanism for accidentally deleted notes.
*   **System Integration**: Tray icon, auto-start on boot.

## Shortcuts

| Function | Shortcut |
| :--- | :--- |
| **Switch Mode** | `Ctrl + Space` |
| **Show/Hide** | `Ctrl + Alt + M` (Global) |
| **Save As** | `Ctrl + Alt + S` |
| **Delete Note** | `Backspace` |
| **New Note** | `Ctrl + N` |
| **Zoom** | `Ctrl + +` / `Ctrl + -` |

## Development & Build

### Install Dependencies

```bash
npm install
```

### Start Development Environment

```bash
npm start
```

### Build

```bash
# Windows
npm run build -- --win

# Mac
npm run build -- --mac

# Linux
npm run build -- --linux
```


