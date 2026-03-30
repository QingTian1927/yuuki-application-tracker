# Yuuki's Application Tracker (YAT)

This is a small personal project I made for convenience so I can track applications in one place.

It is an offline-first browser app, with data saved locally on your device.

## Features

- Add, edit, delete, and search application records
- Filter and sort by status, type, source, and location
- Dashboard metrics and analytics charts
- Import and export data (JSON/CSV)
- Local profile and theme settings (System/Light/Dark)

## Quick Start

1. Open index.html in a modern browser.
2. Use + Add Application to create entries.
3. Use Settings > Data to import/export backups.

Optional local server:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Notes

- Everything is stored locally (IndexedDB + localStorage).
- Importing JSON replaces existing records.
