# Splunk Certification Trainer

A practice-exam and flashcard app for the Splunk Core Certified Power User exam (SPLK-1002),
plus the Admin, Cloud Admin, and Enterprise Architect tracks. Runs entirely in the browser.
No install, no build, no dependencies.

## Run it

Two ways, pick whichever:

**1. Just open the file (easiest)**

Download the folder, then double-click `index.html`. It opens in your browser and works offline.
Keep `index.html` and `data.js` in the same folder.

**2. Local server (optional)**

If you'd rather serve it:

```
python3 -m http.server 8080
```

Then open http://localhost:8080 in your browser.

## What's inside

- 226 practice questions across the 10 exam blueprint categories
- Timed exam mode and untimed practice mode
- Pick your session length (10, 20, 30, 50, or all)
- 100 rapid-review flashcards grouped by topic
- Category drills for weak areas
- Progress, streaks, and score history saved in your browser

## Files

- `index.html` - the app (UI, styles, logic)
- `data.js` - the questions, flashcards, and exam info
