# Time Master

A feature-rich, single-file timer web application built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies, no installation required — just open the file in any browser.

---

## Features

### ⏱ Timer
- Countdown and countup modes
- Animated circular progress ring
- Visual color warnings as time runs low (yellow → red)
- Quick presets: 1 min, 5 min, 10 min, 15 min, 25 min, 1 hour
- Custom time input (hours, minutes, seconds)
- Add extra time mid-session (+1 minute button)

### 🍅 Pomodoro Mode
- Built into the Timer tab
- 4-session work/break cycle (25 min work / 5 min break)
- Session dot tracker with visual progress
- Auto-advances between work and break phases

### ⏲ Stopwatch
- Millisecond precision display
- Lap recording with split times
- Fastest and slowest lap highlighted automatically
- Reset and resume support

### 🔔 Alarm
- Set multiple named alarms by time
- Toggle alarms on/off individually
- Delete alarms
- Fires sound + browser notification when triggered

### 🌍 World Clock
- Live clocks for 8 major cities
- Updates every second
- Shows local date alongside time
- Cities: New York, London, Paris, Dubai, Mumbai, Singapore, Tokyo, Sydney

### 🫁 Breathing Guide
- Three guided techniques:
  - **4-7-8** — Relaxation breathing
  - **Box Breathing** — Used by Navy SEALs for focus
  - **Wim Hof Method** — Energizing and alertness
- Animated expanding/contracting ring
- Phase labels and countdown per breath step

### 📊 Stats
- Sessions completed today
- Total minutes focused
- Alarms set
- Session history log (last 10 sessions)

### 🎵 Sound Alerts
- Three built-in sounds via Web Audio API (no audio files needed):
  - Bell
  - Beep
  - Chime
- Sound visualizer bars animate when timer is running
- Preview sounds any time from the sidebar

### ⊞ Focus Mode
- Fullscreen distraction-free overlay
- Shows current timer/stopwatch time in large display
- Exit with ESC key or button

### 🌗 Theme
- Dark mode (default)
- Light mode toggle

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Start / Pause timer |
| `R` | Reset timer |
| `F` | Toggle Focus Mode |
| `L` | Record lap (Stopwatch) |
| `Escape` | Exit Focus Mode |
| `1` | Switch to Timer tab |
| `2` | Switch to Stopwatch tab |
| `3` | Switch to Alarm tab |
| `4` | Switch to World Clock tab |
| `5` | Switch to Breathing tab |

---

## Getting Started

No installation or setup needed.

1. Download `timer.html`
2. Open it in any modern web browser
3. That's it — everything runs locally in the browser

> **Tip:** Allow browser notifications when prompted for alarm alerts to work even when the tab is in the background.

---

## Browser Compatibility

Works in all modern browsers:

- Chrome / Chromium
- Firefox
- Safari
- Edge

Requires a browser with Web Audio API support (all modern browsers qualify).

---

## Technical Details

- **Single file** — HTML, CSS, and JavaScript all in one `.html` file
- **Zero dependencies** — No npm, no build tools, no external libraries
- **Web Audio API** — Sounds generated programmatically, no audio files needed
- **Canvas API** — Animated particle background
- **CSS animations** — Ring progress, breathing guide, visualizer bars, notifications
- **LocalStorage** — Not used; all state is in-memory per session

---

## Project Structure

```
timer.html
│
├── Styles (CSS)         Dark/light theme, animations, layout
├── Particle System      Canvas-based floating particle background
├── Timer Module         Countdown/countup with ring progress
├── Pomodoro Module      Session tracking and auto-cycle
├── Stopwatch Module     Millisecond precision with lap tracking
├── Alarm Module         Time-based alerts with toggle management
├── World Clock Module   Multi-timezone live display
├── Breathing Module     Guided breath phase animation
├── Sound Engine         Web Audio API tone generation
├── Focus Mode           Fullscreen overlay
└── Stats Module         Session history and usage summary
```

---

## License

This project is open for personal and educational use.
