# Deployment Guide

This guide explains how to deploy the Island Code for Locals website to GitHub Pages.

---

## Prerequisites

Before deploying, make sure you have:
- A GitHub account ([github.com](https://github.com))
- Git installed on your computer (or use GitHub Desktop)
- All website files ready (index.html, styles.css, script.js)

---

## Method 1: Using GitHub Desktop (Easier for Beginners)

### Step 1: Install GitHub Desktop

1. Go to [desktop.github.com](https://desktop.github.com)
2. Download and install GitHub Desktop
3. Sign in with your GitHub account

### Step 2: Create a New Repository

1. Open GitHub Desktop
2. Click "File" → "New Repository"
3. Name it: `island-code-for-locals` (or your preferred name)
4. Choose a location on your computer
5. Add description: "Island Code for Locals website"
6. Make sure "Initialize this repository with a README" is unchecked
7. Click "Create Repository"

### Step 3: Add Your Files

1. Copy all your website files into the repository folder:
   - `index.html`
   - `styles.css`
   - `script.js`
   - Any other files (images, etc.)

2. In GitHub Desktop, you should see your files listed under "Changes"

3. Write a commit message: "Initial website deployment"

4. Click "Commit to main"

### Step 4: Publish to GitHub

1. Click "Publish repository"
2. Make sure "Keep this code private" is unchecked (for public website)
3. Click "Publish repository"
4. Wait for files to upload

### Step 5: Enable GitHub Pages

1. Go to [github.com](https://github.com) in your web browser
2. Find your repository (click your username, then the repository name)
3. Click the "Settings" tab
4. Scroll down to "Pages" in the left sidebar
5. Under "Source", select "Deploy from a branch"
6. Choose "main" branch and "/ (root)" folder
7. Click "Save"

### Step 6: Your Website is Live!

1. Wait 1-2 minutes for GitHub to build your site
2. Go back to Settings → Pages
3. You'll see a link like: `https://yourusername.github.io/island-code-for-locals`
4. Click the link - your website is online!

---

## Method 2: Using Git Command Line (Advanced)

### Step 1: Install Git

**Windows:** Download from [git-scm.com](https://git-scm.com)
**Mac:** Usually pre-installed, or install via Homebrew
**Linux:** `sudo apt-get install git`

### Step 2: Create Repository on GitHub

1. Go to [github.com](https://github.com)
2. Click the "+" icon → "New repository"
3. Name it: `island-code-for-locals`
4. Make it public
5. Don't initialize with README
6. Click "Create repository"

### Step 3: Initialize Git Locally

Open terminal/command prompt in your website folder:

```bash
git init
git add .
git commit -m "Initial commit"
```

### Step 4: Connect to GitHub

```bash
git remote add origin https://github.com/yourusername/island-code-for-locals.git
git branch -M main
git push -u origin main
```

### Step 5: Enable GitHub Pages

Follow Step 5 from Method 1 above.

---

## Method 3: Upload Files Directly (Simplest)

### Step 1: Create Repository

1. Go to [github.com](https://github.com)
2. Click "+" → "New repository"
3. Name it and create it

### Step 2: Upload Files

1. Click "Add file" → "Upload files"
2. Drag and drop your files:
   - `index.html`
   - `styles.css`
   - `script.js`
3. Click "Commit changes"

### Step 3: Enable GitHub Pages

Follow Step 5 from Method 1 above.

---

## Updating Your Website

### Using GitHub Desktop:

1. Edit your files on your computer
2. Open GitHub Desktop
3. You'll see changes listed
4. Write a commit message describing what changed
5. Click "Commit to main"
6. Click "Push origin"
7. Wait 1-2 minutes - your website updates automatically!

### Using Command Line:

```bash
git add .
git commit -m "Updated website"
git push
```

---

## Custom Domain (Optional)

If you want to use `islandcodeforlocals.com` instead of `username.github.io`:

### Step 1: Buy Domain

- Purchase domain from Namecheap, GoDaddy, or similar
- Keep domain registrar information handy

### Step 2: Configure DNS

1. In your domain registrar, add DNS records:
   - Type: `CNAME`
   - Name: `@` or `www`
   - Value: `yourusername.github.io`

2. In GitHub repository Settings → Pages:
   - Add your custom domain
   - Enable "Enforce HTTPS" (wait for DNS to propagate)

### Step 3: Wait

- DNS changes can take 24-48 hours
- Check if it's working: visit your domain

---

## Troubleshooting

### Website shows "404 Not Found"

**Possible causes:**
- Files not in root folder
- Wrong branch selected
- `index.html` not named correctly

**Solutions:**
- Make sure `index.html` is in the main folder
- Check Settings → Pages → Source is set to "main" branch
- Wait a few minutes and refresh

### Changes not appearing

**Solutions:**
- Make sure you clicked "Push origin"
- Wait 1-2 minutes for GitHub to rebuild
- Hard refresh browser (Ctrl+F5 or Cmd+Shift+R)
- Check if you're looking at the right URL

### CSS/JS not loading

**Solutions:**
- Check file paths in HTML are correct
- Make sure files are in same folder
- Check file names match exactly (case-sensitive)

### GitHub Pages not enabled

**Solutions:**
- Make sure repository is public (or you have GitHub Pro for private)
- Check you're in Settings → Pages
- Make sure you selected the right branch

---

## Testing Before Deployment

### Local Testing:

1. Open `index.html` in your browser
2. Check all links work
3. Test on mobile (reduce browser window size)
4. Test contact form
5. Check for console errors (F12 → Console)

### After Deployment:

1. Visit your live URL
2. Test on different devices
3. Ask friends to test
4. Check loading speed
5. Test all links and forms

---

## Security Considerations

**For public websites:**
- Don't put sensitive information in code
- Don't commit passwords or API keys
- Use environment variables for secrets (advanced)

**For contact forms:**
- Current form uses mailto (best for simple sites)
- Consider using Formspree, Netlify Forms, or similar for production

---

## Performance Tips

**Optimize images:**
- Compress images before uploading
- Use appropriate formats (JPG for photos, PNG for graphics)
- Keep file sizes under 500KB when possible

**Minimize files:**
- Remove unnecessary code
- Use compressed CSS/JS for production (advanced)

---

## Backing Up

**Always backup:**
- Keep local copies of files
- GitHub automatically backs up your code
- Consider downloading ZIP of repository periodically

---

## Additional Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Desktop Guide](https://docs.github.com/en/desktop)
- [Custom Domain Setup](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

---

## Need Help?

Contact guillaume@islandcodeforlocals.com if you encounter issues deploying your website.

