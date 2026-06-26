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
- Challenge practice mode with plausible distractors, instant feedback, skipped-question tracking, and per-section new batches
- Batch controls for 5-question, 10-question, or all-in-section drills
- Full-bank challenge mock exam mode (60 questions) with no answer reveal until submit
- Domain score report after mock exam
- Missed-question and skipped-question review modes
- Flashcards
- Local progress tracking with `localStorage`
- Pass-ready checklist
- Two-week interactive study plan
- Practical GitHub/Copilot/MCP/agent workflow labs
- Glossary of GitHub/Copilot/agentic AI terms

## Mock exam note

This site does **not** contain real exam questions, leaked content, or dumps. The mock exam uses 60 harder original scenario questions based on the public GH-600 study guide topics.

## Run locally

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://127.0.0.1:8080
```

## Official Microsoft Learn course path

Useful official baseline:

- Part 1: https://learn.microsoft.com/en-us/training/paths/gh-developing-agentic-systems-1
- Part 2: https://learn.microsoft.com/en-us/training/paths/github-agentic-systems-part-two/github-agentic-systems-part-two
- Instructor-led course page: https://learn.microsoft.com/en-us/training/courses/gh-600t00 — currently listed by Microsoft as available on 7/20/2026.

Use Microsoft Learn for official terminology and module order; use this trainer for challenge questions, skipped/missed tracking, and mock exam pressure.

## Recommended study workflow

1. Use **Visual learn** to click through the exam map.
2. Use **Interactive trainers** before reading long explanations.
3. Drill weak domains in **Practice mode** using New batch for section; the questions are intentionally scenario-heavy and less obvious.
4. Take the **full-bank mock exam** without hints.
5. Review domain score report and missed explanations.
6. Build the labs as small artifacts in a practice repo.
7. Repeat until each domain is consistently above 80%.

## Files

- `index.html` — complete static site with embedded CSS and JavaScript
- `README.md` — this file

## Deployment

Designed for GitHub Pages from the `main` branch root.
