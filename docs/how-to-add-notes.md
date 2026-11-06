# How to add notes

!!! warning "This site is public"
    Anyone with the link can read it. Never include patient names, dates, MRNs, photos or other identifying details.

## With Claude (easiest)

In a study session, say something like *"add this to my notes site"* or *"make a note on brachial plexopathy"*. Claude writes the note in the template below and publishes it. It's live about a minute later.

## Yourself, on GitHub

**To edit a page:** click the :material-file-edit-outline: pencil icon at the top right of the page. Make your changes, then click **Commit changes**. The site updates in about a minute.

**To add a new page:**

1. Go to [github.com/negarmrdn/pmr-notes](https://github.com/negarmrdn/pmr-notes) and open the `docs` folder, then the section folder (for example `msk-sports`).
2. Click **Add file → Create new file**.
3. Name it in lowercase with dashes, ending in `.md`. For example: `rotator-cuff-tears.md`.
4. Paste the template below, fill it in, and click **Commit changes**.
5. Optional: add a link to it on that section's `index.md` page, and under "Recently added" on the home page.

New pages show up in the sidebar and in search automatically.

## Note template

```markdown
---
tags:
  - high-yield
---

# Topic name

!!! abstract "At a glance"
    Two or three sentences: what it is and why it matters.

## Key concepts

- 

## High-yield for boards

!!! tip "Board pearls"
    - 

!!! warning "Easy to mix up"
    - 

## Clinical pearls

!!! example "From the wards"
    - 

## Related

- [Another note](../section-folder/another-note.md)

## Sources

- Braddom's PM&R, ch. __
```

## Formatting cheat sheet

| You type | You get |
|---|---|
| `**bold**` | **bold** |
| `*italic*` | *italic* |
| `==highlight==` | ==highlight== |
| `- item` | a bullet point |
| `1. item` | a numbered list |
| `[text](other-note.md)` | a link to another note |
| `!!! tip "Title"` + indented lines | a colored callout box |
| `??? note "Title"` + indented lines | a collapsible box (good for self-quizzing) |

Tables use `|` between columns. Copy one from an existing note and edit it.
