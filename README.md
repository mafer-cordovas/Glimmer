# Glimmer 

A minimalist Progressive Web App (PWA) designed to help users capture "glimmers"—micro-moments of safety, joy, and calm—to combat stress and negative bias.

**[✨ View Live App](https://mafer-cordovas.github.io/Glimmer/)**

![Version](https://img.shields.io/badge/version-7.0-teal)
![Status](https://img.shields.io/badge/status-live-success)
![License](https://img.shields.io/badge/license-MIT-blue)

## 📖 About The Project

Glimmer is built on the principle of neuroplasticity: by actively looking for small positive moments, we can retrain the brain to scan for safety rather than danger. The application is designed to be frictionless, private, and calming.

It operates entirely client-side, meaning no user data is ever sent to a server. Everything is stored locally on the user's device.

## ✨ Key Features

* **Zero-Friction Logging:** One-tap capture mechanism for rapid logging.
* **Gamification:** Built-in "Streak" logic to encourage daily usage.
* **Bilingual Support:** Instant toggling between English (EN) and Spanish (ES).
* **Privacy First:** 100% local storage. Data never leaves the phone.
* **PWA Ready:** Installable on iOS/Android home screens with native app-like behavior.
* **Sanctuary UI:** Glassmorphism design system using calming aqua/teal gradients.
* **Safety Controls:** Confirmation modals prevents accidental data loss during resets.

## 🛠 Technical Overview

To maintain simplicity and zero hosting costs, the project is architected as a **Single File Component**.

* **Stack:** HTML5, CSS3, Vanilla JavaScript (ES6+).
* **Hosting:** GitHub Pages.
* **Dependencies:** None (0kb bloat).

### Data Structure & Persistence
State is managed via `window.localStorage`. If extending this project, maintain the following key-value schema:

| Key | Type | Description |
| :--- | :--- | :--- |
| `glimmerCount` | `Integer` | Total number of items logged. |
| `glimmerStreak` | `Integer` | Current count of consecutive days active. |
| `lastGlimmerDate` | `String` | ISO Date (`YYYY-MM-DD`) of the last log. |
| `glimmerLang` | `String` | User preference: `'en'` or `'es'`. |
| `glimmerHistory` | `JSON` | Array of objects (see schema below). |

**History Object Schema:**
```json
[
  {
    "text": "Saw a double rainbow",
    "time": "14:30"
  },
  {
    "text": "Drank good coffee",
    "time": "09:15"
  }
]
