# Net-it

Light notes for heavy networking.

Net-it is a lightweight networking memory prototype created for Codex Meetup. It helps you remember meetups, people, and conversation keywords without writing long journals.

## Demo

This is a browser-based demo with sample data. Meetup and people notes are stored locally in the browser using `localStorage`; no account or backend is connected yet.

Core flows:

- Prepare for the next meetup with topic-based conversation starters.
- Pin a meetup as a tactile sticky note.
- Keep lightweight people notes with conversation keywords.
- See your meetup history as a dot-to-dot path in Insights.

## Run locally

Open `index.html` directly, or serve the folder over HTTP for the PWA service worker:

```powershell
python -m http.server 4173
```

Then visit `http://localhost:4173`.

## Status

This is a deployable frontend prototype. Authentication, cloud sync, production AI generation, and push notifications are planned for a future version.

## License

Copyright (c) 2026 thddaisy. All rights reserved. See [LICENSE.md](LICENSE.md).
