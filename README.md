# StudySync 🎓

**A polished student productivity workspace** built with HTML, CSS, and vanilla JavaScript. Plan tasks, focus with a Pomodoro timer, and see your study rhythm at a glance.

![StudySync](https://placehold.co/1200x630/7357e8/ffffff?text=StudySync+%7C+Your+study%2C+in+sync)

## Features

- **Task management:** Create, complete, search, filter, prioritize, and delete tasks.
- **Pomodoro focus room:** 25-minute focus, 5-minute short break, and 15-minute long break timers.
- **Study insights:** Weekly focus visualization, completion rate, completed sessions, and focus minutes.
- **Personalized workspace:** Responsive layout, dark mode, accessible controls, and encouraging empty states.
- **Local-first persistence:** Tasks, theme, and focus history are saved in browser `localStorage`.
- **No build step:** Runs as a static site with no framework or package installation.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in your browser.
3. For the most reliable local development, use VS Code's **Live Server** extension or run `python -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Deploy on GitHub Pages

1. Create a GitHub repository named `StudySync`.
2. Upload `index.html`, `styles.css`, `app.js`, and this README to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. Wait for the Pages URL to appear in the same section.

## Project structure

```text
StudySync/
├── index.html     # App layout and accessible dialog
├── styles.css     # Responsive design system and dark mode
├── app.js         # Task state, timer, charts, and local persistence
└── README.md
```

## Notes

- Data stays in the current browser on the current device; it is not synced across devices.
- Focus time is recorded when a focus timer finishes. Keep the tab open during a session.
- The Google Fonts import is optional; system fallback fonts are included.
- This is a front-end portfolio project, not a medical or academic performance assessment.

## Portfolio talking points

- State persistence with `localStorage`
- Event delegation and DOM rendering
- Timer lifecycle and interval cleanup
- Responsive layout and theme variables
- Accessible semantic forms and dialog interactions

## License

MIT — see [LICENSE](LICENSE).
