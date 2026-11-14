# Certificate Review — concept preview

This repository contains a static HTML/CSS/JavaScript concept for a certificate-review workflow. The page shows a sample interaction only; it does **not** upload or process documents, run OCR or a model, extract certificate fields, or store records.

## Preview

The GitHub Pages site is a static concept preview: <https://kalyan870.github.io/certificate-detector/>. Its button displays illustrative copy and does not analyze a certificate. Do not enter real or sensitive documents into this concept page.

## Run locally

Open `index.html` in a browser, or serve this folder with Python:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>. No package installation or build step is required.

## Current scope

- Implemented: responsive static layout and an illustrative button interaction.
- Not implemented: file upload, OCR/document AI, field extraction, authentication, backend/API, database, and review queue.
- The workflow diagram and labels describe a possible future direction, not current functionality.

There is no automated test suite or production build command in this repository. Before adding document processing, define data-retention and privacy requirements and use synthetic/sample certificates for development.
