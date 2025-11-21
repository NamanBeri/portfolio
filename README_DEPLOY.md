# "The Art of Science" Portfolio - Deployment Guide

Your professional portfolio is ready! Follow these steps to deploy it to the web using GitHub Pages.

## 1. Prerequisites
- You need a GitHub account.
- You need Git installed on your computer (which you likely have).

## 2. Create a Repository
1.  Go to [GitHub.com](https://github.com) and sign in.
2.  Click the **+** icon in the top right and select **New repository**.
3.  Name it `portfolio` (or `naman-portfolio`).
4.  Make it **Public**.
5.  Do **not** initialize with README, .gitignore, or license (we have files already).
6.  Click **Create repository**.

## 3. Push Your Code
Open your terminal (Command Prompt or PowerShell) in this folder (`C:\Users\berin\OneDrive\Desktop\MORE\Naman Beri - Portfolio`) and run these commands:

```bash
# Initialize Git (if not already done)
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial commit - The Art of Science Portfolio"

# Link to your GitHub repository (Replace URL with your actual repo URL)
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## 4. Activate GitHub Pages
1.  Go to your repository on GitHub.
2.  Click on **Settings** (top tab).
3.  Scroll down (or look in the left sidebar) for **Pages**.
4.  Under **Source**, select `Deploy from a branch`.
5.  Under **Branch**, select `main` and `/ (root)`.
6.  Click **Save**.

## 5. You're Live!
Wait a minute or two, and GitHub will give you a link (e.g., `https://your-username.github.io/portfolio/`). Your website is now live!

## 6. Updating Content
- **Images:** Replace the placeholders in `assets/images` or update the `src` tags in `index.html`.
- **Text:** Edit `index.html` or `artist.html` directly.
- **After changes:** Run `git add .`, `git commit -m "Update"`, and `git push` to update the live site.
