# simple-mk-web

A single-file markdown viewer and editor that runs entirely in your browser. Select a local folder, browse your `.md` files, and preview or edit them — nothing is uploaded anywhere.

## Features

- **Folder browsing** — pick any local directory using the File System Access API
- **Recursive or flat** — optionally include subfolders
- **Live preview** — rendered markdown with syntax-highlighted code blocks
- **Editor** — write markdown with a formatting toolbar and keyboard shortcuts
- **Split view** — side-by-side editor and preview
- **Search** — filter files by name
- **File management** — create, rename, and delete files and folders
- **Dark mode** — light/dark theme toggle
- **Responsive** — works on desktop, tablet, and mobile
- **State persistence** — remembers your last folder, open file, theme, and view mode across reloads

## Usage

Open `index.html` in a browser, or visit the hosted version:

**https://your-username.github.io/simple-mk-web**

Click "Open Folder" and select a directory containing markdown files. Your files never leave your device.

## Keyboard shortcuts

| Shortcut | Action |
|----------|--------|
| `⌘O` | Open folder |
| `⌘S` | Save file |
| `⌘N` | New file |
| `⇧⌘N` | New folder |
| `⌘\` | Toggle sidebar |
| `⌘K` | Search files / Insert link (in editor) |
| `⌘1–5` | Switch view mode |
| `⌘B` | Bold |
| `⌘I` | Italic |
| `?` | Show all shortcuts |

## Requirements

- A modern browser with [File System Access API](https://developer.mozilla.org/en-US/docs/Web/API/File_System_Access_API) support (Chrome, Edge, Opera)
- No build step, no dependencies to install — it's one HTML file

## Development

To run locally:

```bash
python3 -m http.server 3456
```

Then open http://localhost:3456.

## License

MIT
