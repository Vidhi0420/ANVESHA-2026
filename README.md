# Technical Affairs Development Task
# Anvesha 2026 — IIITDM Kancheepuram Tech Fest

Single-page landing page for Anvesha 2026, the annual intra-college technical festival of IIITDM Kancheepuram. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no build step.

## Features

- Fullscreen countdown splash screen on load (auto-dismisses after 5 seconds)
- Live countdown timer ticking down to fest date (July 25, 2026)
- 3-day event schedule with tabbed timeline
- Registration form with real-time input validation
  - Email: must match IIITDM format (ab12c3456@iiitdm.ac.in)
  - Roll number: must match college format (CS22B1011)
  - Phone: 10-digit Indian mobile number
  - Form submission logged to browser console
- Fully mobile responsive (hamburger nav, stacked layout)

## Tech Stack

- HTML5
- CSS3 (Flexbox, Grid, CSS Variables, animations)
- Vanilla JavaScript (DOM manipulation, Date API, IntersectionObserver)
- Google Fonts (Rajdhani, Share Tech Mono, Inter)

## How to Run

Clone the repo and open `index.html` in any browser. No installation or build step needed.

```bash
git clone https://github.com/Vidhi0420/ANVESHA-2026.git
cd ANVESHA-2026
open index.html
```

## Live Demo

[View Live Site](https://vidhi0420.github.io/ANVESHA-2026/)

## Project Structure

```
ANVESHA-2026/
├── index.html 
└── README.md
```