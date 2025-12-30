# Notion Page Timer ⏱️

A simple, lightweight timer designed to be embedded directly into **Notion pages** using GitHub Pages.

This timer helps you track how much time you spend working on a specific page or task, without external tools or integrations.

---

## ✨ Features

-  **Start** / **End** buttons
- ⏱️ Live running timer (HH:MM:SS)
- 🕒 **24-hour clock format**
- 📅 Daily session list
- 📊 Automatic **daily total time**
- 💾 Sessions saved in browser (localStorage)
- 🔁 Persists on page refresh
- 🧩 Works perfectly as a **Notion embed**

---

## 🧠 How it works

- The timer runs entirely in the browser
- Sessions are saved using `localStorage`
- No backend, no tracking, no account required
- Each hosted page = one timer

---

## 🚀 Live usage (Notion embed)

1. Host this page using **GitHub Pages**
2. Copy the published URL
3. In Notion, type `/embed`
4. Paste the URL

That’s it 🎉

---

## 🛠️ Installation / Setup

1. Create a GitHub repository
2. Add this project as `index.html`
3. Enable **GitHub Pages**:
   - Branch: `main`
   - Folder: `/root`
4. Open the generated URL to verify it works
5. Embed the URL in Notion

---

## ⚠️ Important notes

- Data is stored **per browser + device**
- Opening the timer on another computer will not show previous sessions
- Clearing browser storage or using incognito mode will reset data

This is intentional for simplicity and privacy.

---

## 🧩 Customization ideas

You can easily extend this project to add:
- Pause / Resume
- CSV export
- Multiple timers (per page ID)
- Weekly / monthly summaries
- Dark mode (for Notion dark theme)
- Sync with external tools (Google Sheets, APIs)

---

## 📄 License

MIT — free to use, modify, and adapt for personal or professional use.

---

## ❤️ Why this exists

Notion does not natively track time spent on a page.
This project fills that gap with a minimal, distraction-free solution that fits naturally into a Notion workflow.
