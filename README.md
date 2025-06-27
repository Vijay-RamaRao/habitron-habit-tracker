# 🌟 Habitron - Habit Tracker Dashboard

> **A no-nonsense, one-file wonder that turns your habit tracking into an aesthetic obsession — Habitron gets it done, beautifully.**

## ✨ Features

- 🎨 **Neumorphic Design**: Soft UI with modern gradient touches and a clean layout.
- 🧠 **Self-Contained**: No build tools, no CDN, no external libraries. One single `.html` file does it all.
- 🗓️ **Calendar Heatmap**: Visualize your daily habit consistency with animated color gradients.
- 📈 **Radial Progress**: Dynamic progress rings with tooltip insights.
- 📊 **Performance Filtering**: Filter habits by completion rate, status, or visibility.
- ✅ **Drag & Drop**: Reorder habits easily with intuitive drag-and-drop.
- 📱 **Responsive Design**: Works seamlessly on desktops and mobile with adaptive views.
- 🔐 **Local Persistence**: Your habits and logs are stored locally using `localStorage`.

## 🚀 Quick Start

No installations. No dependencies.

Just **clone or download** and open the `index.html` file in your browser.

```bash
git clone https://github.com/Vijay-RamaRao/habitron-habit-tracker.git
cd habitron-habit-tracker
open index.html
```

## 🔧 Tech Stack

- HTML5
- CSS3 (Custom Properties + Neumorphism)
- JavaScript (Vanilla)

No frameworks. No dependencies. One HTML file. That’s it.

## 🛠️ Customization

Want to tweak the theme or logic?

- All styles are defined in the `<style>` tag using CSS variables (`--primary-accent-color`, `--card-bg-color`, etc).
- JavaScript logic is inline and modularized inside a single `App` object for easy hacking.
- Calendar, filters, and modals are all DOM-generated for maximum control.

## 💾 Data Persistence

All data is saved automatically in your browser using `localStorage`. This means:
- Your habits persist between sessions.
- No backend or database is required.

> **Note:** Clearing browser data will erase your habits.

**Built with ❤️ and zero dependencies.**  
_Track your habits the elegant way._
