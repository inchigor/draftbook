# Draftbook 📝

A small, dependency-free, local-first app for writing and saving selected drafts in your browser.

**[Live Demo](https://inchigor.github.io/draftbook/)**

## Features

- One large, distraction-free editor
- Automatic local recovery of the current text
- Explicit **Save for later** workflow for keeping drafts
- Saved draft history with reopen and delete actions
- Character, word, and line counters
- English and Russian interfaces
- Light and dark themes with saved preferences
- Responsive desktop and mobile layout
- No uploads, accounts, tracking, frameworks, or external dependencies

## How it works

The current text is automatically stored in `localStorage`, so reloading or reopening the page restores it.

When a text is worth keeping, press **Save for later**. It is added to the saved draft list and the editor opens a new blank page. Press **New** when you simply want to discard the current scratch text and start over.

Saved drafts can be opened again, edited, updated, or deleted.

## Privacy

Everything stays in the browser. The app does not send entered text or saved drafts to a server.

Because drafts are stored in browser `localStorage`, clearing the site's browser data will remove them.

## Tech

Plain HTML, CSS, and JavaScript. No build step is required.

## License

MIT
