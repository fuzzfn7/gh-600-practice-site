# GH-600 Practice Site

A self-contained study website for **GitHub Certified: Agentic AI Developer (beta)** / **Exam GH-600**.

Source of truth: <https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/gh-600>

## What is included

- Domain-by-domain study guide for all six GH-600 areas
- Wesley-specific readiness map: what is already familiar vs what needs focused study
- Interactive practice quiz with 36 original questions
- 24-question mock exam mode
- Missed-question review mode
- Flashcards
- Local domain score tracking with `localStorage`
- Pass-ready checklist
- Two-week study plan
- Practical GitHub/Copilot/MCP/agent workflow labs
- Glossary of GitHub/Copilot/agentic AI terms

## Important ethics note

This site does **not** contain exam dumps, leaked questions, or proprietary test content. The questions are original practice questions derived from the public study guide topics.

## Run locally

Open `index.html` directly in a browser, or run a local static server:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://127.0.0.1:8080
```

## Recommended study workflow

1. Read the official study guide once.
2. Read the domain cards on this site.
3. Take a 24-question mock exam.
4. Review missed questions.
5. Build the six labs as small markdown/YAML artifacts in a practice repo.
6. Re-take mock mode until all domains are consistently above 80%.
7. Schedule GH-600 when Domain 2 (tool use/MCP/environment) stops feeling fuzzy.

## Files

- `index.html` — complete static website with embedded CSS and JavaScript
- `README.md` — this file

## Deployment

This repo is designed to work with GitHub Pages from the `main` branch root.
