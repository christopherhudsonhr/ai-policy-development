# AI Policy Development

An HR Soul tool that walks HR leaders through building a first draft of an AI policy. Users answer mostly Yes/No questions across 7 steps and download an editable Word document. Answers stay in the user's browser; nothing about their policy is sent to HR Soul.

## Pages

- `index.html` — the app.
- `preview.html` — testing version with sample answers for a fictional company (Harborview Staffing Partners), a Jump to menu, and nothing saved.

## Files

- `assets/` — HR Soul logos and the current free download (`freebie.pdf`).
- `vendor/docx.iife.js` — the library that builds the Word file in the browser.

## How updates work

The policy wording and app source are maintained outside this repository and built into `index.html` and `preview.html`. To change wording, update the source and rebuild rather than editing these files by hand.
