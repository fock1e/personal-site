# personal-site

One-page personal site for Ashot Arushanyan — DevOps / SRE engineer.

The whole site is a single self-contained `index.html`: inline CSS, system fonts,
zero JavaScript, no external requests, no tracking. Light/dark via
`prefers-color-scheme`, mobile-first, honors `prefers-reduced-motion`.

The look is a "paper terminal": monospace character grid (page width snaps to
whole character columns), key:value metadata block, one green accent.

Pages: `/` (home) · `/cv/` (printable CV — ⌘P gives the PDF) · `404.html`
(served by GitHub Pages for unknown paths). `og.png` is the social preview
card; only link scrapers fetch it, visitors still load nothing but the page.

## Preview locally

```bash
open index.html
```

## Deploy

Any static host — it's one file.
