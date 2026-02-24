# 📊 Daily Activity

> Keeping the GitHub contribution graph green, one commit at a time.

[![Twice Daily Commit](https://github.com/visheshsanghvi112/Daily-activity/actions/workflows/daily.yml/badge.svg)](https://github.com/visheshsanghvi112/Daily-activity/actions/workflows/daily.yml)

---

## 🤖 What Is This?

An automated GitHub Actions workflow that makes **2 commits per day** — so the contribution graph stays active without lifting a finger.

| ⏰ Schedule     | 🇮🇳 IST     | 🌐 UTC     |
|----------------|------------|------------|
| Morning commit | 9:00 AM    | 3:30 AM    |
| Evening commit | 6:50 PM    | 1:20 PM    |

## � Project Structure

```
Daily-activity/
├── .github/workflows/
│   └── daily.yml        # The magic ✨
├── activity.log         # Auto-updated timestamp log
├── LICENSE              # MIT License
└── README.md
```

## ⚙️ How It Works

1. A **cron-scheduled** GitHub Actions workflow triggers twice daily
2. Appends the current UTC timestamp to `activity.log`
3. Commits the change with a descriptive message
4. Pushes to `main` automatically
5. If there are no changes — it exits gracefully, no failures

## 🚀 Run It Manually

Want to test it or trigger an extra commit?

1. Head to the [**Actions**](https://github.com/visheshsanghvi112/Daily-activity/actions) tab
2. Select **Twice Daily Commit**
3. Click **Run workflow** → **Run**

## �️ Tech

- **GitHub Actions** — CI/CD automation
- **Cron scheduling** — UTC-based triggers
- **Shell scripting** — lightweight, no dependencies

## 📜 License

Licensed under the [MIT License](LICENSE).

---

<p align="center">
  Made with 💚 by <a href="https://visheshsanghvi.me"><b>Vishesh Sanghvi</b></a>
</p>
