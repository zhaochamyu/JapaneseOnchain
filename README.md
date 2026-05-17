# 🌸 JapaneseOnChain

> A blockchain-powered Japanese culture project — live at [japaneseonchain.xyz](http://japaneseonchain.xyz)

---

## 🔗 Live Site

**[japaneseonchain.xyz](http://japaneseonchain.xyz)**  
Also available at: [zhaochamyu.github.io/JapaneseOnchain](https://zhaochamyu.github.io/JapaneseOnchain/)

---

## 📖 About

JapaneseOnChain is a web project combining Japanese culture with blockchain technology. Built and deployed using modern web tooling, the project is live on the web and automatically synced to this GitHub repository.

---

## 🗂 Repository Structure

```
JapaneseOnchain/
├── index.html              # Main entry point
├── favicon.svg             # Site icon
├── CNAME                   # Custom domain config (japaneseonchain.xyz)
├── assets/
│   ├── index-*.js          # JavaScript bundle
│   └── index-*.css         # Stylesheet bundle
└── .github/
    └── workflows/
        └── sync.yml        # Auto-sync from Netlify every 6 hours
```

---

## ⚙️ Tech Stack

- **Frontend:** React + Vite
- **Styling:** Tailwind CSS
- **Hosting:** Netlify (primary) + GitHub Pages (mirror)
- **CI/CD:** GitHub Actions — auto-syncs latest build every 6 hours

---

## 🚀 GitHub Actions — Auto Sync

This repo includes an automated workflow (`.github/workflows/sync.yml`) that:

- Runs **every 6 hours** automatically
- Fetches the latest built files from `japaneseonchain.xyz`
- Commits and pushes any changes to this repo
- Can also be triggered **manually** via the Actions tab

To trigger manually:
1. Go to [Actions](../../actions)
2. Select **"Sync from Netlify"**
3. Click **Run workflow**

---

## 🌐 Custom Domain Setup

The site uses `japaneseonchain.xyz` as a custom domain for GitHub Pages.

**Required DNS Records:**

| Type  | Host  | Value                  |
|-------|-------|------------------------|
| A     | @     | 185.199.108.153        |
| A     | @     | 185.199.109.153        |
| A     | @     | 185.199.110.153        |
| A     | @     | 185.199.111.153        |
| CNAME | www   | zhaochamyu.github.io   |

---

## 📬 Contact

- GitHub: [@zhaochamyu](https://github.com/zhaochamyu)
- Website: [japaneseonchain.xyz](http://japaneseonchain.xyz)

---

<p align="center">Made with ❤️ — JapaneseOnChain</p>
