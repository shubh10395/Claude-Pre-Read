# How to Use Claude — Interactive Pre-Read

An interactive explainer in the style of [Explorable Explanations](https://explorabl.es/), built with vanilla HTML/CSS/JS. No dependencies, no build step.

## Pages

| File | Content |
|---|---|
| `index.html` | Series landing page |
| `part1.html` | Part 01 — What is Claude? (3 interactive demos) |
| `part2.html` | Part 02 — Prompting Essentials (3 interactive demos) |

## Host on GitHub Pages (5 steps)

1. Create a new GitHub repo (e.g. `claude-preread`)
2. Push the three HTML files to the repo root
3. Go to **Settings → Pages**
4. Under *Source*, select **Deploy from a branch → main → / (root)**
5. Save — your site will be live at `https://<your-username>.github.io/claude-preread/`

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/<your-username>/claude-preread.git
git push -u origin main
```

## Run locally

Just open `index.html` in any browser — no server needed.
