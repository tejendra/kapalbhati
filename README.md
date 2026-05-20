# Kapalbhati

A minimal, single-page web app for guided **kapalbhati** (skull shining breath) practice: short, sharp exhales through the nose with passive inhales between them.

## Features

- **15-minute session** with a 3-second prep countdown
- **Pace control**: 1, 1.5, or 2 exhales per second (metronome ticks on each exhale)
- **Visual cue**: pulsing ring on each tick
- **Audio ticks** via the Web Audio API
- **Screen wake lock** during a session (when the browser supports it)
- **Remembers your pace** in `localStorage`
- Collapsible **instructions** and a short **disclaimer** (not medical advice)

## Usage

1. Choose **exhales per second** (1, 1.5, or 2).
2. Click **Start** (or tap the circle during a session to stop).
3. Follow the ticks: sharp exhale on each tick; let the inhale happen passively.
4. Stop if you feel dizzy, strained, or unwell.

## Run locally

From the project root, start a simple HTTP server with Python 3:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

Use another port if 8000 is taken, e.g. `python3 -m http.server 3000`.

## Disclaimer

This app is for personal breath practice only. It is **not medical advice**. If you are unsure whether breath work is appropriate for you, consult a qualified clinician before use.
