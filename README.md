# Local Developer & Business Tools

A collection of privacy-focused developer and business productivity tools designed to process files locally in the browser.

The goal is simple: provide useful document and developer utilities without requiring users to upload potentially sensitive files to third-party online services.

## Features

- PDF compression
- PDF merging
- PDF splitting
- Image to PDF conversion
- PDF signing
- JSON/XML formatting
- Browser-based local processing
- Responsive interface
- No backend server required

## Getting Started

### 1. Save the project

Save or clone the project to your preferred directory.

### 2. Open a terminal

Navigate to the project directory:

```bash
cd /path/to/project
```

For example, on Windows:

```powershell
cd C:\path\to\project
```

### 3. Start the local server

Run Python's built-in HTTP server:

```bash
python -m http.server 8000
```

### 4. Open the application

Open your browser and visit:

```text
http://localhost:8000
```

That's it. No installation or backend server is required.

## Why Local Processing?

Many document-processing websites require users to upload files to remote servers. This can be undesirable when working with sensitive business, financial, personal, or confidential documents.

This project takes a different approach by performing supported operations directly in the browser.

**Your files stay on your device during processing.**

## Privacy

- Files are processed locally in the browser.
- No application backend is required for the core tools.
- Documents do not need to be uploaded to a third-party processing service.
- Internet access may still be required for any dependencies that have not yet been bundled locally.

## Technology

The tools are built using browser-based technologies, including:

- HTML
- CSS
- JavaScript
- PDF.js
- jsPDF
- pdf-lib
- Browser File APIs
- Canvas APIs
- DOM APIs

## Project Structure

A typical project structure looks like:

```text
local-tools/
├── index.html
├── merge.html
├── split.html
├── image2pdf.html
├── json_formatter.html
├── pdf-sign.html
└── pdf-compressor/
    ├── pdf-compressor.html
    ├── pdf.mjs
    └── pdf.worker.mjs
```

The exact structure may evolve as additional tools are added.

## Development

Because the project is browser-based, development is straightforward:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

Make changes to the source files and refresh the browser to test them.

## Design Principles

The project follows a few core principles:

### Privacy First

Sensitive documents should not have to leave the user's device just to perform a simple operation.

### Simple to Use

Each tool should have a clear interface with minimal configuration and obvious actions.

### Local by Default

Where technically practical, processing should happen entirely within the browser.

### No Unnecessary Infrastructure

The tools should be usable without requiring a database, API server, or document-processing backend.

### Consistent User Experience

All tools share a common visual language, including:

- Clean light interface
- Consistent cards and spacing
- Drag-and-drop file selection
- Clear progress and status feedback
- Responsive layouts
- Consistent action and download buttons

## Running in a Demo

To demonstrate the project:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

Select a tool from the home page and start processing a document.

## License

This project is not licenced.
