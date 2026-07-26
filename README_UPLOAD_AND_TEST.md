# Portfolio Web Preview Package

## Local test
Open `index.html` directly in Chrome/Edge after extracting the ZIP. The carousel arrows and Open web preview buttons should work.

If your browser blocks local iframe loading, run this from inside the extracted folder:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## GitHub upload
Upload all items in this folder to the repository root:

- `index.html`
- `.nojekyll`
- `live/`
- optional README files

Do not upload the original ZIP application source files to the public repository.


## Visual identity update

This package uses a white and blue visual identity with light contour-line backgrounds across the main portfolio and all `live/` product preview pages.

Upload the full package contents to GitHub Pages:

```text
index.html
.nojekyll
live/
README_UPLOAD_AND_TEST.md
```

Do not upload the parent folder as a folder inside the repository; upload its contents to the repository root.
