# PDF Merger

A lightweight, browser-based PDF merging tool — no installs, no uploads, no server required. Everything runs locally in your browser.

## Features

- **Drag & drop** or click to browse and add PDF files
- **Reorder files** by dragging items in the list — the merged output follows that order
- **Page count display** — see how many pages each PDF has before merging
- **Custom output filename** — name your merged file before downloading
- **Progress bar** — visual feedback during the merge process
- **100% client-side** — your files never leave your device

## Demo

Open `pdf-merger.html` directly in any modern browser — no build step needed.

## Usage

1. Open `pdf-merger.html` in your browser
2. Add two or more PDF files via drag & drop or the file picker
3. Drag items to reorder them if needed
4. Set your desired output filename
5. Click **Merge PDFs** — the merged file downloads automatically

## Tech Stack

- Vanilla HTML, CSS, JavaScript
- [pdf-lib](https://pdf-lib.js.org/) v1.17.1 (loaded via CDN) — handles PDF parsing and merging

## Browser Support

Works in all modern browsers that support the File API and `ArrayBuffer`:

| Browser | Support |
|---------|---------|
| Chrome  | ✓ |
| Firefox | ✓ |
| Edge    | ✓ |
| Safari  | ✓ |

## Getting Started

No installation required. Just clone or download and open the file:

```bash
git clone https://github.com/your-username/pdf-merger.git
cd pdf-merger
# Open pdf-merger.html in your browser
```

## License

MIT — free to use, modify, and distribute.
