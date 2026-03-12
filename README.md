# Modo Energy Charts

Interactive Plotly charts deployed to GitHub Pages.

## Structure

```
charts/
├── lenders-report/
│   ├── gb/
│   │   ├── 2026-q1/    ← Q1 2026 charts (permanent)
│   │   ├── 2026-q2/    ← Q2 2026 charts (permanent)
│   │   └── ...
│   └── de/
│       ├── 2026-q1/
│       └── ...
└── (other one-off charts here)
```

## Quarterly convention

Each quarter gets its own folder. Old quarter charts **stay live** at their original URLs — never overwrite or delete a previous quarter's folder.

When a new quarter starts:
1. Create `charts/lenders-report/{market}/{YYYY-qN}/`
2. Generate all charts into that folder
3. Push — old quarter URLs remain live

## URL pattern

```
https://modo-arthur.github.io/modo-charts/charts/lenders-report/gb/2026-q1/gb-bess-buildout.html
```

## Iframe embed

```html
<iframe src="https://modo-arthur.github.io/modo-charts/charts/lenders-report/gb/2026-q1/gb-bess-buildout.html"
        width="100%" height="550" frameborder="0"
        loading="lazy" style="border: none;"></iframe>
```

## Current charts

### GB Lenders Report — Q1 2026
| Chart | URL |
|---|---|
| GB BESS Buildout by Duration | [gb-bess-buildout.html](https://modo-arthur.github.io/modo-charts/charts/lenders-report/gb/2026-q1/gb-bess-buildout.html) |
