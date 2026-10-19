# SAT Math HQ

A single-page tutoring hub for running SAT Math classes: timetable, classes and students, homework tracking with scores, and a curriculum checklist with linked materials.

## Run it

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

It can also be hosted as-is with GitHub Pages (Settings → Pages → deploy from the `main` branch).

## Data

- Opened as a local file or website, everything is saved in that browser's `localStorage`.
- Opened as a claude.ai artifact, data syncs to your Claude account.
- Use **Export** / **Import** (top bar) to back up or move data between devices as JSON.

On first run the app loads sample classes, students and a syllabus so you can see how it works. Use **Erase all data** on the Today page to start clean.
