# 🏎️ Office Racer Showdown

A just-for-fun experiment: I took photos around my office desk and asked two AI models
to build a small browser car game set in that office. Each one got the same photos and idea.

| Game | Built by | Folder |
|------|----------|--------|
| DSL Grand Prix | Claude Opus 5.5 | [`claude/`](claude/) |
| DSL Micro GP | Gemini 4 | [`gemini/`](gemini/) |

**Play online:** https://ahmad-zurih/ai-office-games/

> ⚠️ This is a casual side project, not a benchmark or an official project of any organisation.
> The code is AI-generated ("vibe coded") and published as-is.

## Run locally

Each game is a single self-contained `index.html`, so there's no build step.

- Open `index.html` in your browser, **or**
- Serve the folder: `python3 -m http.server 8000`, then go to http://localhost:8000

## Structure

```
index.html          landing page linking to both games
claude/index.html   Claude Opus 5.5's game
gemini/index.html   Gemini 4's game
```
