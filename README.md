# Waiz Media OS — Raw Export Archive

Frozen Google Drive export for Waiz Media OS migration. **Do not edit** files here.

## Relationship to Wm-os

| Repo | Role |
|------|------|
| [Wm-os](https://github.com/gwadawg/Wm-os) | Canonical operating system (`docs/`), skills, team-doc publish tooling |
| **wm-os-archive** (this repo) | Raw `.docx`, `.xlsx`, and other exports — evidence only |

Clone both as siblings (recommended):

```text
~/Documents/GitHub/
├── Wm-os/
└── wm-os-archive/
```

## Layout

- `waiz-drive-export/Waiz Media OS/` — full Drive tree (`00 _ Company DNA`, `01 _ Acquisition`, etc.)

## Rules

1. Never edit files under `waiz-drive-export/`.
2. Convert operating content into canonical Markdown in `Wm-os/docs/` only.
3. Use [Wm-os/docs/_inventory/google-drive-inventory.md](https://github.com/gwadawg/Wm-os/blob/main/docs/_inventory/google-drive-inventory.md) before converting new files.

## Provenance paths

Canonical docs in `Wm-os` may list `source_document: source-docs/waiz-drive-export/...` in frontmatter. That path is historical. On disk, the same file lives here:

```text
waiz-drive-export/<rest of path after source-docs/waiz-drive-export/>
```

Example: `source-docs/waiz-drive-export/Waiz Media OS/00 _ Company DNA/...` → `waiz-drive-export/Waiz Media OS/00 _ Company DNA/...`
