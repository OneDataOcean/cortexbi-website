# CortexBI — website

Marketing site for **CortexBI**, an agentic AI data analytics platform: ask a question
in plain English, get a governed query, a chart, and an insight — with every step
visible.

Live at **[cortexbi.in](https://cortexbi.in)**.

## What's here

A static, self-contained site. No build step, no dependencies, no framework.

```
index.html    the full site (styles inlined; fonts from Google Fonts)
404.html      not-found page
CNAME         custom domain for GitHub Pages
.nojekyll     serve files as-is, skipping Jekyll processing
```

## Local preview

```bash
python3 -m http.server 8765
# then open http://localhost:8765
```

## Deploying

GitHub Pages serves the `main` branch from the repository root. Pushing to `main`
publishes; there is nothing else to run.
