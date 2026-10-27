# ✦ DailyPath Tracker

> **A private, offline-first personal dashboard for holistic daily discipline, physical fitness, spiritual sadhana, career momentum, financial prudence, and honest moral accountability.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-4f46e5?style=for-the-badge&logo=github)](https://bhanu2006-24.github.io/dailytracker/)
[![Zero Backend](https://img.shields.io/badge/Zero%20Backend-100%25%20Client--Side-10b981?style=for-the-badge)](https://bhanu2006-24.github.io/dailytracker/)
[![100% Private](https://img.shields.io/badge/Privacy-100%25%20Local%20Storage-0ea5e9?style=for-the-badge)](https://bhanu2006-24.github.io/dailytracker/)
[![License: MIT](https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge)](LICENSE)

---

## 🌐 Live Application

Access the application anytime directly in your web browser:
👉 **[https://bhanu2006-24.github.io/dailytracker/](https://bhanu2006-24.github.io/dailytracker/)**

*Works completely offline once loaded — no login, no database, no subscriptions, zero data leaves your device.*

---

## 📖 Table of Contents

- [Overview & Philosophy](#-overview--philosophy)
- [Key Features](#-key-features)
  - [1. Daily Log & Habit Architecture](#1-daily-log--habit-architecture)
  - [2. History & Past Entries](#2-history--past-entries)
  - [3. Visual Analytics & Charts](#3-visual-analytics--charts)
  - [4. Settings, Backups & Portability](#4-settings-backups--portability)
- [Architecture & Tech Stack](#-architecture--tech-stack)
- [Keyboard Shortcuts](#-keyboard-shortcuts)
- [Data Privacy & Storage](#-data-privacy--storage)
- [Getting Started Locally](#-getting-started-locally)
- [Export & Import Guidelines](#-export--import-guidelines)
- [License](#-license)

---

## 🧘 Overview & Philosophy

**DailyPath Tracker** was built on a foundational truth: *What gets measured gets mastered, but real self-mastery requires a holistic lens.*

Most productivity tools isolate tasks or calories while ignoring spiritual depth, character flaws, or evening reflection. DailyPath combines all critical pillars of human life into a single unified cockpit:

```
                      ┌────────────────────────────────────────┐
                      │          DAILYPATH TRACKER             │
                      └──────────────────┬─────────────────────┘
                                         │
        ┌───────────────┬────────────────┼────────────────┬───────────────┐
        ▼               ▼                ▼                ▼               ▼
   [Physical]     [Spiritual]        [Career]         [Moral]        [Mental]
   • Sleep         • Naam Jap Mala   • Jobs Applied   • 14 Sins       • Wins
   • Water         • Routine         • Deep Work      • Distractions  • Mistakes
   • Diet          • Kirtan          • YouTube        • Fast Screen   • Lessons
   • Reps/Cardio   • Scriptures      • Teaching       • Clean Badge   • Tomorrow Goal
```

---

## ✨ Key Features

### 1. Daily Log & Habit Architecture

The **Daily Log** provides an intuitive, collapsible dashboard where you log your daily routine in seconds:

- **⚡ Mood & Dominant Energy**:
  - One-tap selector for Peak Energy (🔥), Peaceful (😊), Deep Focus (⚡), Tired (🥱), or Low/Anxious (🌧️).
- **🌙 Sleep & Rest**:
  - Bedtime and wake-up time tracking.
  - **Auto-Calculate Sleep Hours**: Computes the exact sleep duration across midnight with one click.
  - Afternoon nap indicator and sleep stepper adjustments (`±0.5h`).
- **🍽️ Food, Diet & Hydration**:
  - **Hydration Tracker**: Interactive glass counter (`- 1 Glass`, `+ 1 Glass (250ml)`, `+ 1 Liter`) with real-time liter conversions.
  - Roti count stepper, dinner type selector (Normal, Milk only, Fruit, Fasting).
  - Checkboxes for sugar, non-water drinks, and junk food consumption.
- **💪 Physical Fitness & Conditioning**:
  - Quick increment steppers (`+10`, `+25`, `+50`) for **Dandwat** and **Uthak Bethak** for fast mobile entry during workouts.
  - Laps counter, walking/cardio minutes, and freeform workout notes.
- **📿 Spirituality & Sadhana**:
  - Dedicated **Naam Jap Mala counter** with one-tap `+1 Mala (108)` and `+5 Malas` steppers.
  - Checkpoints for spiritual routine, Kirtan, Bhakt Namawali, Chaturasi Ji, Charnamrit, Braj Raj, Aarti, and Sacred Readings.
- **💼 Career, Content & Teaching**:
  - Job applications count and target company details.
  - Deep work / study hours counter.
  - YouTube content publishing log (videos count, duration, titles, URLs).
  - Tuition students taught and pedagogical notes.
- **💰 Finances & Real-Time Net Balance**:
  - Track daily money earned and spent in ₹ (INR).
  - **Live Net Balance Badge**: Instant colored indicator displaying daily surplus (`+₹`) or deficit (`-₹`).
  - Expense category breakdown (Essentials, Food, Tuition, Transit, Entertainment, Investment).
- **⚠️ Moral Accountability & Sins Checklist**:
  - Radical honesty checkboxes for 14 universal character traps: Greed, Desire for money, Anger, Lust, Lustful thoughts, Selfishness, Jealousy, Moha (Attachment), Pride, Oversleeping, Disrespect, Lying, Laziness, and Gossiping.
  - Automatic **Clean Day 🕊️** badge when zero negative triggers occur.
- **📱 Distractions & Wellness**:
  - Accountability for wasted screen time (Anime, Instagram/Reels, online rabbit holes).
  - Illness checkbox and physical symptom log.
- **🧠 Evening Reflection & Wisdom**:
  - Four cornerstone journaling prompts:
    1. *What did I do well today?* (Celebrate victories & gratitude)
    2. *What did I do wrong today?* (Acknowledge mistakes & triggers)
    3. *What did I learn today?* (Insights, quotes & spiritual takeaways)
    4. *What must I improve tomorrow?* (Non-negotiable morning target)
- **🎉 Confetti Celebration & Sign Off**:
  - Clicking **Complete Day & Sign Off** locks the record to maintain discipline integrity and triggers a celebratory canvas confetti animation.

---

### 2. History & Past Entries

- **Search & Filter**: Search full-text reflections, company applications, YouTube titles, and expense notes.
- **Filter Views**: Switch instantly between *All Days*, *Completed Only*, *Drafts Only*, or *Clean Days Only*.
- **Detailed Inspection Modal**: View all data points across physical, spiritual, career, habits, and reflections in a structured view.
- **One-Click Edit**: Jump straight from any past record directly into the Daily Log editor for that date.
- **Delete Protection**: Easily remove unwanted entries with double-confirmation dialogs.

---

### 3. Visual Analytics & Charts

Powered by [Chart.js](https://www.chartjs.org/):

- **Key Performance Indicators**:
  - **Current Active Streak** (calculated with timezone-safe calendar arithmetic).
  - **Best Longest Streak**.
  - **Clean Days Counter & Percentage** of total recorded days.
  - **Total Physical Reps** (Lifetime Dandwat + Uthak Bethak sum).
  - **Net Financial Balance** (Total lifetime earned minus total spent).
- **Timeframe Selector**: Toggle visual charts between **7 Days**, **14 Days**, **30 Days**, or **All Time**.
- **Interactive Charts**:
  - 📈 **Fitness Progression**: Dual smooth curves for Dandwat and Uthak Bethak volume.
  - 📊 **Sleep Consistency**: Bar chart of hours slept with reference baseline.
  - 💹 **Finances Trend**: Income vs. Expenses comparison.
  - 📉 **Habits Frequency Breakdown**: Horizontal bar chart identifying your most frequent triggers so you can focus self-mastery where it matters most.

---

### 4. Settings, Backups & Portability

- **Export JSON**: Download a complete, uncompressed backup of your entire tracking history with a single click.
- **Export CSV (Spreadsheet)**: Export a clean `.csv` file ready to open in Microsoft Excel, Apple Numbers, or Google Sheets.
- **Import / Restore JSON**: Restore backups or merge data from other devices with validation.
- **Sample Demo Generator**: One-click generator that creates 7 days of realistic sample data to immediately explore charts and dashboard features.
- **Storage Status**: Live indicator showing total records and exact local storage footprint.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|:---|:---|
| <kbd>Ctrl</kbd> / <kbd>Cmd</kbd> + <kbd>S</kbd> | Complete / Sign Off Current Day |
| <kbd>Ctrl</kbd> / <kbd>Cmd</kbd> + <kbd>←</kbd> | Jump to Previous Day |
| <kbd>Ctrl</kbd> / <kbd>Cmd</kbd> + <kbd>→</kbd> | Jump to Next Day |
| <kbd>Ctrl</kbd> / <kbd>Cmd</kbd> + <kbd>T</kbd> | Jump to Today |
| <kbd>?</kbd> | Toggle Keyboard Shortcuts Modal |
| <kbd>Esc</kbd> | Close any open modal / dialog |

---

## 🔒 Data Privacy & Storage

DailyPath Tracker runs **100% on your machine**:

- **No Remote Servers**: No database, no telemetry, no tracking cookies, no Google Analytics.
- **Encrypted LocalStorage**: Your data is saved in your browser's persistent `localStorage` under the key `dailyTrackerData_v2`.
- **Offline Capable**: The app works without an active internet connection once loaded.
- **Data Portability**: You can export your JSON and CSV records at any time.

---

## 🚀 Getting Started Locally

No complex dependencies, build tools, or package managers are required!

### Option 1: Direct File Open
1. Clone or download this repository:
   ```bash
   git clone https://github.com/bhanu2006-24/dailytracker.git
   cd dailytracker
   ```
2. Double-click `index.html` or open it with your favorite browser:
   ```bash
   open index.html   # On macOS
   xdg-open index.html # On Linux
   start index.html  # On Windows
   ```

### Option 2: Local HTTP Server (Python / Node)
```bash
# Using Python 3
python3 -m http.server 8080

# Or using npx serve
npx -y serve .
```
Then visit `http://localhost:8080` in your browser.

---

## 📁 Project Structure

```
dailytracker/
├── index.html        # Complete standalone application (HTML5, Tailwind CSS, Chart.js, JS)
├── .gitignore        # Comprehensive gitignore for OS, IDE, and personal backup files
└── README.md         # Documentation & user manual
```

---

## 🛠️ Tech Stack

- **HTML5 & Vanilla JavaScript**: Zero runtime frameworks; blazing fast, lightweight, and future-proof.
- **Tailwind CSS**: Modern utility styling, responsive grid layouts, and automatic dark/light theme switching.
- **Chart.js**: Smooth, responsive HTML5 Canvas charts with dynamic dark mode color adaptivity.
- **Canvas Confetti**: Delightful celebratory feedback upon completing and signing off days.
- **Google Fonts (Inter)**: Clean, contemporary typography optimized for readability.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — feel free to use, modify, and distribute it for personal or educational growth.

---

*Made with dedication for discipline, self-improvement, and conscious living.*
