# Ankitha R — Portfolio Website

Personal portfolio · Single HTML file · Zero dependencies · GitHub Pages ready.

Live at: https://<your-username>.github.io/<repo-name>/

---

## Deploy to GitHub Pages in 5 minutes

### Step 1 — Create a GitHub Repo
1. Go to github.com → Click "New"
2. Name it `portfolio` (or `<your-username>.github.io` for a root URL)
3. Set to Public → Click "Create repository"

### Step 2 — Upload Files

Option A — GitHub Web UI (easiest):
1. Open your repo → click "Add file → Upload files"
2. Drag and drop index.html and README.md
3. Commit message: "Add portfolio" → Click "Commit changes"

Option B — Git CLI:
```
cd /path/to/folder/with/index.html
git init
git add .
git commit -m "Add portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Repo → Settings → Pages (left sidebar)
2. Source → "Deploy from a branch"
3. Branch: main · Folder: / (root) → Save
4. Wait ~60 seconds → visit https://<username>.github.io/<repo>/

---

## Things to update before publishing

Open index.html in VS Code and update:
- GitHub link: find href="https://github.com/" and add your username
- Any other personal details

---

## Structure
```
portfolio/
├── index.html   <- full site (HTML + CSS + JS in one file)
└── README.md    <- this file
```

No build step. No npm. Open index.html directly in any browser to preview.

---

Contact:
Email: ankitharam436@gmail.com
LinkedIn: linkedin.com/in/ankitha-ramesh-a63839268
