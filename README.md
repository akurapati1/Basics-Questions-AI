# AI / ML Engineering — Interview Field Manual

A fast, single-file, **zero-dependency study guide** for AI / ML engineering interviews. 50 curated questions across five domains, with concise model answers, live search, and per-question progress tracking.

| Domain | Topics |
|---|---|
| **LLM Systems** | Transformers, attention, prompting, fine-tuning, evaluation |
| **RAG & Vector Databases** | Chunking, embeddings, retrieval, re-ranking, ANN indexes |
| **MLOps & Deployment** | Serving, monitoring, drift, CI/CD for ML |
| **Deep Learning** | Optimisation, regularisation, architectures |
| **Python / Backend** | Concurrency, APIs, data structures, system design |

## Features
- Instant full-text search with result counts
- Mark questions as reviewed; progress bar and counter persist in the browser
- Expand/collapse all, reset progress, sticky section navigation, responsive layout (mobile bar)
- One `index.html` — no build step, no framework, works offline (fonts fall back gracefully)

## Run locally
```bash
python3 -m http.server 8000     # then open http://localhost:8000
```
or simply open `index.html` in a browser.

## Deployment
Every push to `main` is published to **GitHub Pages** by `.github/workflows/static.yml`
(enable *Settings → Pages → Source: GitHub Actions* once).

## Customising
Questions live in the `DATA` array near the bottom of `index.html`. Add a section or question object and the navigation, search and progress tracking pick it up automatically.
