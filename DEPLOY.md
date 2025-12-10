# How to Deploy Your Portfolio on GitHub Pages

Follow these steps to deploy your portfolio website for free on GitHub Pages.

## Step 1: Create a GitHub Account (if you don't have one)
1. Go to [github.com](https://github.com)
2. Sign up for a free account

## Step 2: Create a New Repository
1. Click the "+" icon in the top right corner
2. Select "New repository"
3. Name it: `Portfolio_AmiraSofea` (or any name you prefer)
4. Make it **Public** (required for free GitHub Pages)
5. **DO NOT** initialize with README, .gitignore, or license
6. Click "Create repository"

## Step 3: Initialize Git in Your Project
Open Terminal and run these commands:

```bash
# Navigate to your project folder
cd /Users/aimarhaizzad/Portfolio_AmiraSofea

# Initialize git (if not already done)
git init

# Add all files
git add .

# Create your first commit
git commit -m "Initial commit: Portfolio website"

# Add your GitHub repository
git remote add origin https://github.com/amrasfea/Portfolio_AmiraSofea.git

# Rename branch to main (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
```

## Step 4: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

## Step 5: Access Your Website
- Your site will be available at:
  `https://amrasfea.github.io/Portfolio_AmiraSofea/`
- It may take a few minutes to deploy (usually 1-2 minutes)

## Future Updates
Whenever you make changes to your portfolio:

```bash
# Navigate to your project
cd /Users/aimarhaizzad/Portfolio_AmiraSofea

# Add changes
git add .

# Commit changes
git commit -m "Description of your changes"

# Push to GitHub
git push
```

Your site will automatically update within a few minutes!

## Important Notes
- Make sure your repository is **Public** for free hosting
- The main file must be named `index.html` (which you already have ✓)
- All images and files must be in the repository
- GitHub Pages supports custom domains if you want to use your own domain later

## Troubleshooting
- If your site doesn't load, wait 5-10 minutes and refresh
- Check the "Actions" tab in your repository for deployment status
- Make sure all file paths are relative (not absolute)

