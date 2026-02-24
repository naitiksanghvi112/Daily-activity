# 📊 Daily Activity

> Keeping the GitHub contribution graph green, one commit at a time.

[![Twice Daily Commit](https://github.com/visheshsanghvi112/Daily-activity/actions/workflows/daily.yml/badge.svg)](https://github.com/visheshsanghvi112/Daily-activity/actions/workflows/daily.yml)

---

## 📈 Live Stats

| Metric | Value |
|--------|-------|
| 🔥 Current Streak | **1 days** |
| 🏆 Longest Streak | **1 days** |
| 📝 Total Commits | **2** |
| 🕐 Last Update | 2026-02-24 03:39 PM IST |
| 📅 Started On | 2026-02-24 |

> 💬 *"Any fool can write code that a computer can understand. Good programmers write code that humans can understand. – Martin Fowler"*

---

## 🤖 How It Works

A scheduled GitHub Actions workflow runs **twice daily** and:

1. ⏳ Waits a random 0–5 min delay (so commits look natural)
2. 📜 Picks a random motivational quote from a curated list
3. 🤖 Optionally fetches an AI-generated thought via Gemini API
4. 📝 Appends the content to `activity.log`
5. 📊 Updates streak & stats tracking
6. 📋 Refreshes this README with live stats
7. 🚀 Commits with a randomized message & pushes

| ⏰ Schedule     | 🇮🇳 IST     | 🌐 UTC     |
|----------------|------------|------------|
| Morning commit | 9:00 AM    | 3:30 AM    |
| Evening commit | 6:50 PM    | 1:20 PM    |

## 📂 Project Structure

```
Daily-activity/
├── .github/workflows/
│   └── daily.yml        # The magic ✨
├── data/
│   ├── quotes.txt       # 50 curated motivational quotes
│   ├── streak.json      # Streak & stats tracker
│   └── today.json       # Today's snapshot
├── activity.log         # Auto-updated timestamp + quote log
├── LICENSE              # MIT License
└── README.md            # This file (auto-updated!)
```

## 🚀 Run It Manually

1. Head to the [**Actions**](https://github.com/visheshsanghvi112/Daily-activity/actions) tab
2. Select **Twice Daily Commit**
3. Click **Run workflow** → **Run**

## 📜 License

Licensed under the [MIT License](LICENSE).

---

<p align="center">
  Made with 💚 by <a href="https://visheshsanghvi.me"><b>Vishesh Sanghvi</b></a>
</p>
