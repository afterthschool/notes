# aftertheschool — notes

A collaborative repository of school notes, organised by board and class.

## Boards & classes

- [Class 10 — Andhra Pradesh (SSC)](./class-10-ap/)

More boards and classes will be added over time.

## Repository layout

```
notes/
├── class-10-ap/              # Andhra Pradesh SCERT — Class 10
│   ├── physical-science/
│   ├── biological-science/
│   ├── mathematics/
│   ├── social-studies/
│   ├── english/
│   ├── telugu/
│   └── hindi/
├── assets/                   # Shared images, figures, diagrams
│   └── class-10-ap/
├── tasks/                    # Per-contributor task lists
└── .github/
    └── CODEOWNERS
```

Each subject folder contains a chapter-wise breakdown. A chapter lives in its
own directory (e.g. `chapter-1/`) and is written as Markdown — `index.md` for
the chapter overview and `section1.md`, `section2.md`, … for individual
sections. Figures and images are stored under `assets/<class>/<subject>/` and
referenced with relative paths from the note.

## Contributing

- Main owner: [@avinashreddydev](https://github.com/avinashreddydev)
- Collaborator: [@kavya-collab](https://github.com/kavya-collab)

Pull requests are welcome. All changes are reviewed by the code owners listed
in [`.github/CODEOWNERS`](./.github/CODEOWNERS). Keep notes accurate to the
official textbook, cite activity/figure numbers, and prefer plain Markdown so
content renders well on GitHub.

## Conventions

- Use Markdown (`.md`) for all notes.
- One chapter per folder. Name folders `chapter-<n>`.
- Store figures under `assets/<class>/<subject>/` and reference them with
  relative links.
- Frontmatter on every `index.md`:

  ```
  ---
  title: <chapter title>
  description: <short summary>
  ---
  ```
