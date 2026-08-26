# Atomic Ledger — Habit Builder

A beautiful, self-contained habit tracking web application built as a single HTML file with no external dependencies (besides Google Fonts). Track your habits, set milestones, and visualize your progress with elegant charts and statistics.

## Features

- **Habit Management**: Create, edit, and delete habits with custom colors and icons
- **Flexible Actions**: Support for identity actions (yes/no) and numeric actions (reps, minutes, pages, etc.)
- **Streak Tracking**: Monitor current and longest streaks for each habit
- **Milestones**: Set custom goals like longest streak, totals, or personal bests
- **Analytics & Reports**:
  - Perfection gauge (completion rate)
  - Weekday pattern charts
  - Perfection trend over time (daily/weekly/monthly)
  - Action trend lines for numeric habits
- **Local Storage**: All data is stored locally in your browser—no server required
- **Responsive Design**: Works on desktop and mobile devices
- **Accessibility**: Keyboard navigation and reduced motion support

## Usage

1. Open `index.html` in any modern web browser
2. Click "+ New habit" to create your first habit
3. Fill in the habit details:
   - Name and optional goal
   - Color and icon
   - Actions (what you'll track daily)
4. Log your progress daily by checking off actions or entering numeric values
5. View your progress in the Report tab

## Project Structure

```
├── index.html    # Single-file application (HTML + CSS + JavaScript)
└── README.md     # This file
```

## Technology Stack

- **HTML5** - Semantic structure
- **CSS3** - Custom styling with CSS variables, flexbox, and grid
- **Vanilla JavaScript** - No frameworks, pure ES6+
- **Google Fonts** - Fraunces, IBM Plex Mono, and Inter typefaces
- **LocalStorage API** - Persistent client-side data storage

## Customization

You can customize the appearance by modifying the CSS variables in the `<style>` section:

- `--paper`, `--paper-deep` - Background colors
- `--ink`, `--ink-soft` - Text colors
- `--amber`, `--sage`, `--rust` - Accent colors
- `--radius` - Border radius
- `--shadow-sm`, `--shadow-md` - Shadow definitions

## Privacy

All your habit data is stored locally in your browser's LocalStorage. No data is sent to any server.

## Browser Support

Works in all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## License

This project is provided as-is for personal use.

---

*Built with care for building better habits, one day at a time.*
