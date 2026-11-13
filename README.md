# THE LIFT DEPT. Team Race Timer

A full-screen team race timer for The Lift Dept. gym (Sydney). Open it on a laptop, phone or the gym TVs.

- Each team has its own clock: Start / Pause / Resume / Reset
- Shared time cap (40 minutes by default), editable before anyone starts
- Start all, Pause all, and Reset all at the top
- Finish locks that team's time and place (fastest finish is #1)
- A team that hits the cap shows CAP
- Times are based on real timestamps and survive a page refresh
- **Rotate for portrait TV** turns the layout 90° so it reads upright when a landscape laptop is cast to a portrait-mounted TV

Built as a single `index.html` file. All race state stays in the browser (`localStorage`).
