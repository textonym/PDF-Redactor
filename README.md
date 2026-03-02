markdown

# ⬛ PDF Redactor

A fully client-side PDF redaction tool — no uploads, no server, no data leaves your browser.

🔗 **[Live Demo](https://textonym.github.io/PDF-Redactor)**

<img width="910" height="646" alt="image" src="https://github.com/user-attachments/assets/8feedfd8-034c-42b2-99f6-24d6c1784968" />


## Features

- 📄 **Open any PDF** — drag & drop or click to upload
- ✏️ **Draw redaction boxes** — click and drag to mark sensitive areas with black rectangles
- 📑 **Multi-page support** — redactions are tracked independently per page
- 🔍 **Zoom controls** — zoom in for precision on small text
- 🗂️ **Redaction list** — sidebar tracks all boxes; remove any with one click or right-click
- 💾 **Export** — downloads a real redacted PDF with black fills permanently burned in using [pdf-lib](https://pdf-lib.js.org/)

## Usage

1. Open the app and upload a PDF
2. Switch to **Redact** mode (default)
3. Click and drag on the document to draw black redaction boxes
4. Navigate pages and add more redactions as needed
5. Click **Export Redacted PDF** to download the final file

## Privacy

All processing happens entirely in your browser. No data is sent to any server.

## Tech Stack

- [PDF.js](https://mozilla.github.io/pdf.js/) — PDF rendering
- [pdf-lib](https://pdf-lib.js.org/) — PDF modification & export
- Vanilla HTML/CSS/JS — no build step, no dependencies to install

## Running Locally

No build step needed — just open the file:

```bash
git clone https://github.com/yourusername/pdf-redactor.git
cd pdf-redactor
open index.html   # or double-click the file
```

## License

MIT
