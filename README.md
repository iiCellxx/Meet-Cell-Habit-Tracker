<div align="center">

# 🧠 Meet Cell – The Habit Tracker Intelligent Web App

**A beautiful, AI-powered habit tracking app — built with pure HTML, CSS & JavaScript. No backend. No sign-up. Just results.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20App-7c6eff?style=for-the-badge&logo=github)](https://your-username.github.io/meet-cell)
[![License: MIT](https://img.shields.io/badge/License-MIT-6effd4?style=for-the-badge)](LICENSE)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love%20%26%20Coffee-ff6eb4?style=for-the-badge)](#)
[![HTML CSS JS](https://img.shields.io/badge/Stack-HTML%20%7C%20CSS%20%7C%20JS-ffd166?style=for-the-badge)](#)

![Meet Cell Banner](https://via.placeholder.com/1200x400/0a0a0f/7c6eff?text=Meet+Cell+%E2%80%93+Habit+Tracker)

</div>

---

## ✨ What is Meet Cell?

**Meet Cell** is a fully static, intelligent habit-tracking web app that helps you build consistency, track progress, and stay motivated — all without an account or internet connection (except for the AI Coach feature).

Your data lives entirely in your browser's **LocalStorage**, meaning your habits, streaks, and XP are always private and always available — even offline.

> *"Every habit you build is a vote for the person you want to become."* — James Clear

---

## 🚀 Features

### 📋 Habit Checklist
- Add, edit, and delete daily habits with custom emoji icons
- Mark habits as complete with a satisfying one-tap check
- Filter habits by **All / Pending / Done**
- 12 habit categories: Wellness, Exercise, Learning, Mindfulness, and more

### 🔥 Streak Counter
- Tracks consecutive days each habit is completed
- Streaks automatically reset if a day is missed
- Best-streak memory preserved across all time
- Streak bonus XP — the longer your streak, the more XP you earn per completion

### 📊 Progress Charts & Stats
- **Animated progress ring** showing today's completion percentage
- **7-day bar chart** (Chart.js) showing your weekly completion history
- **Week dot indicators** for a quick glance at the last 7 days
- 5 live stat cards: Total Habits, Done Today, Best Streak, Total XP, Badges

### 📅 Activity Heatmap
- GitHub-style **16-week heatmap** showing overall daily habit intensity
- **Per-habit mini heatmaps** with 8-week history and all-time completion rate
- 5 heat intensity levels, color-coded by completion percentage

### ⚡ XP & Level System
- Earn XP for every action: adding habits (+10 XP), completing them (+20 XP + streak bonus), and unlocking badges (+50 XP)
- **10 levels** from Beginner → Grandmaster with an animated XP progress bar
- Recent XP events log so you can see exactly how you earned your points

### 🏅 16 Unlockable Badges

| Badge | Name | How to Earn |
|-------|------|-------------|
| 🌱 | First Step | Add your very first habit |
| ✅ | Checked In | Complete a habit for the first time |
| 🔥 | On Fire | Reach a 3-day streak |
| ⚡ | Week Warrior | Reach a 7-day streak |
| 💎 | Diamond Habit | Reach a 30-day streak |
| 🌟 | Perfect Day | Complete ALL habits in one day |
| 🏆 | Hat Trick | 3 perfect days |
| 👑 | Royalty | 7 perfect days |
| 🎯 | Collector | Track 5+ habits at once |
| ⚡ | Power User | Earn 500 total XP |
| 🚀 | Rocket | Earn 1000 total XP |
| 💯 | Centurion | Complete 50 habits total |
| 🎖️ | Veteran | Complete 100 habits total |
| 🌈 | Diverse | Cover 4+ habit categories |
| 🌅 | Early Bird | Set a reminder before 7 AM |
| 🤖 | AI Friend | Chat with Cell AI |

### 🤖 Cell AI — Intelligent Habit Coach
- Powered by the **Anthropic Claude API**
- **Context-aware**: Cell AI reads your actual habit data, streaks, XP, and badges before responding
- Get personalized habit analysis, streak-building tips, new habit suggestions, and motivation
- Conversational memory within each session
- Quick-tap suggestion prompts to get started instantly

### 🔔 Smart Reminders
- Set a custom reminder time for any habit
- Browser push notifications fire at the exact time you set
- Supports next-day scheduling if the time has already passed

### 🌙 Dark / Light Mode
- Full dark and light themes with one-click toggle
- Theme preference saved automatically across sessions
- All charts, heatmaps, and UI elements adapt seamlessly

### 💬 Motivation Quote Generator
- A curated quote fires automatically every time you complete a habit
- "New Quote" button to refresh on demand
- 12 quotes from James Clear, Aristotle, Warren Buffett, Jim Rohn, and others

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure and semantic markup |
| **CSS3** | Custom theming with CSS variables, animations, responsive grid |
| **Vanilla JavaScript** | All app logic, state management, LocalStorage I/O |
| **Chart.js** | Weekly completion bar chart |
| **Anthropic Claude API** | AI Coach (Cell AI) — claude-sonnet-4 |
| **LocalStorage** | Persistent data storage — no backend needed |
| **Web Notifications API** | Browser-native habit reminders |

---

## 📁 Project Structure

```
meet-cell/
│
└── index.html        # The entire app — single self-contained file
```

That's it. One file. Deploy anywhere.

---

## 🚀 Getting Started

### Option 1 — Open Locally
```bash
# Clone the repo
git clone https://github.com/your-username/meet-cell.git

# Open in your browser
open meet-cell/index.html
```
No `npm install`. No build step. No server required.

### Option 2 — Deploy to GitHub Pages
1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your app will be live at `https://your-username.github.io/meet-cell`

### Option 3 — Deploy to Netlify / Vercel
Simply drag and drop `index.html` into [Netlify Drop](https://app.netlify.com/drop) — done.

---

## 🤖 Setting Up the AI Coach

The AI Coach (Cell AI) uses the Anthropic API. To enable it:

1. Get a free API key from [console.anthropic.com](https://console.anthropic.com)
2. The app calls the API directly from the browser — no server needed
3. Note: For production use, consider proxying through a backend to protect your API key

> The app works fully without an API key — the AI Coach tab will simply show a connection error, while all other features remain fully functional.

---

## 📱 Screenshots

> *(Add your own screenshots here)*

| Dashboard | Heatmap | Badges |
|-----------|---------|--------|
| ![Dashboard](https://via.placeholder.com/380x220/13131a/7c6eff?text=Dashboard) | ![Heatmap](https://via.placeholder.com/380x220/13131a/6effd4?text=Heatmap) | ![Badges](https://via.placeholder.com/380x220/13131a/ffd166?text=Badges) |

---

## 🗺️ Roadmap

- [ ] Export habit data as CSV or PDF
- [ ] Shareable streak cards for social media
- [ ] Habit grouping / morning routine stacks
- [ ] Offline PWA support with service workers
- [ ] Import / export JSON backup
- [ ] Habit completion rate analytics
- [ ] Best day-of-week insights

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🙏 Acknowledgments

- Habit framework inspired by *Atomic Habits* by James Clear
- AI powered by [Anthropic Claude](https://anthropic.com)
- Charts by [Chart.js](https://chartjs.org)
- Fonts: [Syne](https://fonts.google.com/specimen/Syne) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts

---

<div align="center">

**Built with 🧠 by [Your Name](https://github.com/your-username)**

*If this project helped you, please consider giving it a ⭐ — it means a lot!*

</div>
