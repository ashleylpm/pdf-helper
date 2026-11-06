# PDF helper

A simple, private PDF tool that runs entirely in your browser. Files never leave your device.

## What it does

- **Combine files**: join several PDFs and photos into one PDF, in the order you choose.
- **Replace a page**: swap one page of a PDF for a photo or a page from another PDF.
- **Fill in or fix text**: fill in form fields, change existing words on a page, or type new text anywhere.

## Use it

Open `index.html` in any modern browser, or host it with GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

## Limits

- Scanned PDFs have no real text, so use "Add text" with "Cover" to write over them.
- Text can only be saved in English letters, numbers and common symbols for now.
- Password-protected PDFs need their password removed first.

## Built with

- [pdf-lib](https://pdf-lib.js.org/) for creating and editing PDFs
- [PDF.js](https://mozilla.github.io/pdf.js/) for showing pages
