# 🚀 Free Hosting Deployment Guide

## GitHub Pages Setup (Recommended)

### Step 1: Create GitHub Repository
1. Go to [github.com](https://github.com) and sign up/login
2. Click "New repository" (green button)
3. Repository name: `sanit-kothiya-portfolio`
4. Make it **Public** (required for free hosting)
5. Check "Add a README file"
6. Click "Create repository"

### Step 2: Upload Files
1. In your new repository, click "uploading an existing file"
2. Drag and drop ALL files from this folder:
   - `index.html` (your main portfolio)
   - All `.png` image files (game screenshots)
   - `README.md`
3. Add commit message: "Initial portfolio upload"
4. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. Go to repository **Settings** tab
2. Scroll down to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Select "main" branch and "/ (root)" folder
5. Click "Save"
6. Your site will be available at: `https://yourusername.github.io/sanit-kothiya-portfolio`

## Alternative: Netlify (Even Easier)

### Option A: Drag & Drop
1. Go to [netlify.com](https://netlify.com)
2. Sign up for free account
3. Drag your entire portfolio folder to the deploy area
4. Get instant live URL!

### Option B: GitHub Integration
1. Connect your GitHub account to Netlify
2. Select your repository
3. Auto-deploy on every update

## Custom Domain (Optional)
- Buy domain from Namecheap, GoDaddy, etc.
- Point DNS to your hosting provider
- Get professional URL like `sanitkothiya.com`

## 🎯 Quick Start Commands
```bash
# If you have Git installed:
git init
git add .
git commit -m "Initial portfolio"
git remote add origin https://github.com/yourusername/sanit-kothiya-portfolio.git
git push -u origin main
```

## 📱 Mobile Testing
- Test your portfolio on mobile devices
- Ensure all images load properly
- Check responsive design

## 🔧 Troubleshooting
- **Images not loading**: Check file paths are correct
- **Styling issues**: Ensure CSS is properly linked
- **Mobile issues**: Test responsive design

---
**Need help?** Contact: sanit.kothiya@gmail.com
