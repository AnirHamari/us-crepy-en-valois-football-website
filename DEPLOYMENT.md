# 🚀 Deployment Guide - U.S. Crépy en Valois Football Website

## Quick Start - GitHub Pages Deployment

### Prerequisites
- GitHub account
- Git installed on your computer

### Step-by-Step Deployment

#### 1. Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** icon in the top right → **"New repository"**
3. Repository settings:
   - **Name**: `us-crepy-en-valois-football-website`
   - **Description**: "Official website for U.S. Crépy en Valois Football (FFF #500503)"
   - **Visibility**: Public
   - **DO NOT** check "Initialize with README" (we already have files)
4. Click **"Create repository"**

#### 2. Push Your Code to GitHub

Open terminal/command prompt in the project directory and run:

```bash
# Add GitHub as remote origin (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/us-crepy-en-valois-football-website.git

# Push to GitHub
git branch -M main
git push -u origin main
```

#### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** tab
3. In the left sidebar, click **"Pages"**
4. Under **"Source"**:
   - Select branch: **main**
   - Select folder: **/ (root)**
5. Click **"Save"**

#### 4. Access Your Website

After a few minutes, your website will be live at:
```
https://YOUR_USERNAME.github.io/us-crepy-en-valois-football-website/
```

GitHub will show you the URL in the Pages settings.

---

## 📝 Updating the Website

### Adding New Content

1. Edit the HTML files locally
2. Test changes by opening HTML files in your browser
3. Commit and push changes:

```bash
git add .
git commit -m "Description of your changes"
git push
```

Changes will appear on the live site within 1-2 minutes.

### Adding Images

1. Add images to `assets/images/` folder
2. Reference them in HTML: `<img src="assets/images/your-image.jpg" alt="Description">`
3. Commit and push

### Updating Match Results

Edit `matches.html` to add real match results from your competitions.

### Adding News

Edit `news.html` to add club announcements and updates.

---

## 🎨 Customization

### Changing Colors

Edit `styles.css` and modify the CSS variables in the `:root` section:

```css
:root {
  --color-blue-primary: #003B7A;    /* Main blue */
  --color-gold-primary: #FFD700;    /* Main gold/yellow */
  /* ... other colors */
}
```

### Adding Pages

1. Create new HTML file (e.g., `sponsors.html`)
2. Copy structure from existing page
3. Add link to navigation in all pages
4. Commit and push

---

## 🔧 Troubleshooting

### Website not showing up?
- Wait 2-3 minutes after enabling GitHub Pages
- Check that `index.html` is in the root directory
- Verify GitHub Pages is enabled in Settings → Pages

### Images not loading?
- Check file paths are correct (case-sensitive)
- Ensure images are in `assets/images/` folder
- Verify images were committed and pushed to GitHub

### Changes not appearing?
- Clear browser cache (Ctrl+F5 or Cmd+Shift+R)
- Wait 1-2 minutes for GitHub Pages to rebuild
- Check that changes were pushed: `git status`

---

## 📱 Testing

### Local Testing
Simply open `index.html` in your web browser to test locally.

### Mobile Testing
Use browser developer tools (F12) → Toggle device toolbar to test responsive design.

---

## 🆘 Support

For technical issues with the website:
- Check the README.md file
- Review HTML/CSS for errors
- Test locally before pushing to GitHub

For club-related content:
- Contact club administrators
- Update via Facebook page

---

## ✅ Checklist

- [ ] Create GitHub repository
- [ ] Push code to GitHub
- [ ] Enable GitHub Pages
- [ ] Verify website is live
- [ ] Add your own images
- [ ] Update match results
- [ ] Add news and announcements
- [ ] Share website URL with club members

---

**Your website will be live at:**
`https://YOUR_USERNAME.github.io/us-crepy-en-valois-football-website/`

Replace `YOUR_USERNAME` with your actual GitHub username.
