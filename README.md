# Keeping in Touch

A personal relationship-maintenance tool that tracks how long it's been since you last contacted someone and reminds you when it's time to reach out.

## Features
- Set a reminder cadence per contact: 1 week, 2 weeks, monthly, bimonthly, annually, custom, or none
- One-tap logging that resets the timer when you reach out
- Import real contacts from iMessage, Facebook, Messenger, Instagram, WhatsApp, Telegram, LinkedIn, and Discord exports (vCard, CSV, or JSON)
- A Tinder-style swipe feed to quickly triage imported contacts — assign platform + cadence or skip
- In-app step-by-step export instructions for each platform
- Mobile-first design, works great added to your phone's home screen

## Running it
Just open `index.html` in a browser — no build step, no dependencies to install. Data saves to your browser's local storage, so it persists between visits on the same device/browser.

## Hosting it live (GitHub Pages)
1. Push this repo to GitHub.
2. Go to Settings → Pages.
3. Under "Build and deployment," set Source to "Deploy from a branch," branch `main`, folder `/ (root)`.
4. Your app will be live at `https://<your-username>.github.io/<repo-name>/`.
5. Open that URL on your phone and use "Add to Home Screen" for an app-like experience.

## Note on data
All contact data is stored locally in your browser (`localStorage`). Nothing is sent to a server — it's entirely private to your device. Clearing your browser data will clear your contact list, so don't rely on this as your only backup for anything critical.

## Tech
Single-file HTML/CSS/vanilla JavaScript. No frameworks, no build tools, no dependencies beyond a Google Fonts import.
