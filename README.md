# PM&R Study Notes

Physical Medicine & Rehabilitation study notes by Negar Moradian, MD, MPH.

**Live site:** https://negarmrdn.github.io/pmr-notes/

## How it works

- Notes are Markdown files in `docs/`, one folder per topic area.
- Every push to `main` rebuilds and publishes the site through GitHub Actions (`.github/workflows/publish.yml`). It takes about a minute.
- Built with [MkDocs](https://www.mkdocs.org/) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).
- Section titles and sidebar order live in the `.pages` files.

See `docs/how-to-add-notes.md` (or the "How to add notes" page on the site) for the note template.

## Preview locally (optional)

```bash
pip install -r requirements.txt
mkdocs serve
```

Personal study notes for education. Not medical advice. No patient information.
