# GH-600 Interactive Trainer

A visual, interactive study website for **GitHub Certified: Agentic AI Developer / Exam GH-600**.

Source of truth: <https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/gh-600>

## What is included

- Visual domain map for all six GH-600 areas
- Wesley-specific “already know vs study next” cards
- Interactive simulators:
  - Agent SDLC flow sequencing
  - Autonomy/risk sorter
  - MCP/tool permission matrix
  - Failure root-cause triage
- Practice mode with instant feedback
- Full-bank mock exam mode with no answer reveal until submit
- Domain score report after mock exam
- Missed-question review mode
- Flashcards
- Local progress tracking with `localStorage`
- Pass-ready checklist
- Two-week interactive study plan
- Practical GitHub/Copilot/MCP/agent workflow labs
- Glossary of GitHub/Copilot/agentic AI terms

## Mock exam note

This site does **not** contain real exam questions, leaked content, or dumps. The mock exam uses original questions based on the public GH-600 study guide topics.

## Run locally

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://127.0.0.1:8080
```

## Recommended study workflow

1. Use **Visual learn** to click through the exam map.
2. Use **Interactive trainers** before reading long explanations.
3. Drill weak domains in **Practice mode**.
4. Take the **full-bank mock exam** without hints.
5. Review domain score report and missed explanations.
6. Build the labs as small artifacts in a practice repo.
7. Repeat until each domain is consistently above 80%.

## Files

- `index.html` — complete static site with embedded CSS and JavaScript
- `README.md` — this file

## Deployment

Designed for GitHub Pages from the `main` branch root.
