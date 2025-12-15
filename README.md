# ✨ Glimmer (Beta)

**Capture the tiny moments that spark joy.**

Welcome to **Glimmer**, a mindful web application designed to help you recognize and collect "glimmers"—those micro-moments of safety, connection, and joy that happen every day.

In a world often wired to notice danger, Glimmer helps you rewire your nervous system to notice the light.

---

## 🌿 The Philosophy

Our brains are naturally biased toward survival, scanning for threats. A "glimmer" is the opposite: a sunbeam, a good cup of coffee, a smile from a stranger, or the smell of rain.

This app isn't about toxic positivity; it's about **grounding**. By taking 5 seconds to log a glimmer, you acknowledge it, celebrate it, and build a history of happiness that you can look back on.

---

## 📱 Features

This **Beta version** is packed with features designed for simplicity and delight:

* **Privacy First:** Zero data collection. Everything is stored locally on your device.
* **Bilingual Support:** Toggle seamlessly between English and Spanish.
* **Gamification:** Track your **Streaks** 🔥 and level up from "Novice" to "Glimmer Master."
* **Dark Mode:** A soothing interface for late-night reflection 🌗.
* **Smart Tags:** Categorize moments (Nature, People, Cozy, Wins, Food).
* **Export Data:** Download your history as a CSV file to keep forever.
* **App-Like Feel:** Installable on mobile home screens with native-like scrolling and behavior.

---

## 🔍 Deep Dive: Under the Hood

Glimmer was built with a philosophy of **"Digital Minimalism."** It is lightweight, fast, and requires no installation, no servers, and no accounts.

### 1. The Tech Stack
* **Single-File Architecture:** The entire application lives in one file (`index.html`). There is no complex build process, no backend server, and no dependencies to manage.
* **Vanilla JavaScript:** We avoided heavy frameworks like React or Vue. This uses pure, efficient JavaScript logic to ensure the app loads instantly even on older devices.
* **CSS Glassmorphism:** The UI uses modern CSS variables (`var(--glass-bg)`) and backdrop filters to create a translucent, calming "frosted glass" aesthetic that adapts dynamically to Light and Dark modes.

### 2. Data Persistence
We use the browser's **LocalStorage API**.
* **Why?** Trust. By keeping data in LocalStorage, your thoughts remain strictly private. Your entries never leave your phone or computer.
* **Persistence:** Even if you refresh the page or close the browser, your history, streak, and preferences (Theme/Language) are saved automatically.

### 3. Mobile Optimization
The code utilizes specific `<meta>` tags (viewport-fit, apple-mobile-web-app-capable) to handle "safe areas" (like the notch on iPhones) and prevent overscrolling, giving the web app a native, polished feel.

---

## 🚀 How to Run

1.  **Download:** Save the `index.html` file to your computer or phone.
2.  **Open:** Double-click the file to open it in any web browser (Chrome, Safari, etc.).
3.  **Install (Mobile):**
    * **iOS:** Tap the "Share" button in Safari -> "Add to Home Screen."
    * **Android:** Tap the menu (three dots) in Chrome -> "Add to Home Screen."

---

## 🤝 Collaborate with Me

I believe that tools for mental well-being should be accessible, private, and community-driven. This is currently a **Beta** release, and I would love your help to make it better.

**Ideas we could explore:**
* Adding a daily gentle notification.
* More color themes / mood palettes.
* A "random memory" recall feature to surprise you with past joy.

If you are a developer, a designer, or just someone who uses the app and has an idea, please reach out. Let's build a brighter internet together.

---

## 💌 Say Hello

I’d love to hear your story. Did you find a glimmer today? Did the app crash? Do you just want to say hi?

* **Email:** [hi@mafer.rocks](mailto:hi@mafer.rocks)
* **Instagram:** [@mafer_cordovas](https://instagram.com/mafer_cordovas)

*Built with intention and ✨.*
