# Youssef Portfolio - GitHub Pages Setup

## Prerequisites
1. Install Git: https://git-scm.com/downloads
2. Create a GitHub account if you don't have one: https://github.com/signup

## Setup Steps

### 1. Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `portfolio` (or any name you prefer)
3. Make it **Public**
4. **Don't** initialize with README (we already have files)
5. Click "Create repository"

### 2. Push Your Files to GitHub
After installing Git, open a terminal in this folder and run:

```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username and `portfolio` with your repo name.

### 3. Enable GitHub Pages
1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under "Source": select **Deploy from a branch**
4. Branch: select **main**, folder: **/ (root)**
5. Click **Save**

### 4. Access Your Portfolio
- Your site will be live at: `https://YOUR_USERNAME.github.io/portfolio/`
- It may take 1-2 minutes to deploy the first time
- Share this URL with anyone!

## Updating Your Portfolio
Whenever you make changes:
```bash
git add .
git commit -m "Update portfolio"
git push
```

Changes go live automatically within 1-2 minutes.

## Files in This Project
- `index.html` - Your portfolio page
- `portrait.jpg` - Your photo (if used)
- `CV_FINAL.pdf` - Your CV (optional, currently using Drive link)
- `README.md` - This file
