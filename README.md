# timelyversion2
# Timely - AI-Enhanced Student Schedule Builder

Timely is a smart weekly schedule optimizer built for students. It combines performance-based predictions, intelligent meal scheduling, and drag-and-drop flexibility to help you manage classes, clubs, tasks, and daily habits all in one place.

## Features

- **Performance Assessment** — Typing and reading speed tests that calibrate task duration predictions to your actual pace
- **Smart Meal Scheduling** — Meals are automatically placed around your fixed commitments at reasonable times, never overlapping with classes or clubs
- **AI-Powered Task Predictions** — Tracks how long tasks actually take and uses weighted history to improve future estimates
- **Drag-and-Drop Calendar** — Rearrange meals and flexible tasks visually across a full weekly grid; fixed events (classes/clubs) stay locked
- **Conflict Prevention** — Tasks and meals cannot be dropped onto occupied time slots
- **Task Templates** — Save frequently recurring tasks for quick reuse
- **Calendar Export** — Export your full schedule as an `.ics` file compatible with Google Calendar, Apple Calendar, and Outlook
- **Persistent Storage** — Your classes, clubs, habits, task history, and performance data are saved in localStorage across sessions

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/riayagielski/timelyversion2.git
   ```
2. Open `index.html` in a browser, or use **Live Server** in VS Code (right-click → Open with Live Server)

> Requires an internet connection to load React, Tailwind CSS, and Babel from CDN.

## How It Works

1. **Performance Assessment** — Complete typing and reading speed tests (or skip them)
2. **Schedule Setup** — Add your classes, clubs, flexible tasks, and daily habits (wake time, meals, productive hours, session length)
3. **Generate Schedule** — Timely auto-schedules meals around fixed events and places tasks during your most productive hours, balanced across the week
4. **Refine** — Drag and drop to adjust, log actual task times to improve predictions, and export when ready

## Tech Stack

- React 18 (via CDN)
- Tailwind CSS (via CDN)
- Babel standalone (for in-browser JSX)
- Vanilla localStorage for persistence
- No build step required — single HTML file

## Color Legend

| Color | Event Type |
|-------|-----------|
| 🔵 Blue | Class (fixed) |
| 🟣 Purple | Club (fixed) |
| 🟠 Orange | Meal (draggable) |
| 🔴 Red | High priority task (draggable) |
| 🟡 Yellow | Medium priority task (draggable) |
| 🟢 Green | Low priority task (draggable) |

## License

This project is for personal and educational use.
