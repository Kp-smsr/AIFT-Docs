# AIFT Documentation

This repository contains the source for the AIFT (Automated Intelligent Functional Testing) documentation website generated with MkDocs and the Material theme.

## Purpose

Provide a professional, searchable, and maintainable documentation website for AIFT.

## Prerequisites

- Python 3.8+
- Git

## Installation

Install project dependencies:

```bash
pip install -r requirements.txt
```

## Local development

Run a live-reloading documentation server:

```bash
mkdocs serve
```

Open http://127.0.0.1:8000 in your browser.

## Build

Build the static site:

```bash
mkdocs build
```

The site will be generated in the `site/` directory.

## Deploy to GitHub Pages

This project includes a GitHub Actions workflow that builds and deploys the site on pushes to the `main` branch.

1. Push your repository to GitHub.
2. Ensure Pages is configured to serve from the `gh-pages` branch or use the Actions workflow to deploy.

## Repository structure

```
AIFT-Documentation/
├── docs/
│   ├── index.md
│   ├── overview.md
│   ├── definitions.md
│   ├── test-plan.md
│   ├── test-cases.md
│   ├── test-scripts.md
│   ├── evaluation-framework.md
│   ├── ctx-vs-aift.md
│   └── results.md
├── mkdocs.yml
├── requirements.txt
└── README.md
```

## Notes

- Update `mkdocs.yml` to set `repo_name` and other metadata.
- The workflow uses GitHub Actions to deploy to GitHub Pages automatically.