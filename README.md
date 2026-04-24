# 💶 Erasmus Budget Tracker

A mobile-first, serverless web app to track spending during an Erasmus exchange. It calculates a **Safe Margin** — how much you can still spend freely before your end date — using a predictive algorithm based on your real daily food average, projected forward with a configurable safety margin.

Live at: **[joshuari03.github.io](https://joshuari03.github.io)**

---

## Features

- Predictive spending algorithm with safety margin projection
- Three expense categories: Food/Variable, Fixed, Extra/Leisure
- Cloud sync via **Firebase Firestore** — data persists across devices
- Session key system — restore your tracker on any device
- Real-time updates, budget breakdown bar, and time elapsed timeline
- Zero backend — fully static, hosted on GitHub Pages

## Tech Stack

Vanilla HTML/CSS/JS · Firebase Firestore · GitHub Pages

## Setup

1. Create a Firebase project and enable Firestore
2. Paste your `firebaseConfig` values into the `FIREBASE_CONFIG` block in `index.html`
3. Restrict your API key to your GitHub Pages domain in [Google Cloud Console](https://console.cloud.google.com/apis/credentials)
4. Push to `main` and enable GitHub Pages in repository settings

## License

MIT
