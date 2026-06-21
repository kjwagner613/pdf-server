# PDF Server Workspace

This workspace contains several static HTML/CSS mini-sites and document pages.

## Structure

- `home.html`, `index.html`, `style.css`: root landing pages/styles
- `bplan-v1/`: business plan page (v1)
- `bplan-v2/`: business plan page (v2)
- `count-1/`: count 1 page with PDF attachment
- `count-2/`: count 2 page with PDF attachment
- `DD-futureVision/`: future vision page with PDF attachment
- `Info-release-auth/`: information release page with PDF attachment
- `richardPilotGroup/`: pilot group page with PDF attachment

## Run Locally

Because this is a static site workspace, you can run it with any local web server.

### Option 1: VS Code Five Server

1. Open this folder in VS Code.
2. Start Five Server from `home.html` or `index.html`.
3. Open the served URL in your browser.

### Option 2: Python HTTP server

From this folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Notes

- Paths to PDFs are relative, so keep each PDF in its current folder.
- `DD-futureVision` currently uses `infdex.html` (spelling kept as-is).

## Maintenance Checklist

- Keep HTML filenames and links in sync.
- Keep associated PDFs in the same project folder.
- Test each page after content edits in desktop and mobile widths.
