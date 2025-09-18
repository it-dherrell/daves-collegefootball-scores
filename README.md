# College Football Scoreboard

A simple, static **College Football Scoreboard** you can keep open on a monitor or TV during game days. Built with plain HTML/CSS/JS and published for free using **GitHub Pages**.
You can learn how to set this up as a GitHub hosted page along with a custom domain by following this step-by-step process: https://www.daveherrell.com/github-hosting-a-free-static-site-college-football-scoreboard-edition/

This repo contains:
- `index.html` – the scoreboard page  
- `404.html` – a custom not‑found page  
- `staticwebapp.config.json` – simple route handling (keeps 404s friendly)  
- `CNAME` – added automatically when you set a custom domain in GitHub Pages

> Live demo: `https://davesfootballscores.site/`

---

## Features

- **Live scores** pulled from the (unofficial) ESPN endpoints  
- **Zero backend** — just static files  
- **Free hosting** on GitHub Pages  
- **Custom domain + HTTPS** supported out of the box

> ⚠️ Note: ESPN’s public endpoints are unofficial and may change without notice.

---

## Quick Start (Deploy in 2–3 minutes)

### Option A — Use this repo directly
1. **Fork** this repository to your GitHub account.
2. Go to **Settings → Pages** → set **Branch** to `main` and **Folder** to `/ (root)`, then **Save**.
3. GitHub will publish your site at:  
   `https://<your-username>.github.io/<your-repo>/`
4. (Optional) Add a **Custom Domain** in **Settings → Pages**. GitHub will create/maintain the `CNAME` file for you.

### Option B — Start fresh
1. Create a new public repo (e.g., `daves-collegefootball-scores`).
2. Add `index.html`, `404.html`, and (optionally) `staticwebapp.config.json`.
3. Follow this setup procedure: https://www.daveherrell.com/github-hosting-a-free-static-site-college-football-scoreboard-edition/

> FYI: Pages only publishes from **public** repos on free plans. If you want a **private** repo with Pages, use **GitHub Pro**. (As of writing, Pro is ~$48/year.)

---

## Local Preview (Optional)

You can open `index.html` directly, or run a tiny static server:

**Python 3**
```bash
python -m http.server 8080
# then visit http://localhost:8080
```

**Node**
```bash
npx serve .
# then visit the URL it prints
```
---

## Contributing

Issues and PRs are welcome!  
- Open an **Issue** for bugs or feature suggestions.  
- For PRs, please keep changes small and clearly described.