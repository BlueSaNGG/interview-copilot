# Interview Copilot

A private, client-side mock-interview coach. Bring your own story bank, pick a behavioral question, answer out loud (or in writing), and get scored on structure, metrics, and senior signal.

**Live demo:** https://bluesangg.github.io/interview-copilot/

## Privacy model

There is no server. Your story bank, answers, and session history live only in your browser's `localStorage`. Nothing is uploaded anywhere. The scoring is a transparent client-side heuristic — no API calls, no tracking.

This is what makes it safe to practice with real career material: the code is public and generic, your stories never leave your machine.

## Features

- **Story bank** — paste STAR stories as markdown; autosaves locally; ships with two sample stories
- **Mock interview** — 10 built-in senior-engineering behavioral questions (each with "what good looks like" hints), plus your own custom questions
- **Speech timer** — 90–120 second target window with visual markers
- **Heuristic scoring** — conciseness (word count → speaking time), STAR completeness, metrics detection, senior-signal vocabulary, each 1–5 with concrete fixes
- **Session history** — every scored round logged locally, newest first

## Scoring rubric

| Dimension | 5/5 looks like |
|---|---|
| Conciseness | 200–330 words (≈90–120s spoken) |
| STAR completeness | Situation, Task, Action, Result all present |
| Metrics | At least one concrete number (%, before/after, scale) |
| Senior signal | Tradeoff named, stakeholder aligned, rollout de-risked |

## Roadmap

- Optional BYO-LLM-key feedback for qualitative scoring
- Spoken-answer transcription via Web Speech API
- Question packs per role (platform, backend, EM)

## Local development

It's a single `index.html` — just open it. No build step.
