# 2D WFC

## Run locally
ES modules don't load from `file://`, so serve the folder:
- VS Code: right-click `index.html` → "Open with Live Server"
- or `python -m http.server`, then open http://localhost:8000

## Deploy (InfinityFree)
Upload the folder contents to `htdocs/<folder>/` via File Manager or FTP.
Paths are relative, so any folder name works. No build step needed.
