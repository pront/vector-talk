# GitHub Maintainer Month 2026

Companion page for two talks at **GitHub Maintainer Month NYC, May 2026** by
[Pavlos Rontidis](https://github.com/pront) and
[Adrien Guillo](https://github.com/guilload) (Datadog COSE team).

- **Vector: One Agent to Rule Them All?** (Pavlos): Vector as a unified
  observability agent for logs, metrics, and traces.
- **Quickwit: Subsecond Full-Text Search on Object Storage** (Adrien).

Live: <https://pront.github.io/maintainer-month-vector-2026/>

## Run locally

```sh
python3 -m http.server 8000 & open http://localhost:8000
```

Or, with no-cache during edits:

```sh
npx http-server -c-1 -o
```

## Editing

`index.html` is the source of truth, served by GitHub Pages from `main`.
Just edit, commit, push, and Pages redeploys.
